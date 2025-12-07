---
title: 【Webクリップの最適解】RaindropとNotionでインプット情報の完全整理
source: https://iketerumens.com/web-clip-raindrop-and-notion/
published: 2023-07-17
created: 2025-08-20
description: 以前Webクリップのワークフローを解説しましたが、もう完全にこのフローはぶっ壊れました。 RaindropもNotionもできることが多いというのもあって、良い感じの使い分けに困っており、それが原因でこのワークフローが破綻してしまったのだと思います。 その反省を生かして今回はこの2ヶ月ぐらい上手く行ってるどシンプルなRaindropとNotionだけを使うワークフローを紹介します。
updated: 2025-08-20 12:13
---
1. [HOME](https://iketerumens.com/)
2. 【Webクリップの最適解】RaindropとNotionでインプット情報の完全整理

2023年7月17日

![Raindorp×Notion - Webクリップの最適解](https://iketerumens.com/wp-content/uploads/2023/07/02fe1ed836b80635dea22f4590da1002.webp)

Raindorp×Notion - Webクリップの最適解

以前下記の記事でWebクリップのワークフローを解説しましたが、もう完全にこのフローはぶっ壊れました。  
  
RaindropもNotionもできることが多いというのもあって、良い感じの使い分けに困っており、それが原因でこのワークフローが破綻してしまったのだと思います。  
  
その反省を生かして今回はこの2ヶ月ぐらい上手く行ってるどシンプルなRaindropとNotionだけを使うワークフローを紹介します。

![](https://iketerumens.com/wp-content/uploads/2023/02/25fecc9dea7d3aaed72385e8f4137de4-300x157.webp)

## 前提: 多くの記事を読む必要はない

以前はRSSリーダーとかを使ってより多くの記事に触れて、多くの記事を読もうと思ってたのですが意味がないと気づきました。  
  
ニュース記事は毎日読んだところで大して自分の能力向上には繋がらないので、インプットの目的を「自己能力の向上」と捉えるなら効率の悪い行為になります。  
  
個人的なコンテンツの質として

ニュース記事 < 個人ブログ記事 < 良質なメディア記事 < 本

だと思っているので、限られた時間でインプット時間を捻出するなら本を読むのがベストだと言えます。  
  
ただ、毎回インプットの時間があるからといって読書をするメンタリティ、モチベーションの人はいないでしょう。（よっぽどの読書の変態でない限り）  
なので、読みたい・読む必要のある記事というのをRaindropなり何らかのアプリでストックしておき、読書以外のインプットの選択肢を常に持っておく必要があると考えています。

## Raindropを使わないことで起こる問題

でも記事をストックしておこうと思って、Twitterとかで良さそうな記事を見つけると、とりあえずChromeの新しいタブで開いて「後で読もー」って放置してませんか？  
  
そんな感じの「後で読もー記事」が大量に残ってタブ多すぎストレス問題になってませんか？  
  
これ私です。  
  
Pocketとかブックマークツールを使ったことないのでわかりませんが、この問題を解決することを目的にRaindropの運用方法を考えました。

## RaindropとNotionの役割

前回の記事では

- Raindrop: 永久保存
- Notion: お気に入りのWebメディアを保存

という形式で運用していましたが、現在はざっくり

- Raindrop: 後で読む記事・お気に入りのメディアなどを保存
- Notion: 永久保存

という形に変更しています。

### インプットのフローを簡略化

![Webクリップのワークフロー | シンプル化](https://iketerumens.com/wp-content/uploads/2023/07/92384829880a9ed47a981e0b456df5e8-1024x536.webp)

Webクリップのワークフロー | シンプル化

まず、インプットのフローをかなりシンプルにしました。  
  
前回はInoreaderで毎日大量の記事に目を通して、良いものはRaindropに保存して、Twitterやなんかで良いメディアを見つけたらNotionのWebサイトDBに保存する….というめんどくさいフローを作って満足していました。  
  
今回はざっくり、後で読むものはRaindrop、読み終わって永久保存したいものはNotionと完全に住み分けしたのでインプットの際にフローを考える必要がなくなりました。

### Randropのコレクション構成

![Raindrop - コレクション構成](https://iketerumens.com/wp-content/uploads/2023/07/315cc858bb94784908e19b43188dd826-1024x312.webp)

Raindrop - コレクション構成

総じて『後で読む記事』を保存していきますが、「Twitterで見つけた面白そうな個人ブログの記事」や「本の代わりになるような骨太の解説記事」など粒度はまちまちです。  
  
使い方として、コレクション構成は以下のようにしており、タグは使っていません。

- Unsorted(未整理)
- When I have time(時間があるときにじっくり読む)
- Document(公式ドキュメントなど)
- Tools(便利なWebサービス)
- Web Media(お気に入りのビジネスメディア)
- Hobby(お気に入りの趣味メディア)

RaindropでURLを入力すると自動的に\[Unsorted(未整理)\]コレクションに入ってくれるので「後で読む記事」はここで管理していきます。  
  
\[When I have time(時間があるときにじっくり読む)\]コレクションでは後で読もうと思うんだけど優先順位が低いもの、例えば現在はLaravelを学習しているけど将来的に学びたいDockerで話題の記事などがここに入ってきます。  
  
\[Document\]コレクションはそのままでLaravel公式や日本語ドキュメントなど各言語やFW、体系化されたマニュアルが入ります。  
  
\[Tools\]コレクションには便利なWebサービスが入ります。例えば [バフェット・コード](https://www.buffett-code.com/) や [The 社史](https://the-shashi.com/) などを自分は入れています。  
  
\[Web Media\]、\[Hobby\]についてはそのままで好きなWebメディア（例えば [アプリマーケティング研究所](https://appmarketinglabo.net/) ）、好きなスポーツなどのメディア（など）を入れています。  
  
場合によってはさらに細分化しても良いですが、ここ2ヶ月ぐらいはこの6つのコレクションでうまくいっております。

### NotionのDB構成

![Notion - Web ClipのDB構成](https://iketerumens.com/wp-content/uploads/2023/07/notion-webclip-db-1024x536.webp)

Notion - Web ClipのDB構成

こうして無事読み終わった記事をNotionに保存するか否か判定します。  
  
一つ保存の仕方として工夫した点として「DBを分離させる」ということを行いました。  
  
以前はNotionに『WebクリップDB』という全ての記事を保存する巨大なDBを一つ用意していましたが、現在は各カテゴリーごとにそれぞれDBを作り、データの肥大化を避けるようにしています。  
  
これによってカテゴリーやタグなどプロパティの設定もさらに細分化したものを設定できますし、各DBのデータ量が減るので単純に検索性が上がります。

### Raindrop → Notionの流れ

ここまで紹介したインプットからWebクリップまでの例をステップ形式で一つ紹介しておきます。

1. 通勤電車でTwitterをいじっている時に良さげな「タスク管理」についての記事を見つける
2. すぐに読めそうなのでRaindropに追加し、\[Unsorted(未整理)\]コレクションに入れておく
3. 帰りの電車で疲れたので本を読む気にはなれず、さっき見つけた記事を読むことに決める
4. Raindropに行って、\[Unsorted(未整理)\]コレクションから先ほどの「タスク管理」についての記事をクリックし読む
5. めちゃくちゃ良かったので永久保存すると決める
6. Notionの\[Productivity Articles DB(生産性記事のデータベース)\]に保存
7. 週末にNotionからその記事を再度開いて、実際にやってみる

## まとめ: 厳選して記事を保存していくということ

Raindropで「後で読む記事」を選択するときも、Notionで「永久保存する」と選択するときも厳選するということを自分は重視しています。  
  
エンジニアならドキュメントは一通り読んでおくべきだし、本も積読はしているし、Youtubeの解説動画も見なきゃだし、購入したUdemyの講座も進めなきゃだし、サブスクしている有料メディアの記事も読まないといけない。  
  
そんな中であれもこれも\[後で読む\]としているとどんどん記事が溜まり、その分知らんうちに「まだこんな読まなきゃいけない記事がある…」とストレスが溜まります。  
  
精読して、自分の言葉でまとめたり、読み返したりすることでインプットが「自己能力の向上」につながってくれるので、まずは『読むべき記事の数を減らすこと』その次に『読んだ中でも後世に残したいと思うレベルの記事のみを保存すること』。  
  
この2つを注意すれば良いインプットライフを送れるのではないでしょうか。

## noteでも情報発信中

実際に試したAIツールや知的生産手法、暗号資産の最新動向をnoteで公開しています。SEOをガン無視して、ガチの個人的に厳選した内容をシェアしているのでぜひチェックいただけると！今後の読書まとめや映画の感想などもこちらのnoteで公開していく予定です！

また、最新情報はXで発信しているので、Xとnoteもフォローしてもらえると嬉しいです！発信されている方はどちらもフォロバします！仲良くしてください！

![](https://assets.st-note.com/poc-image/manual/production/default_top_ogp_202212.png)

[Tweets by lifeoptimizer7](https://twitter.com/lifeoptimizer7?ref_src=twsrc%5Etfw)

![Raindorp×Notion - Webクリップの最適解](https://iketerumens.com/wp-content/uploads/2023/07/02fe1ed836b80635dea22f4590da1002-300x157.webp)

Raindorp×Notion - Webクリップの最適解

この記事が気に入ったら  
フォローしてね！

- [ObsidianのノートをGithubにバックアップする方法](https://iketerumens.com/obsidian-git/)
- [【Notion】筋トレ管理テンプレートの作り方 | 自動でボリュームまで計算](https://iketerumens.com/notion-workout-template/)

## この記事を書いた人

## 関連記事

- [
	![Notion × 筋トレ](https://iketerumens.com/wp-content/uploads/2023/08/5d38982f84a683f9303e13fcd88c6371-300x157.webp)
	Notion × 筋トレ
	【Notion】筋トレ管理テンプレートの作り方 | 自動でボリュームまで計算
	](https://iketerumens.com/notion-workout-template/)
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