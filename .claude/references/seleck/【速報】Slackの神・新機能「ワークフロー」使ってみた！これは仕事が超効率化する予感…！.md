---
title: 【速報】Slackの神・新機能「ワークフロー」使ってみた！これは仕事が超効率化する予感…！
source: https://seleck.cc/1356
published: 2019-10-17
created: 2025-11-28
description: Slackが一昨日（2019年10月15日）に発表した新機能「ワークフロービルダー」！ みなさま、もう使いましたか？　結論から言うと、この機能は最高です。いますぐ使うべし！ 公式サイトによると、ワークフロービルダーとは、下記のような機能との
updated: 2025-11-28 12:44
---
- コラボレーター
- SELECK編集長
- 舟迫鈴

更新日：2023 年 2 月 24 日 公開日：2019 年 10 月 17 日

![](https://seleck.cc/wp-content/uploads/2019/10/1c652c38699c6cf78bbf2947a213844d.jpeg)

**Slack** が一昨日（2019年10月15日）に発表した新機能「 **ワークフロービルダー** 」！

みなさま、もう使いましたか？　 *結論から言うと、この機能は最高です。いますぐ使うべし！*

[公式サイト](https://slack.com/intl/ja-jp/features/workflow-automation) によると、ワークフロービルダーとは、下記のような機能とのこと。

> *定型的なアクションやコミュニケーションを自動化するワークフローをわずか数分で作成。*

![](https://seleck.cc/wp-content/uploads/2019/10/workflow30.jpg)

ということで早速ためしてみたのですが、 *これ、めちゃくちゃ使える…！* 用途としては、下記のようなものが考えられると思います。

- *入社後の手続きや、オンボーディングのフローを自動化*
- *年末調整や健康診断といった、総務系オペレーションの効率化*
- *会社・チームの目標管理や更新*
- *チームの朝会のような、アジェンダの決まったMTGをSlack上で実施*
- *bot的に使って遊ぶ（おまけ。あとで紹介しています）*

弊社では、早速ワークフローがじゃんじゃん生成されています！

![](https://seleck.cc/wp-content/uploads/2019/10/workflow35.jpg)

実際のワークフローの中身は、例えばこんな感じ…（※あとで説明しますが、これは *Slackが提供しているテンプレート* をベースに作成しています）。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow37.jpg)

では早速、使い方を詳しく見ていきましょう！

## 誰でもできる！「ワークフロービルダー」の使い方を徹底解説！

まずはSlackの左上のメニューから、「 **ワークフロービルダー** 」を選択します。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow01.jpg) すると、このような画面になります。右上の「作成」ボタンから、新しいワークフローを作り始めることができます。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow02.jpg) わかりやすい例として、 *今回は「チームの朝会」のワークフロー* を作っていきます。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow031.jpg) ワークフローを開始する方法（トリガー）を選択します。トリガーは現在、以下の3種類から選ぶことができます。

> **・アクションメニュー  
> **メンバーの誰かがチャンネルの「アクションメニュー（※新機能）」からワークフローを選択（したときに開始される）
> 
> **・チャンネルの新しいメンバー**メンバーの誰かが特定のチャンネルに参加（したときに開始される）
> 
> **・絵文字リアクション**メンバーの誰かが特定の絵文字リアクションをチャンネルに追加（したときに開始される）  

となっています。今回は「 *アクションメニュー* 」を使います。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow041.jpg) アクションの中身を作っていきます。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow051.jpg) *ここで、つまずきやすいポイント！* ワークフローを動かすチャンネルを選択するのですが、右側のドロップダウンボタンを押しても、候補のチャンネルがちゃんと出てきません。（これはおそらくバグかな？）

*でも、使いたいチャンネルの「頭文字」を打ち込めば、見つかります！（ここでつまずいている人をいっぱい見たので重要）*

![](https://seleck.cc/wp-content/uploads/2019/10/workflow061.jpg) こんな感じ。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow08.jpg) 動かすチャンネルとワークフローの短い名前（わかりやすい名前）を設定したら、いよいよ中身を作っていきます。 *「ステップを追加」* をクリックします。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow09.jpg)

今回は「 *フォームを作成する* 」を使います（あとで「 *メッセージを送信* 」も使います）。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow101.jpg) フォームを作っていきます。ここはすごくわかりやすいですね。タイトルを決めて、質問を追加していきます。最後に、通知を設定します。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow12.jpg) 質問を4つ作りました！なお、この画面で *質問の順番を後から入れ替えることもできます。*

![](https://seleck.cc/wp-content/uploads/2019/10/workflow13.jpg) せっかくなので、もう1ステップ追加していきます。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow14.jpg) 今度は「 *メッセージを送信* 」を使ってみます。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow15.jpg) メッセージの送信では、送信先とテキストを自由に設定できます。 *テキストでは、「変数」を使うことができます。例えば、特定のアクションをした人に対してメンションを飛ばしたり、といったことが可能です* 。

（このあたりがSlackらしさがあって良いですねー）

![](https://seleck.cc/wp-content/uploads/2019/10/workflow16.jpg) ![](https://seleck.cc/wp-content/uploads/2019/10/workflow17.jpg) 完成したら、「 *公開* 」ボタンをクリックします！

![](https://seleck.cc/wp-content/uploads/2019/10/workflow18.jpg) できましたー！！！

![](https://seleck.cc/wp-content/uploads/2019/10/workflow19.jpg) では早速、実際に使ってみましょう。 *アクションメニューの場合は、設定したチャンネルの右上にある「雷」のようなマークをクリックすると、誰でもそのワークフローを動かすことができます。*

![](https://seleck.cc/wp-content/uploads/2019/10/workflow20.jpg) ![](https://seleck.cc/wp-content/uploads/2019/10/workflow21.jpg) クリックすると、ワークフローがスタートします。今回はフォームなので、フォームを埋めていきます。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow22.jpg) 投稿されました！規定したワークフローに沿って、カスタマイズしたメッセージも送信されているのがわかります。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow23.jpg) 一番簡単なワークフローの使い方は、こんな感じかなと思います。

## 「絵文字ワークフロー」も使ってみた

せっかくなので、もう1種類くらい作ってみようと思います。今度はアクションメニューではなく、「 *絵文字リアクション* 」を使ってみます。

*これは、メンバーが特定の絵文字リアクションを投稿することをトリガーに動かせるワークフローです* 。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow24.jpg) 動かすチャンネルと、絵文字を選びます！（この「ぴぴぴ」という絵文字は、弊社のオリジナル絵文字です。）

![](https://seleck.cc/wp-content/uploads/2019/10/workflow25.jpg) 先ほどと同様に設定していきます。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow26.jpg) 変数も使えるので、だいぶ遊んでみた（笑）。 *地獄のようなワークフローを作ろうと思います* 。 *ついでに、「ボタン」機能も入れてみます* 。

*Slackのメッセージ上にボタンを表示することで、ユーザーが自分で次のステップに進むことができる機能です* 。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow27.jpg) こうなった（よく見るとめっちゃ怖い）。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow28.jpg)

早速、チームメンバーに使ってもらおうと思います。うちの編集長 [@hanahanayaman](https://twitter.com/hanahanayaman) に送ってみよ。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow34.jpg)

（↑素直だからすぐにリアクションしてるわ。）

![](https://seleck.cc/wp-content/uploads/2019/10/workflow36.jpg) ははははは！（悪魔）

具体的にワークフローが動いているのはここです。もはやワークフローとは言えませんが…むしろbotに近い。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow31.jpg) ワークフローの途中はこういう感じになってます。 *ちゃんとボタンが表示されていますね。*

![](https://seleck.cc/wp-content/uploads/2019/10/workflow33.jpg) こういう、楽しい使い方も工夫次第！自由度が高いのが素晴らしいなと思います。

## Slackの提供するテンプレートを使うと、もっと簡単です！

また、 *イチから自分でワークフローを作らなくても、Slackが提供しているテンプレート（サンプル）を使うともっと簡単です。* 私も最初はこれで作りました！

[こちらから](https://slack.com/intl/ja-jp/slack-tips/workflow-builder-examples) チェック＆ダウンロードが可能です（ただし、いまは英語しか対応していません）。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow38.jpg) いま6種類のサンプルが公開されていました。その中から、「 [オンボーディング](https://seleck.cc/onboarding) 」を選び、JSONファイルをダウンロードします。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow39.jpg) ワークフローのメニューで *「インポート」* をクリックして、先ほどダウンロードしたファイルをインポートします。

![](https://seleck.cc/wp-content/uploads/2019/10/workflow40.jpg) すると、この状態からワークフローを作り始めることができます！（英語なので、私はこれを翻訳してヒント的に使いました）

![](https://seleck.cc/wp-content/uploads/2019/10/workflow41.jpg) ぜひ、気軽に試してみてはいかがでしょうか？

[すべての投稿(1607)を見る >](https://seleck.cc/)

;