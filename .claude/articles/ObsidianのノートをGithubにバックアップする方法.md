---
title: ObsidianのノートをGithubにバックアップする方法
source: https://iketerumens.com/obsidian-git/
published: 2023-04-15
created: 2025-08-20
description: Obsidianはローカル型のノートアプリなので、会社のPCなどデバイスが変わればアクセス不可能になってしまいます。やはりそこはクラウド型のノートアプリに比べると利便性に劣る部分ではあるのですが、その弱点をこのプラグインObsidian GitによってObsidianをローカルとクラウドのハイブリッド型に進化させることができるのです。
updated: 2025-08-20 12:14
---
1. [HOME](https://iketerumens.com/)
2. ObsidianのノートをGithubにバックアップする方法

2023年4月15日

![Obsidian Git - ローカルとクラウドのハイブリッド型ノートアプリ](https://iketerumens.com/wp-content/uploads/2023/03/ebc69b0d24e1713485d530e2f7790316.webp)

Obsidian Git - ローカルとクラウドのハイブリッド型ノートアプリ

先日、誤ってObsidianの日記をフォルダごと削除してしまいました。  
  
Macのゴミ箱から復元できたものの、あの時はマジで冷や汗が止まらず、自分の稚拙な情報管理を呪いました。  
  
こんなこともあり、「めんどくさいけど、Githubでバックアップ取っとくかー」ということで\[[Obsidian Git](https://github.com/denolehov/obsidian-git)\]というプラグインを使ってObsidianのノートを10分おきにGithubにバックアップするように連携させました。  
  
久しぶりにGitをいじるということもあって、エラーにぶち当たったりとかなり時間を消費してしまったので「Obsidian Gitこの通りやればあなたも大丈夫ガイド」を作成したのでこれからやってみようと思う方は参考にしてくださると嬉しいです。  
  
推定読了時間は5分！

## 対象読者

- Githubのアカウントを持っている
- 最近Gitをいじっておらず、忘れている

## Obsidian Gitを使うとできること

できることと言っても、タイトル通り以下二つのことだけなのですが、

- ObsidianのノートをGithubにバックアップできる
- Githubを通してクラウド上でもObsidianのノートを確認することができる

Obsidianはローカル型のノートアプリなので、会社のPCなどデバイスが変わればアクセス不可能になってしまいます。  
  
やはりそこはクラウド型のノートアプリに比べると利便性に劣る部分ではあるのですが、その弱点をこのプラグインObsidian GitでによってObsidianをローカルとクラウドのハイブリッド型に進化させることができるのです。

## ObsidianとGithubの連携手順

1.Githubでリポジトリを作成する  
2.ターミナルを開き、 `git clone` でローカルにダウンロード  
3.ダウンロードしたディレクトリをVSCodeで開いて、 `git add` → `git commit -m "first commit"` → `git push` をしてリモートリポジトリへプッシュ  
4.リモートディレクトリにプッシュできたら、そのディレクトリをObsidianで開く  
5.Obsidian上で何か適当にノートを作成する  
6.プラグイン: \[[Obsidian Git](https://github.com/denolehov/obsidian-git)\]をインストール  
7.ステータスバーに「Git is ready」が出ていればそのまま進める  
7-a.「Git is not ready!」が出ている場合は、ターミナルを開いて、ホームディレクトリで、 `xcode-select --install`  
8.有効化して、1分おきに変更

![](https://iketerumens.com/wp-content/uploads/2023/03/4b69229bfe7edcbb1476844f8ff407c8-1024x536.webp)

9.変更がGithubに反映されていれば完了  

## まとめ: ローカルとクラウドのハイブリッド型ノートアプリへ

ローカルにファイルを作りつつ、クラウドの便利さも享受する。これでObsidianが名実ともに最強のノートアプリになったんじゃないでしょうか。  
  
Logseqも最近使っていますが、「こっちにもObsidian Gitのようなプラグインがあればなー」と感じています。  
  
ObsidianとLogseqの併用についての記事はまた別途書くつもりです。

## 参考文献

- [ObsidianをGitでバージョン管理する](https://kattsun.dev/posts/2021-05-25-obsidian-with-git/)
- [「Git is not ready!」のエラーが出た場合](https://github.com/denolehov/obsidian-git/issues/314)

## noteでも情報発信中

実際に試したAIツールや知的生産手法、暗号資産の最新動向をnoteで公開しています。SEOをガン無視して、ガチの個人的に厳選した内容をシェアしているのでぜひチェックいただけると！今後の読書まとめや映画の感想などもこちらのnoteで公開していく予定です！

また、最新情報はXで発信しているので、Xとnoteもフォローしてもらえると嬉しいです！発信されている方はどちらもフォロバします！仲良くしてください！

![](https://assets.st-note.com/poc-image/manual/production/default_top_ogp_202212.png)

[Tweets by lifeoptimizer7](https://twitter.com/lifeoptimizer7?ref_src=twsrc%5Etfw)

![Obsidian Git - ローカルとクラウドのハイブリッド型ノートアプリ](https://iketerumens.com/wp-content/uploads/2023/03/ebc69b0d24e1713485d530e2f7790316-300x157.webp)

Obsidian Git - ローカルとクラウドのハイブリッド型ノートアプリ

この記事が気に入ったら  
フォローしてね！

- [【2024年最新版】Obsidian使い方大全 - 最強ノートアプリで第二の脳を構築する](https://iketerumens.com/obsidian/)
- [【Webクリップの最適解】RaindropとNotionでインプット情報の完全整理](https://iketerumens.com/web-clip-raindrop-and-notion/)

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