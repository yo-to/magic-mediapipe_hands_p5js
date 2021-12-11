# 某アニメの悪役が使う「とっておきの手品」っぽい禁呪が使える（気がするかもしれない）Webアプリ V2

## 概要
![demo](https://github.com/yo-to/magic-mediapipe_hands_p5js/blob/main/demo.gif?raw=true)

### 使い方
使い方は簡単！以下の通りです。  
1） ページを開く  
2） グーにした手をカメラにうつす（手を近づけすぎないほうが良いかも）  
3） 指を一本ずつ開く ⇒ 開いた指先に炎がともる  
4） 手をグーにして、「r キー」を押すと、表示がリセットされます

### ↓体験できるものを用意しました！
https://yo-to.github.io/magic-mediapipe_hands_p5js/

### 利用している技術

Googleさんの [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html)で Webカメラにうつった手を認識させ、指の動きに合わせた画像の描画等の処理を [p5.js](https://p5js.org/) で行っています。  
技術概要などの補足は以下の記事にて。

* [Zennの関連記事： 某アニメの悪役が使う「とっておきの手品」っぽい呪文が使えた気になる（かもしれない）Webアプリを作った話【技術概要】](https://zenn.dev/youtoy/articles/8900adadd996caf643a5)
* [ProtoPediaへの登録： 某アニメの悪役が使う「とっておきの手品」っぽい禁呪が使える（気がするかもしれない）Webアプリ V2](https://protopedia.net/prototype/2734)

### MediaPipe Hands と p5.js を使った別の作品の例

MediaPipe Hands は複数の手を同時に認識でき、また、p5.js は WebGL による 3D の描画もできるものです。
そのため、例えば以下のようなものも作成可能です（※ 以下は、YouTube動画へのリンク）。

* [【両手の認識】 Googleさんの MediaPipe Hands を使った仕組みのテスト - YouTube](https://www.youtube.com/watch?v=vlZRC8iDqjE)
* [【両手の認識】 両手の動きで音を奏でる（p5.js ＋ MediaPipe Hands ＋ Sonic Pi ＋ osc.js） - YouTube](https://www.youtube.com/watch?v=Xz7_Mq_DUNo)
* [【両手の認識 ＋ 3D描画】 p5.js ＋ MediaPipe Hands の組み合わせで WebGL による 3D表現を使ってみた - YouTube](https://www.youtube.com/watch?v=ehJeN8pFHeI)

## その他の関連リンク
* [ProtoPediaの作品登録： 某アニメの悪役が使う「とっておきの手品」っぽい呪文が使えた気になる（かもしれない）Webアプリ | ProtoPedia](https://protopedia.net/prototype/2147)
* [YouTube動画： 某アニメの悪役が使う「とっておきの手品」っぽいことができるアプリ](https://www.youtube.com/watch?v=EkzZNFuWYNk)

