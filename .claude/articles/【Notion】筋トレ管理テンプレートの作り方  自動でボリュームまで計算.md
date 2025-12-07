---
title: 【Notion】筋トレ管理テンプレートの作り方 | 自動でボリュームまで計算
source: https://iketerumens.com/notion-workout-template/
published: 2023-08-19
created: 2025-08-20
description: 最近筋トレを本格的に再開したので以前Notionで作っていた筋トレテンプレートで記録していました。ただ、この筋トレテンプレートはボリューム（重量×レップ数）を自動計算するだけで、あとは手動でメニューや部位を打ち込んでいくというスマートでない
updated: 2025-08-20 12:13
---
2023年8月19日

![Notion × 筋トレ](https://iketerumens.com/wp-content/uploads/2023/08/5d38982f84a683f9303e13fcd88c6371.webp)

Notion × 筋トレ

最近筋トレを本格的に再開したので以前Notionで作っていた筋トレテンプレートで記録していました。  
  
ただ、この筋トレテンプレートはボリューム（重量×レップ数）を自動計算するだけで、あとは手動でメニューや部位を打ち込んでいくというスマートでないものでした。  
  
今回作った筋トレテンプレートはメニューを選択すると自動で鍛えられる部位を登録できるようにしてあります。  
  
「Notionで筋トレのテンプレートないかなー」と探している方はぜひ参考にしてください。

## Notionで作る筋トレ管理テンプレートの概要

### 想定読者: Notion普通に使ってますという筋トレをしている方

今回の筋トレテンプレートはデータベースを二つ作り、リレーションを貼って実現します。  
  
全くのNotionの初心者という方は他のブログやYoutubeでリレーションの貼り方をまずは確認すると良いかと思います。

## 筋トレテンプレートの作り方

まずは以下二つのデータベースを用意します。

1. メニュー・データベース
2. トレーニング・データベース

### 筋トレメニュー・データベース

![筋トレメニュー・データベース](https://iketerumens.com/wp-content/uploads/2023/08/workout-menu-1024x374.webp)

筋トレメニュー・データベース

事前に筋トレメニューを登録したデータベース。完成図はこんな感じ。  
  
作るカラムはシンプルで

- \[Genre\]  
	コンパウンド種目かアイソレーション種目かを選択する
- \[Part\]  
	鍛えられる筋肉群

上記二つのみ。  
  
\[Name\]としてある部分に筋トレのメニュー名を入力して、2つ目のデータベースと連携することで、わざわざ毎回トレーニングごとに「ベンチプレス」などと記録する必要がなくなります。

### 筋トレトレーニング・データベース

![筋トレトレーニング・データベース | テーブルビュー](https://iketerumens.com/wp-content/uploads/2023/08/workout_db-1024x543.webp)

筋トレトレーニング・データベース | テーブルビュー

こちらは毎回のトレーニングで利用するデータベース。  
  
こちらは作るカラムがやや多く、いくつか関数も必要になります。

- \[Weight\]  
	重量を入力。
- \[Reps\]  
	回数を入力。
- \[Vol\]  
	重量×回数の値を計算
- \[Created Time\]  
	データ作成時間を入力（インターバル時間・トレーニングにかかった時間が大体わかる）
- \[Date\]  
	日付を入力。
- \[Days\]  
	曜日をDateから算出。
- \[Month\]  
	月をDateから算出。
- \[Year\]  
	年をDateから算出。

\[Weight\]と\[Reps\]、\[Date\]の3つをトレーニングを終えるたびに入力する必要がありますが、あとは全て関数で設定しているカラムになるので自動で入力されます。  
  
Date以降3つのカラムは必須ではありませんが、年や月で絞り込んで筋トレ記録を振り返りやすくなるので、個人的にはあったほうが良いかと思います。

#### 各種関数の公式

**Vol**

```
prop("Weight") * prop("Reps")
```

**Days**

```
formatDate(prop("Date"), "dddd")
```

**Month**

```
formatDate(prop("Date"), "MMMM")
```

**Year**

```
formatDate(prop("Date"), "YYYY")
```

## 筋トレテンプレートの使い方

### カレンダービューでプログラム管理

![筋トレトレーニング・データベース | カレンダービュー](https://iketerumens.com/wp-content/uploads/2023/08/7c46e5e01e1ce348fe4f82b56458eb99-1024x555.webp)

筋トレトレーニング・データベース | カレンダービュー

基本的な運用方法は先ほど紹介したテーブルビューで年、月などでフィルタリングし、専用のページで1セットが終わるごとに記入していきます。  
  
このカレンダービューでは先週行ったトレーニングが一目でわかるので、先のトレーニングの予定を立てることが可能です。  
  
個人的には毎週の週次レビューの際に来週行う予定のトレーニングを全てこのカレンダービューに記入しておいており、「今日なんのトレーニングでどのぐらいの負荷でやるんだっけ？」という迷いを解消しています。

### 種目ごとにフィルタリング

![筋トレトレーニング・データベース | フィルタリング](https://iketerumens.com/wp-content/uploads/2023/08/df6bc8fc8ccdc1b09f2b88d3a822683c-1024x574.webp)

筋トレトレーニング・データベース | フィルタリング

種目ごとにフィルタリングをかけることで、以前のトレーニングの重量や回数を一目でわかるので、種目ごとの目標設定をする上では便利だと思います。

## まとめ: 筋トレノートはNotionで管理すべき

「筋トレノートを取って記録をつけるべき」と山本先生もおっしゃっていますが、ギークでナードな私たちはNotionでスマートに記録をつけ、技術によって脳筋トレーニーたちと戦っていきましょう。  
  
特に「予定を立てる」、「振り返る」ということにおいてはアナログでノートを取る時とは比べ物にならないぐらい効率的に行えると思うので、筋トレをしている方はぜひ今回の筋トレテンプレートを参考にしてみてください。

## noteでも情報発信中

実際に試したAIツールや知的生産手法、暗号資産の最新動向をnoteで公開しています。SEOをガン無視して、ガチの個人的に厳選した内容をシェアしているのでぜひチェックいただけると！今後の読書まとめや映画の感想などもこちらのnoteで公開していく予定です！

また、最新情報はXで発信しているので、Xとnoteもフォローしてもらえると嬉しいです！発信されている方はどちらもフォロバします！仲良くしてください！

![](https://assets.st-note.com/poc-image/manual/production/default_top_ogp_202212.png)

[Tweets by lifeoptimizer7](https://twitter.com/lifeoptimizer7?ref_src=twsrc%5Etfw)

![Notion × 筋トレ](https://iketerumens.com/wp-content/uploads/2023/08/5d38982f84a683f9303e13fcd88c6371-300x157.webp)

Notion × 筋トレ

この記事が気に入ったら  
フォローしてね！

- [【Webクリップの最適解】RaindropとNotionでインプット情報の完全整理](https://iketerumens.com/web-clip-raindrop-and-notion/)
- [引っ越して3ヶ月経ったのでコスパの良かった商品を12個紹介していく](https://iketerumens.com/great-cost-performance-item-for-newroom/)

## この記事を書いた人

## 関連記事

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
- [
	![](https://iketerumens.com/wp-content/uploads/2023/02/83143cc04b955c659272fbf9490bd1c8-300x157.webp)
	生産性を上げるワークフローの構築【情報整理編】| Notion + Obsidian + Good Notes5
	](https://iketerumens.com/life-log-workflow/)

保存