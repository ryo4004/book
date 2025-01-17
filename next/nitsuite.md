# 改訂版について

{% hint style="danger" %}
改訂版は現在進行中のプロジェクトです。完成しているページと、未完成のページがあります。
{% endhint %}

改訂版は、章立てを大きく変更したものです。内容は、「JavaScript再入門」と「これだけはおさせておきたいTypeScriptの機能」と同じです。変更内容は次の3点です。

## 1. よりJavaScriptとTypeScriptを並行して学べる章立てにする

従来、「JavaScript再入門」と「これだけはおさせておきたいTypeScriptの機能」の2つに章が分かれていました。読者の学習の流れとしては、JS→TSの順になっていました。

独自の調査結果で、TS学習者の半数はJSの勉強を並行していることが判明しています。そこで、改訂版では、JSとTSを行ったり来たりして学べるような、実際の学習の流れに合う自然な章立てを目指します。

##  2. 小さいパーツから大きいパーツへ

従来の章立てでも、変数は最初のほうで、オブジェクトは後のほうで紹介していました。プログラミングのパーツのうち、変数は小さいパーツ、オブジェクトは大きいパーツです。

一般的にプログラミング言語の学習は、小から大への順で学んだほうが分かりやすいです。本書でも、よりその学習の流れを強くしたいと考えています。具体的には、「型、値、変数」→「式」→「文・制御構造」→「関数」→「オブジェクト指向」→「モジュール」の順で章立てを見直します。

## 3. ページの粒度を小さくする

本書従来の章立てでは、「関数」や「クラス」といった大きなテーマごとに長いページを作っています。これを改訂版では、より細かいトピックごとにページにします。これには次のような目的があります。

1つ目の目的は、Googleで検索されやすくすることです。Googleから本書へのアクセスを分析すると、「TypeScript 関数」のような機能名より、「TypeScript Promise 戻り値 型」のような具体的な課題解決視点のワードで検索されることのほうが多いことが分かっています。そこで、例えば、「クラス」のページは「クラス」「クラスの継承」「プロパティの修飾子」「抽象クラス」などに分解します。そのほうが、Googleで探しやすくなり、TS学習者の問題解決に寄与できます。

2つ目の目的は、サイト内リンクをしやすくすることです。GitBookの仕様上、サイト内リンクコンポーネントはページ単位になるため、特定の段落にリンクがしずらい課題がありました。ページをトピックごとに分割することで、サイト内リンクが活用できるようになり、読者にとってもメリットになります。

## 新しい章立て

新しい章立ての案は[マインドマップ](https://mm.tt/2009110519?t=Lmnbr9xfKc)にあります。

