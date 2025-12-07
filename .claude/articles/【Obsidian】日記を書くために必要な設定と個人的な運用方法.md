---
title: 【Obsidian】日記を書くために必要な設定と個人的な運用方法
source: https://iketerumens.com/obsidian-journal/
published: 2022-07-27
created: 2025-08-20
description: 各種日記アプリやNotionなど多くのアプリで日記を書いてきましたが、ついにObsidianで運用していくことで決着がついた感じがあります。個人的にObsidianで日記を書くことによって普段あまり見返すことのない日記を定期的に見直すシステムを作れるということが一番デカいです。
updated: 2025-08-20 13:17
---
1. [HOME](https://iketerumens.com/)
2. 【Obsidian】日記を書くために必要な設定と個人的な運用方法

2022年7月27日

![obsidian - 日記](https://iketerumens.com/wp-content/uploads/2022/08/ce4c8c096cde6ef5176f02c1be9008f8.webp)

obsidian - 日記

各種日記アプリやNotionなど多くのアプリで日記を書いてきましたが、ついにObsidianで運用していくことで決着がついた感じがあります。  
  
Obsidianで日記を書くにあたって他のアプリと異なる点や、個人的な運用方法を紹介するのでぜひご参考ください！  
  
（以下書籍にインスパイアされ、この記事を書いています。）

目次
1. [Obsidianで日記を書くことの効用](https://iketerumens.com/obsidian-journal/#index_id0)
	1. [振り返りを自動的に行うことができる](https://iketerumens.com/obsidian-journal/#index_id1)
	2. [Zettelkasten内のメモと日記をリンクさせることができる](https://iketerumens.com/obsidian-journal/#index_id2)
	3. [その日読んだ記事の管理が異常に楽](https://iketerumens.com/obsidian-journal/#index_id3)
2. [デイリーノート(日記)に必要なプラグイン](https://iketerumens.com/obsidian-journal/#index_id4)
	1. [Calender](https://iketerumens.com/obsidian-journal/#index_id5)
	2. [Templater](https://iketerumens.com/obsidian-journal/#index_id6)
3. [個人的なデイリーノート(日記)のテンプレートと続けるコツ](https://iketerumens.com/obsidian-journal/#index_id7)
	1. [日・週・月ごとに振り返る](https://iketerumens.com/obsidian-journal/#index_id8)
	2. [4行日記のテンプレート](https://iketerumens.com/obsidian-journal/#index_id9)
	3. [1日の終わりではなく、思いついたら書いていくメモ的なスタイル](https://iketerumens.com/obsidian-journal/#index_id10)
4. [Obsidianで日記を書くことについてのまとめ](https://iketerumens.com/obsidian-journal/#index_id11)
5. [参考文献](https://iketerumens.com/obsidian-journal/#index_id12)
6. [noteでも情報発信中](https://iketerumens.com/obsidian-journal/#index_id13)

## Obsidianで日記を書くことの効用

Obsidianでノートを書くメリットはノート同士をリンクさせ、一見なんとも言えないアイデア同士に繋がりを見出すことですが、Obsidianで日記を書くことによって普段あまり見返すことのない日記を定期的に見直すシステムを作れるということが一番デカいです。

### 振り返りを自動的に行うことができる

後ほど紹介する「Calender」というプラグインでデイリーノート(日記)とウィークリーノートを管理しているので、以下画像のようにカレンダーの日にちをタップするだけでその日のデイリーノートを作成できます。

![Obsidian - デイリーノート(日記) Calender](https://iketerumens.com/wp-content/uploads/2022/08/obsidian-calender.webp)

Obsidian - デイリーノート(日記) Calender

そうして書き溜めたデイリーノートを週ごとに振り返る際に、ウィークリーノートを作成します。ウィークリーノートもデイリーノートと同じように左のWの欄にある数字をクリックすると簡単に作成できます。  
  
以下画像が個人的なウィークリーノートの一部になっていますが、このようにその週に書いたデイリーノートがリンクされ、半自動的に振り返れるようになっています。  
  
例えば、2022-W30のウィークリーノートには7/18 ~ 7/24までのデイリーノートがリンクされ、そのノート内で全て内容を確認することが可能です。

![Obsidian - ウィークリーノート](https://iketerumens.com/wp-content/uploads/2022/07/obsidian-weekly-note-1024x1009.webp)

Obsidian - ウィークリーノート

Notionでもリレーション機能を使うことで日記をウィークリーノートにリンクさせることができましたが、このようにノートの画面内で振り返りを完結することはできないので、個人的にここがObsidianを使う最大のメリットかなと思います。

### Zettelkasten内のメモと日記をリンクさせることができる

日記を書く中でZettelkasten内のメモと関連づいていると感じた場合にはすぐにリンクさせることが可能です。  
  
無理にメモをリンクさせる必要はありませんが、日記同士の振り返りだけでなく、Zettelkastenともリンクさせることで振り返りの機会を増やすことに繋がります。  
  
ただし、日記は日記、ZettelkasteはZettelkastenと分けた方が役割は明確になるので「第二の脳は知識のデータベースで感情や出来事は混ぜたくない」という方はリンクは避けた方が無難でしょう。

![](https://iketerumens.com/wp-content/uploads/2022/08/zettelkasten-1-300x157.webp)

### その日読んだ記事の管理が異常に楽

「Auto Link Title」というプラグインを導入することで外部リンクをめちゃくちゃ簡単に入れることができます。  
  
以下画像のようにリンクをそのまま貼り付けるとFetching Title(タイトル取得中)と表示され、しばらく経つと

![Obsidian - Auto Link Title -1](https://iketerumens.com/wp-content/uploads/2022/07/obsidian-autolink-1024x377.webp)

Obsidian - Auto Link Title -1

以下のようにタイトルを表示してくれるようになります。

![Obsidian - Auto Link Title -2](https://iketerumens.com/wp-content/uploads/2022/07/obsidian-autolink2-1024x351.webp)

Obsidian - Auto Link Title -2

個人的に外部リンクを貼り付ける際にタイトルとURLをコピーして貼り付けるといった作業がだるすぎて読んだ記事の記入を怠るといったことが多かったのですが、このプラグインのおかげでそれも無くなりました。  
  
Obsidianコミュニティの開発者すごい。

## デイリーノート(日記)に必要なプラグイン

以下の二つはObsidianで日記を運用する際にはほぼ必須のプラグインです。

### Calender

サードパーティプラグインから「Calender」をインストールします。  
  
これによって右サイドバーにカレンダーが表示されるようになり、前述したデイリーノートとウィークリーノートを作成できるようになります。  
  
また、\[Words par dot\]という項目を設定することで日記に書いた文字数に応じてドットの数が増えていきます。  
  
これも結構モチベーションになるので初期値を250から30ぐらいに変更しておきましょう。

### Templater

こちらの「Templater」もサードパーティプラグインからインストールします。  
  
このプラグインによってデイリーノートに先週や先月のノートとリンクされるテンプレートが挿入されるようになり、時代を超えた振り返りが可能に。自分が利用している実際のテンプレートのコードは次の章で紹介します。  
  
個人的にObsidianで日記を運用する決め手となったプラグインなのでぜひ導入してみてください。

## 個人的なデイリーノート(日記)のテンプレートと続けるコツ

### 日・週・月ごとに振り返る

個人的には以下のリンクをテンプレート化して全てのデイリーノートに挿入し、振り返りのきっかけになるようにしています。

- 日: 前日と後日のノート
- 週: 先週と次週のノート
- 月: 先月と来月のノート
- 年: 去年と来年の同じ日のノート

同じテンプレートを使いたい方は以下コードをそのままコピペしてください。

```
日: [[<% tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD") %>]] | [[<% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>]]
週: [[<% tp.date.now("YYYY-MM-DD", -7, tp.file.title, "YYYY-MM-DD") %>]] | [[<% tp.date.now("YYYY-MM-DD", 7, tp.file.title, "YYYY-MM-DD") %>]]
月: [[<% tp.date.now("YYYY-MM-DD", "P-1M", tp.file.title, "YYYY-MM-DD") %>]] | [[<% tp.date.now("YYYY-MM-DD", "P1M", tp.file.title, "YYYY-MM-DD") %>]]
年: [[<% tp.date.now("YYYY-MM-DD", "P-1Y", tp.file.title, "YYYY-MM-DD") %>]] | [[<% tp.date.now("YYYY-MM-DD", "P1Y", tp.file.title, "YYYY-MM-DD") %>]]
```

![Obsidian - 振り返りノートテンプレート](https://iketerumens.com/wp-content/uploads/2022/08/obsidian-reflect.webp)

Obsidian - 振り返りノートテンプレート

こんな感じで表示されるようになります。

### 4行日記のテンプレート

１日を「事実」「発見」「教訓」「宣言」の4つで振り返っていく日記の手法。  
  
4行日記ということで一つの項目に1行だけ書いていけばいいので、何を書くか考えるハードルと多く書かなければという心理的ハードル両方を下げてくれるので日記を書く習慣が身に付きます。  
  
個人的にもこの形にテンプレートを変更してから日記が続くようになりました。

### 1日の終わりではなく、思いついたら書いていくメモ的なスタイル

日記といえば、一日の終わりに時間を取って書くものだとつい思い込んでしまいがちです。  
  
それで書くのを忘れてしまったり、疲れて書けなくて結果的に続かないことになってしまうのが典型的な失敗パターンで自分も何度も挫折してきました。  
  
これを解決するために常に日記を書ける状態にしておいて、思いついたこと、メモしたいこと、感じたことがあればその場で書き込んでいくスタイルにしてみました。  
  
人間は進捗が予定通りに進んでいる時にモチベーションが上がったり、既に何か手をつけているものを完成させたい(ツァイガルニク効果)という心理が働くので「先に手をつけておく」というのは非常に効果がある方法なんでしょう。  
  
リアルタイムで感情を書き込んでいくことによって鮮度の高い感情を書き残すことにも繋がります。  
  
日記が続かないという人は「思いついたらその場で日記(メモ)を書く」を試してみてください。  
  
また書き溜めたメモを「エバーグリーンノート」に進化させる方法については以下の記事をご参考ください。

![](https://iketerumens.com/wp-content/uploads/2022/08/a64de4d96f039066382e64dbf989acf7-300x157.webp)

## Obsidianで日記を書くことについてのまとめ

- 振り返りを自動的に行えるようになる
- 「Calender」と「Templater」が必須のプラグイン
- 日記を無理なく続けるには4行日記のテンプレートを使う
- 1日の終わりではなく、思いついたら日記に書き加えていく

## 参考文献

- [Obsidianでつなげる情報管理術](https://amzn.to/3VHjqdn)
- [世界は「日記」でできている: 自分の人生を取り戻す21の日記の技法](https://amzn.to/3isTOlS)

## noteでも情報発信中

実際に試したAIツールや知的生産手法、暗号資産の最新動向などをnoteで公開しています。SEOをガン無視して、ガチの個人的に厳選した内容をシェアしているのでぜひチェックいただけると！今後の読書まとめや映画の感想などもこちらのnoteで公開していく予定です！

また、最新情報はXで発信しているので、Xとnoteもフォローしてもらえると嬉しいです！発信されている方はどちらもフォロバします！仲良くしてください！

![](https://assets.st-note.com/poc-image/manual/production/default_top_ogp_202212.png)

[Tweets by lifeoptimizer7](https://twitter.com/lifeoptimizer7?ref_src=twsrc%5Etfw)

![obsidian - 日記](https://iketerumens.com/wp-content/uploads/2022/08/ce4c8c096cde6ef5176f02c1be9008f8-300x157.webp)

obsidian - 日記

この記事が気に入ったら  
フォローしてね！

- [「権力に翻弄されないための48の法則 上」【まとめ】| 究極のサバイバル処世術](https://iketerumens.com/the-48-lows-of-power-part1/)
- [「Sleep Cycle」 無料版を2週間使ってみた結果【最強の睡眠改善アプリ】](https://iketerumens.com/sleep-cycle-two-weeks-results/)

## この記事を書いた人

## 関連記事

- [
	![Notion × 筋トレ](https://iketerumens.com/wp-content/uploads/2023/08/5d38982f84a683f9303e13fcd88c6371-300x157.webp)
	Notion × 筋トレ
	【Notion】筋トレ管理テンプレートの作り方 | 自動でボリュームまで計算
	](https://iketerumens.com/notion-workout-template/)
- [
	![Raindorp×Notion - Webクリップの最適解](https://iketerumens.com/wp-content/uploads/2023/07/02fe1ed836b80635dea22f4590da1002-300x157.webp)
	Raindorp×Notion - Webクリップの最適解
	【Webクリップの最適解】RaindropとNotionでインプット情報の完全整理
	](https://iketerumens.com/web-clip-raindrop-and-notion/)
- [
	![Obsidian Git - ローカルとクラウドのハイブリッド型ノートアプリ](https://iketerumens.com/wp-content/uploads/2023/03/ebc69b0d24e1713485d530e2f7790316-300x157.webp)
	Obsidian Git - ローカルとクラウドのハイブリッド型ノートアプリ
	ObsidianのノートをGithubにバックアップする方法
	](https://iketerumens.com/obsidian-git/)
- [
	![Obsidian 使い方大全 - リンク思考を身につける](https://iketerumens.com/wp-content/uploads/2023/03/a05dabe8449962df190fd6a55615a69a-300x157.webp)
	Obsidian 使い方大全 - リンク思考を身につける
	【2024年最新版】Obsidian使い方大全 – 最強ノートアプリで第二の脳を構築する
	](https://iketerumens.com/obsidian/)
- [
	![最強のブックマーク管理アプリ【Raindrop.io】の使い方 | ブックマーク界の超新星](https://iketerumens.com/wp-content/uploads/2023/03/cd5b872da8f196dce3eb3327ae1a681d-300x157.webp)
	最強のブックマーク管理アプリ【Raindrop.io】の使い方 | ブックマーク界の超新星
	最強のブックマーク管理アプリ【Raindrop.io】の使い方 | ブックマーク界の超新星
	](https://iketerumens.com/raindrop-intro/)
- [
	![運用ワークフロー 【情報収集編】](https://iketerumens.com/wp-content/uploads/2023/02/25fecc9dea7d3aaed72385e8f4137de4-300x157.webp)
	運用ワークフロー 【情報収集編】
	Webクリップのワークフロー構築【情報収集編】| Inoreader + Raindrop
	](https://iketerumens.com/webclip/)