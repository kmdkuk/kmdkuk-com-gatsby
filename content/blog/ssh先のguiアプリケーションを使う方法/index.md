---
layout: post
title: SSH先のGUIアプリケーションを使う方法
date: 2019-11-19 18:22 +0900
tags:
  - Linux
---

# SSH 先の GUI アプリケーションを使う方法

SSH 先の強力なサーバでシミュレーションを動かして，手元でシミュレーションの動作を見たかったので，X11Forwarding を使った SSH 時の GUI アプリケーションを利用できる設定をしました．

## 環境

SSH Host: Ubuntu 18.04  
SSH Client: macOS Catalina Version 10.15.1

SSH 先は，Linux で OpenSSH を使っているのであれば，なんでも行けると思います．
SSH クライアントは，macOS だとひと手間必要です．こちらも Linux であれば，すんなり行けるはず．．．ただ，試したわけではないので不明
SSH に必要なあらゆる設定はできていて，普通の ssh はできていることとします．

## Host の設定

X11Forwarding はデフォルトでは許可されていないため，許可する設定を行います.

```sh
$ sudo vim /etc/ssh/sshd_config
X11Forwarding yes # この行がコメントアウトされていたりするので有効化してください
$ # sshdを再起動
$ sudo systemctl restart ssh.service
```

これをするだけで SSH 時に GUI アプリケーションを利用することができるようになります．

## Client の設定

Mac では,デフォルトで X Window System に対応していないため，XQuartz をインストールする必要があります

```sh
$ brew update
$ brew cask install xquartz
```

インストール後再起動をしてください．
その後，ssh 時に X11 を有効にするため，~/.ssh/config を追記します．

```sh
$ vim ~/.ssh/config
Host hogehoge
  HostName hogehoge
  User kmdkuk
  Port 22
  IdentityFile <IdentityFileへのPATH>
  XAuthLocation /opt/X11/bin/xauth
  ForwardX11Trusted yes
```

XAuthLocation, ForwardX11Trusted の行を追記してください．
これで準備完了です．

## 実行

```sh
$ -X をつけることで，X11Forwardが有効になります．
$ ssh -X hogehoge
$ firefox &
```

これで，リモートにインストールされている GUI アプリケーションが，Mac 上の xqurts で見ることができると思います．
