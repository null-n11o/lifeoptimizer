---
title: Claudeの新機能「Projects」完全解説 - 最強AIはさらに一段階上のレベルへ
source: https://iketerumens.com/claude-projects/
published: 2024-08-17
created: 2025-08-20
description: 現状世界最強性能のAIモデルとして知られるClaude 3.5 Sonnetを開発したAnthropic社からClaudeの新機能として「Projects」をリリースされました。ClaudeのProjects機能はプロジェクト単位で自分が持つ情報やスレッドを管理することが可能で、プロジェクト一つにつき一人のアシスタントを雇っているかのごとく様々なタスクをこなしてくれます。
updated: 2025-08-20 12:02
---
## Claudeの新機能「Projects」完全解説 – 最強AIはさらに一段階上のレベルへ

2024年8月17日

![ClaudeのProjects機能 - 現在世界最強AIの新機能](https://iketerumens.com/wp-content/uploads/2024/08/Claude-Projects.webp)

ClaudeのProjects機能 - 現在世界最強AIの新機能

現状世界最強性能のAIモデルとして知られるClaude 3.5 Sonnetを開発したAnthropic社からClaudeの新機能として「Projects」をリリースされました。  
  
ClaudeのProjects機能はプロジェクト単位で自分が持つ情報やスレッドを管理することが可能で、プロジェクト一つにつき一人のアシスタントを雇っているかのごとく様々なタスクをこなしてくれます。  
  
今回はこのClaudeのProjects機能の概要と、具体的な使用方法を詳しく紹介していきます。個人的に今一番使っているAIツールであり、現状最強のAIをさらに進化させたProjects機能について徹底的に解説していくのでぜひ参考にしてください。

## Claudeの新機能「Projects」の概要

ClaudeのProjects機能は、Anthropic社が2024年6月26日にリリースしたClaudeの新機能です。  
この新機能により、Claudeとの対話や関連する情報を一箇所にまとめることができるようになりました。

主な特徴は以下。

1. Custom Instructions
2. Knowledge
3. Artifacts機能との連携

特に注目すべきは、Knowledgeによるコンテクストをプロジェクトごとに与えることができる点でしょう。  
これによってRAGを簡単に行えるようになり、プロジェクトに関するテキストやファイル、PDF、画像など様々な形式の情報を与えることで長いプロンプトを作らなくてもClaudeにそのプロジェクトの前提条件や進んでいる内容を理解させることができます。

また、ChatGPTと同じく、Custom Instructionsを使えば、プロジェクト固有の要件や制約をAIに伝えることができるので、何度も同じようにAIに与える役割や自分の依頼を伝えなくても、高精度な出力をしてくれるようになっています。  
  
Projects機能を使うにはClaude Proと契約する必要があり、毎月20ドルの支払いが必要です。  
※現在(2024年8月13日)のレートで約2,946円

## Claude Projects機能の使い方と具体的な流れ

実際に「ドイツで起業する」プロジェクトを例にProjects機能の使い方と流れを見ていきます。

### Projects作成とKnowledgeのアップロード

まず、新しいプロジェクトを作成し、関連するナレッジファイルをアップロードします。過去の議事録、見積書、要件定義書や図解資料(画像)などできるだけ多くの資料をアップロードして、Claudeにそのプロジェクトをできるだけ詳しく理解してもらいます。

![Projectsの作成 - Claude](https://iketerumens.com/wp-content/uploads/2024/08/209307fdb162ae927f649000bc4b394e-1024x661.webp)

Projectsの作成 - Claude

プロンプトの基本的な要素として「コンテクストを与える」というものがありますが、このProjectsのKnowledgeアップロード機能によってプロンプトで与える必要がなくなり、今持っている資料をそのままアップロードすれば良いという革命的なことができるようになったわけです。

![Knowledgeのアップロード - Claude](https://iketerumens.com/wp-content/uploads/2024/08/b0a516dad30e28f43182185740e60261-1024x730.webp)

Knowledgeのアップロード - Claude

### Custom Instructionsの設定

ChatGPTと同じくClaudeのProjectsにもCustom Instructionsを設定することが可能です。  
以下のことが主な特徴と言えるでしょう。

- プロンプト作成時間の短縮
- トークン数の節約
- 出力の精度向上

Custom Instructionsは簡単にいうとユーザーのニーズに合わせて事前情報や出力方法を追加・調整できる機能になります。  
  
この機能は一度設定を行うと、その後の質問すべてに適用されてしまうので細かく質問内容を変える場合には不向きですが、ある特定条件や制約の下で連続使用する場合、非常に有用な機能と言えます。

![Custom Instructionsの設定 - Claude](https://iketerumens.com/wp-content/uploads/2024/08/9485da1f7ab1a228029284147c0e79f2-974x1024.webp)

Custom Instructionsの設定 - Claude

### Artifact機能によるコンテンツの生成と改善

Knowledgeを与え、Custom Instructionsを設定したら実際にチャットを始めていきます。  
  
Artifactの機能を一言で言えばコンテンツの生成と即時改善です。例えば、プロジェクト計画書の作成を依頼すると、AIが関連情報を基に初期ドラフトを生成してくれます。

その後、対話を通じて内容を微調整していくことができます。「この部分をもう少し詳しく」「ここにリスク分析を追加して」といった指示を出すことで、コンテンツを改善していけるのです。

![Artifact機能 - Claude](https://iketerumens.com/wp-content/uploads/2024/08/2024-08-12-Screenshot-from-Squoosh-1024x188.webp)

Artifact機能 - Claude

## Claude Projects機能、ChatGPT GPTsとNotebookLMの比較

ChatGPTのGPTsとGoogleから提供されているNotebookLMがClaudeのProjectsと同じような機能を備えているので比較してみました。  
  
比較する際にはProjects機能だけでなく、モデル自体の性能や他の付随する機能も使い心地に関わってくるので、Projects機能の比較をメインにしつつもAIチャットボット全体の比較になっています。

| 機能 | Claude Projects | ChatGPT GPTs | NotebookLM |
| --- | --- | --- | --- |
| カスタマイズ性 | プロジェクト固有のCustom Instructionsを設定可能 | プロジェクト固有のCustom Instructionsを設定可能 | 非常に限定的 |
| Knowledge | ユーザーがあらゆる情報(画像、PDF、テキスト)をアップロード可能。   URLは不可。 | ユーザーがあらゆる情報(画像、PDF、テキスト)をアップロード可能。   URLは不可。 | ユーザーが全ての形式の情報をアップロード可能。   URLも可。 |
| コンテキストウィンドウ | 200Kトークン | モデルによって異なる | 不明（Gemini 1.5 Proがベース） |
| Web検索機能 | なし | あり | なし |
| マルチモーダル対応 | 画像解析・（画像生成: Artifactによるコード生成） | 画像生成・解析、音声対話 | 文書解析のみ |
| コンテンツの生成・改善 | Artifact機能により、高速に生成・改善が可能 | 従来のAIチャットボットと同じくテキストベースの出力 | 生成不可。アップロードされたKnowledgeの回答のみ可能 |
| 外部アプリ連携 | 限定的 | 豊富（プラグイン） | 限定的 |
| 使用モデル | Claude 3.5 sonnet | GPT-4o | Gemini 1.5 Pro |

カスタマイズ性とKnowledgeについては、ClaudeのProjects機能とChatGPTのGPTsはほぼ同じで、どちらもCustom Instructionsを設定できますし、URL以外の様々な形式の情報をアップロード可能で、その情報に基づいたコンテンツを生成することができます。  
  
対してNotebookLMはアップロードされた情報の回答を行うことがメインのサービスなので、URLを含む全ての情報のアップロードが可能ですが、コンテンツの生成は非常に限定的です。  
  
次にコンテンツ生成関連の項目についてです。  
  
マルチモーダル対応に関してはGPTsの方が多く対応していますが、Claudeでもコードを生成し、Artifactを用いて図解や画像を表示することが可能なので大きな違いは音声対話といったところでしょう。これはChatGPT GPTsの大きな強みと言えると思います。  
  
逆にClaudeはProjects機能に加えて、Artifact機能があることによってコンテンツの生成・改善のスピードという部分に関してはClaudeに軍配が上がりますが、ChatGPTはGPTsを組み合わせるということも可能なので、またClaudeとは違った出力が可能になるかとも思います。

まとめると、ProjectsとGPTsの違いは以下3つになるかと思います。

- モデルの違い
	- Claude 3.5 sonnet・GPT-4o
- マルチモーダル対応
	- ChatGPTは音声対話も可能
- コンテンツの生成・改善
	- ClaudeはArtifact機能により高速な生成・改善が可能、ChatGPTはGPTsを組み合わせることができる

現状最高レベルのモデルである、Claude 3.5 sonnetに加えて、Artifactによるコンテンツの生成・改善スピードがとんでもなく早くなることを考えると個人的にメインに使うべき（課金すべき）AIチャットボットはClaude Proかなと思います。

![Claude、ChatGPT、NoteboolLMの比較の結論](https://iketerumens.com/wp-content/uploads/2024/08/68ab7b7bb3ea1a4846ab158ebaf6e1e2-1024x281.webp)

Claude、ChatGPT、NoteboolLMの比較の結論

## 個人的なClaude Projectsの活用事例

実際に現在私が活用しているProjects機能の事例を紹介します。主に以下2つです。

1. 情報整理とアイデア生成
2. コンテンツの生成（ブログ）

### 情報整理とアイデア生成

こちらに関しては本業（ソフトウェア受託開発）の案件で多く行っている事例です。  
  
まずはとにかく全ての書類をProjectsのKnowledgeにぶち込みます。  
自分はプロジェクト・マネージャーなので要件定義書や定例MTGの議事録、各種開発した機能のテスト要件書や見積書など全てです。  
  
まず要件定義書をアップロードすることでどのようなプロダクトなのかという一番の前提条件をClaudeに理解させ、その後の細かい機能の要件定義・実装方法などの出力精度を上げます。  
  
そして、毎週の定例MTGの議事録をアップロードすることで「ここの機能ってこういう仕様でしたよね？」という起こりがちな認識齟齬も議事録ベースで回答してくれます。  
  
Claudeは元々コード生成に強いモデルなので、こういった情報をアップロードするだけでコードを書くのが得意でない自分でも大体の機能を作れてしまうわけです。

![Claudeによるプロジェクト・マネジメント](https://iketerumens.com/wp-content/uploads/2024/08/Squoosh-Aug-13-Screenshot-1024x491.webp)

Claudeによるプロジェクト・マネジメント

### コンテンツの生成（ブログ）

もはやClaudeのProjects機能なしにブログ記事の作成するのは無理ですね。  
  
Knowledgeにアップロードするのはブログのテーマとカテゴリーなど概要をまとめた資料に、以前作成した記事。これによって自分の文体のような文章を生成してくれるようになります。  
  
また、図解作成も以前はCanvaで自分で考えて作っていましたが、今は文章を元にArtifact機能でClaudeが図解してくれるのでここは10倍ぐらい効率化できた部分と言って良いでしょう。  
  
ブログ記事の作成についてはPerplexity AIも併用しているのでまた今度コンテンツ生成のためのAI活用をテーマにした記事を作成しようと思います。

## まとめ: ClaudeのProjects機能を使い倒して生産性をぶち上げましょう

Claudeの新機能「Projects」は、AIとの対話を新たな次元に引き上げる画期的な機能と言えるでしょう。カスタマイズ性の高さ、豊富なKnowledge機能、そしてArtifact機能との連携により、ユーザーは複雑なプロジェクトや長期的なタスクをより効率的に管理し、遂行することが可能になりました。

個人的に生産性を上げてくれた特筆すべき点は以下3つです。

1. プロジェクト固有のコンテクスト理解
	- Custom InstructionsとKnowledgeにより、AIがプロジェクトの背景や要件を深く理解し、より適切な応答を提供できるように。
2. 高速なコンテンツ生成と改善
	- Artifact機能により、出力と同時にコンテンツ生成が行われるように。質問から具体的なアウトプットまでの時間がほぼ0になり、コンテンツの生成・改善が高速で行えるように。
3. 図解
	- Projects機能によるコンテクスト理解とArtifact機能によって出力される図解の精度

ChatGPTのGPTsやGoogleのNotebookLMと比較しても、Claudeの「Projects」機能は総合的な性能と使いやすさで一歩リードしていると言えます。  
特に、Claude 3.5 sonnetという高性能モデルをベースにしていることと、Artifact機能による高速なコンテンツ生成・改善能力は大きな強みで、現状最強のAIサービスであることに間違い無いです。  
  
AIの進化は早く、また来月にでもChatGPTやGemini、まだ見ぬAIサービスに革新的なモデルや機能が追加される可能性もあるので年間契約をすることはおすすめできませんが、ひとまずClaude Pro（月額20ドル）を1ヶ月契約して現状最強のAIサービスを触ってみることをおすすめします。

## より詳しいClaudeや生成AIの情報は以下をチェック

以下noteにてより具体的な生成AIやデジタルツールの使い方を紹介していきますのでフォローお願いします！

![](https://assets.st-note.com/poc-image/manual/production/default_top_ogp_202212.png)

## noteでも情報発信中

実際に試したAIツールや知的生産手法、暗号資産の最新動向をnoteで公開しています。SEOをガン無視して、ガチの個人的に厳選した内容をシェアしているのでぜひチェックいただけると！

最新情報はXで発信しているので、Xとnoteもフォローしてもらえると嬉しいです！発信されている方はどちらもフォロバします！仲良くしてください！

![](https://assets.st-note.com/poc-image/manual/production/default_top_ogp_202212.png)

[Tweets by lifeoptimizer7](https://twitter.com/lifeoptimizer7?ref_src=twsrc%5Etfw)

![ClaudeのProjects機能 - 現在世界最強AIの新機能](https://iketerumens.com/wp-content/uploads/2024/08/Claude-Projects-300x157.webp)

ClaudeのProjects機能 - 現在世界最強AIの新機能

この記事が気に入ったら  
フォローしてね！

- [【完全解説】「イシューからはじめよ」要約 | バリューのある仕事と生産性の本質](https://iketerumens.com/issue-driven/)
- [【Perplexity AI】の使い方を徹底解説 | 最強の検索AIを使いこなし爆速でコンテンツ作成](https://iketerumens.com/how-to-use-perplexity/)

## この記事を書いた人

## 関連記事

- [
	![DeepSeek - オープンソースの革命AIモデル -](https://iketerumens.com/wp-content/uploads/2025/02/DeepSeek-1280x670-1-300x157.webp)
	DeepSeek - オープンソースの革命AIモデル -
	【DeepSeek】中国発のAI革命 | 新興企業の全貌と最新モデルR1とV3を徹底解説
	](https://iketerumens.com/deepseek/)
- [
	![Google AI Studio - 完全無料で全Geminiモデルを利用可能](https://iketerumens.com/wp-content/uploads/2024/12/Google-AI-Studio-1280x670-1-300x157.webp)
	Google AI Studio - 完全無料で全Geminiモデルを利用可能
	【Google AI Studioとは？】無料でGeminiの最強モデルを使い倒せるバグレベルのプラットフォーム
	](https://iketerumens.com/google-ai-studio/)
- [
	![AIエージェント入門](https://iketerumens.com/wp-content/uploads/2025/01/2776eadeba59b0563dc34e902c478548-300x157.webp)
	AIエージェント入門
	15分でざっくり概要をつかめるAIエージェント入門
	](https://iketerumens.com/ai-agent/)
- [
	![Replit - プログラミング不要で完全自動開発](https://iketerumens.com/wp-content/uploads/2024/12/Replit-1280x670-1-300x157.webp)
	Replit - プログラミング不要で完全自動開発
	【Replitの使い方】完全自動のフルスタックAI開発ツールを徹底解説
	](https://iketerumens.com/replit/)
- [
	![Gamma - AI-Powerd Presentation](https://iketerumens.com/wp-content/uploads/2024/12/Gamma-300x157.webp)
	Gamma - AI-Powerd Presentation
	【Gamma】使い方完全ガイド | 最強のプレゼンテーション資料生成AIを徹底解説
	](https://iketerumens.com/gamma/)
- [
	![Genspark - 大量の情報を完全自動で収集](https://iketerumens.com/wp-content/uploads/2024/12/Genspark-1280x670-1-300x157.webp)
	Genspark - 大量の情報を完全自動で収集
	【Gensparkの使い方】SparkpageとAuto Pilot Agent機能など独自の機能を徹底解説
	](https://iketerumens.com/genspark/)

保存