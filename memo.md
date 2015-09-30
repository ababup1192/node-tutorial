# Node.js

## 概要
JavaScriptは二種類に分けられる。
- フロントエンドJavaScript
- サーバサイドJavaScript

フロントエンドJavaScriptはHTMLを操作し、
jQueryなどを使ってリッチな「ブラウザ」での
プログラミングが行える。

Node.jsはサーバサイドのためのJavaScriptである。

## サーバサイドJavaScript
JavaScriptはブラウザ上で動くケースが多い。しかしこれは
単なるコンテキストに過ぎない。JavaScriptは「完全なる言語」
であり、様々なコンテキストで使える。

Node.jsもまた、ひとつのコンテキストに過ぎない。Node.jsによって
JavaScriptはバックエンド、ブラウザの外で動作することができる。

バックエンドでJavaScriptが動作するには、インタープリターで変換され、 そして実行されなければならない。これをNode.jsが行う。
内部ではGoogleのV8 VMが利用されている。
