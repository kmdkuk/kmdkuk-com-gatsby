---
layout: post
title: 先週末いろいろと参加してきた
date: 2019-05-21 18:44 +0900
tags:
  - Diary
---

先週末の土日にいろいろと学内のイベントがあったのでそれらに参加してきたメモ

- [未来大 × 企業エンジニア 春の LT 大会](https://fun.connpass.com/event/127784/)
- AWS ハンズオン
- [【ふるさと開催】TDD+モブプログラミングでワイワイする会 その 24](https://tddyyx.connpass.com/event/128503/)

## 未来大 × 企業エンジニア 春の LT 大会

まずは，土曜日(2019/5/18)に行われた春の LT 大会ですね．
これは，未来大に企業の人と学生で LT 大会しようという，今回で第 2 回になるのかな？ちょっとづつ学内のこういったイベントが恒例になってきてとても嬉しいお気持ちとありがたいお気持ちですね．

基本こういったわざわざ函館で開いてくれるようなイベントには，せっかく開催して頂いてるしとりあえず良いか悪いかおいておいて参加しよう精神で参加しています．結果，今回のイベントもとてもおもしろくて参加してとても良かったなあと感じました．それに，イベント参加者総数 120 人くらい？と風のうわさで聞いてすごおという感想しか出てきません．

中でも，印象的だった LT は 3 つですかね．

### エスパー力を高める ~ソフトウェアの問題解決の技術~

これは，Ruby 開発者としてもとても有名な GMO ペパボから来ていただいた@hsbt さんの LT でした．

スライドは[こちら](https://speakerdeck.com/hsbt/how-to-become-the-psychic?slide=9)\
URL 貼ってまずかったら教えてください．．．

まず，なんと言っても「あ，本物だ」とほんとにただただ有名人を見た感想ですね笑

さて，LT の中身ですが，タイトルにもあるように，エスパー力についての LT でした．
すごいエンジニアっていうのは，エラーメッセージ見ただけで直すべき場所がわかったり，触ったことないソフトウェアの使い方がわかったりして，超能力者(エスパー)にしか見えない．そういったエスパーに見える力って実は技術なんですよ．っていうお話でした．

そのエスパーみたいな技術を習得するために 3 つのポイントを上げて解説していました．

- ソフトウェアの特性を知る
- 期待している振る舞いを知る
- 中身を知る
  この 3 点のポイントを抑えておくとエスパー力が高まって捗るらしい!

10 分で話を聞くには，とても内容の濃いものでもう少しもう少しお話を聞いていたかったです．残念．
特に，印象に残った言葉として"人を知ると高速にソフトウェアを理解できる"これが，このお話を聞いたなかで一番なるほどなと思えました．
作っている人を知ることで，どんなソフトウェアの振る舞いをするか予測することができるようになると
今までは，そこまで自分自身この人が書いたソフトウェア，ライブラリみたいに書いた人を意識しながらソフトウェアを見てこなかったのでとても参考になりました．
僕もエスパー力高めていきたい．．

### 動かして理解する Git の内側

この LT は，同期で Cookpad で活躍している@natmark の LT です！
さすが，つよつよ過ぎて同期というのも恐れ多い内容の濃い LT だったなあと

スライドは[こちら](https://speakerdeck.com/natmark/dong-kasiteli-jie-surugitfalsenei-ce)

普段なんとなく Git を使ってますが，Git がどんなことをしてそのバージョン管理を行っているかなんて考えたことがなかったので新鮮でした．

しかも，どういう挙動をしているか.git を更に git init して見てみるというアプローチもなにそれおもしろという感じで
さすが swift で Git を開発してるだけあるなと([gift](https://github.com/natmark/Gift))，

今回の LT の中で一番技術的にワクワクしながら見ることができた LT でした．
自分で手を動かしてみてもっと知りたいなと純粋に思いました．

### わざわざ学ばなくて良い言語第 1 位をわざわざ学ぶ理由

この LT は Baho 猫@takachan-mirai の Elm は良いぞというものでした．
なんと言っても発表の仕方が面白かった．

スライドは[こちら](https://speakerdeck.com/baho/wazawazaxue-banakuteliang-iyan-yu-di-1wei-wowazawazaxue-buli-you)

話の流れとしては，Elm はわざわざ学ばなくて良い言語 2019 の第 1 位になっているが，その観点として市場価値が基準として選ばれている．それってほんとに学ぶ価値がないと言えるの？っていうところから問題提起されていて，学習者として学ぶためなら Elm って良いんじゃない？っていうのがちょっとした茶番を混ぜつつおもしろおかしく詰まってました．

僕も Elm でママみを感じに行きたい(やりたいことのキューに入ったけど Elm がいつデキューされるかわからない)

### 感想

企業の方々がすごい得になる話をもってきて頂いてたなと思ったのはもちろん，学部 1 年生の人たちもすんごく中身のしっかりしてうまい LT をしていたのが印象的でした．
僕もある意味では，同じ 1 年生ですが，単純計算 4 つも下の人たちに負けていられないと感じました．(年齢が全てとは言わないとよく言いますがそれでも，4 年も多く生きてる分負けてられないと感じたわけです．)
次のこのような機械では聞くだけじゃなくて自分から発信したいなあ．

## AWS ハンズオン

こちらのイベントは，VoyageGroup の三浦さん(@hironomiu)に開催していただいた AWS ハンズオンです．
内容としては，最初に EC2 上で DB と WordPress を同時に動かしている状態から，DB と WordPress を動かしているインスタンスを分離して垂直分散させたり，
DB を別のアベイラビリティゾーンにレプリカを作成して冗長化してみたり，
EC2 も別のアベイラビリティゾーンに立ててロードバランサを設定して水平分散させてみたりと
こんな感じにやったら教科書とかで言葉だけ聞いたことあるようなことが実際にできるよっていうのを感じ取ることができました．

内容の多さの割には時間が足りなくて，少々駆け足にはなってしまいましたが，AWS を実際に使ってこんな雰囲気でできるんだぞっていうのが感じ取れてとても良かったかなと思います．

(あと，全く関係ないけど WordPress が動いているのを初めて見たのですが，プラグインやらをインストールするのだったり管理画面がちゃんとしてたりと，なるほど WordPress みんな使うわけですわと感じましたまる)

## 【ふるさと開催】TDD+モブプログラミングでワイワイする会 その 24

こちらのイベントは，19 日の午後に行われた通称#tddyyχ と呼ばれるものです．

TDD とは，Test Driven Development の略でプログラムの実装前にテストコードを書いて，そのテストが成功するように実装とリファクタリングを進めていく開発手法です．

モブプログラミングは，一人のドライバーがコードを書いていって，ナビゲータと呼ばれる複数人の人がドライバーの書くコードのバグを仕込まないように注意したり，先回りして調べたりして，複数人が 1 台のパソコンに向かってコードを書いていくことでいろいろな良いことがあるんじゃない？というプラクティス？です．

正直，TDD もモブプロも初めてだったのでどんなもんかなと不安だったのですが，ワイワイする会というだけあってとても楽しめました．

今回は，簡単なお題に取り組んで，とりあえずやってみようみたいな感じだったのですが，その御蔭で TDD とモブプログラミングの雰囲気を掴むことができたかなと思います．

やっている中でとても感じたのは，同じコードに対して，複数人で取り組むので，一つづつテストを増やしていくことでこのコードがどこまで動くのかという理解している地点の共有をしながら進めることができたり，それぞれの人がどんなことを考えながらコードを書いているのかがわかったりして，とても新鮮な経験ができたかなとおもいました．

あとは，モブプログラミングのいいところか悪いところかわかりませんが，話が軽く脱線したりして，技術的な話ではあるけれど自然な雑談みたいなものが発生したりしていて，アイスブレイクする方法としてもちょっとおもしろいんじゃないかなと感じました．

バイトや学校の演習でチーム開発をする機会が多いので，そこに TDD+モブプログラミングをもっていけると良いなあと感じましたね．

## 感想

全体を通して，18~19 の二日間で函館で 3 つも技術的なイベントに参加できてとても良かったです．
函館にいると，やっぱり東京と違って人が集まりにくくしてイベントがそもそも開催されないので，開催されたときには積極的にまた参加していきたいなと思っています．
また，別のイベントが開催されたときには，もっと能動的にイベントに参加できるようにこれからも頑張っていきたいなと思いました．

3 つのイベントを運営していただいた各所にお礼申し上げます．

ありがとうございました．
