---
title: "Vue.js devtoolsで開発効率アップ"
emoji: "📚"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: [Vue]
published: true
---

## はじめに
Vueで開発している方であれば、多くの人がすでにご存知だとは思いますがVue.jsのdevtoolsの紹介記事です。

Vue.js devtoolsはChromeの拡張機能で、開発を効率的に行うことができます。
https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=ja

## 使い方
拡張機能をインストールすると、Vue.jsで開発されているサイトをChromeで開き、DevToolsを開くと「Vue」の項目が追加されています。

### Inspector
![Inspector](/images/b99fd4fedd6b03/inspector.png)
**Components**
現ページのコンポーネントの親子関係がツリー上で表示されます。
コンポーネントを選択すると、propsやdata、computedの値などを見ることができます。
コンポーネントはUI上からも選択することができます。

また、プロパティの値を編集することもできます。
対象のプロパティにカーソルをホバーさせると「鉛筆マーク」が出てくるので、編集することができます。リアクティブに画面の状態が変化したり、computedで算出した値も変化します。

オプションでpropsを編集したり、更新されたコンポーネントをハイライト表示することも可能です。
![InspectorOption](/images/b99fd4fedd6b03/inspector-option.png =250x)


**Routes**
Routesの一覧、親コンポーネントを確認することができます。

**Vuex**
storeの状態などを確認することができます。
こちらもComponents同様、プロパティの編集を行うことができます。


### Timeline
ComponentsやVuexのイベントが正しくトリガーされたかどうかを確認し、イベント発生時刻に関連する状態を調べることができます。
![timeline](/images/b99fd4fedd6b03/timeline.png)



## おわりに
まだ使用していない方は、ぜひ使用してみてください！
個人的にはパフォーマンスの計測への活用がまだできていないので、今後試していきたいです。

最後に宣伝ですが、sweeepではエンジニアを募集しています。ご興味のある方は下記リンクよりご応募お待ちしております！

https://corp.sweeep.ai/recruit