# HTML・CSS

## HTMLとは

Hyper Text Markup Language の略語です。

Webページのパーツに対して役割を決めます。

名前の通りマークアップ言語であり、プログラミング言語ではありません。
なので計算とかはほとんどできません。

データの構造化をするやつなので、意外に[データ構造]()(未作成)あたりと近かったりします。

## CSSとは

Cascading Style Sheets の略語です。

HTMLで作った要素に色をつけたりサイズを決めたり配置を決めたり、つまりWebのデザインほぼ全てを担当しています。

## はじめに

とりあえず[Progate](https://prog-8.com/courses/html)やるのが早いです。

わからないことがあったら「HTML 〇〇 やり方」とかで検索をかけましょう。

エンジニア塾的なサイトはわかりやすいです。
MDNというサイトは仕様作ってる側の人々のサイトなので細かくて正確です。

## 目標

以下の項目が大体できたらまあ完璧でしょう。
(全部が完璧でなくても、困った時に戻ってくる感じで大丈夫です)

### 初級編

- HTMLの`head`、`meta`、`body`、`div`、`span`、`table`辺りが分かる
- HTMLの要素に対して親・子と言われて分かる
- CSSのセレクタ(`tag {}`、`.class {}`、`#id {}`、`.a .b {}`、`.a > .b {}`、`.a + .b {}`、`.a, .b {}`とか)の違いが分かり、HTMLと照らし合わせて適用される範囲を把握できる
- CSSの`background-color`、`border-radius`など表示系のスタイルが分かる
- CSSの`padding`、`border`、`margin`の違いが分かる
- CSSのインライン要素、ブロック要素を区別できる
- 絶対リンク・相対リンクの違いが分かる(cf. [Linux]()(未作成))
- Youtube動画やTwitterの埋め込みができる

### 中級編

- CSSの絶対配置・相対配置が分かる(基準点含めて)
- CSSで中央配置ができる
- CSSでの文字のデザインの変え方(`font-size`、`font-weight`、`color`、`line-height`)が分かる
- CSSでのフォントの変え方(`font-family`、`@font-face`)が分かる
- CSSで`flexbox`や`grid`が使える
- CSSの`display`の使い方(`inline`、`block`、`inline-block`)が分かる
- CSSの`px`、`%`、`vw`、`vh`、`vmin`、`vmax`、`em`、`rem`を説明できる
- CSSの`overflow`を使える
- CSSの`rgba(255,255,255,1)`、`#ffffff`を脳内で変換できる

### 上級編

- CSSのpositionで`sticky`や`fixed`を使える
- Base64を使ってフォントファイルや小さな画像ファイルをコードに埋め込め、また、その利点が分かる(cf. [ネットワーク]()(未作成))
- png、jpeg、webp、svgの特徴を理解し、適切に使い分けられる

### 発展編

- 簡単なSVGを理解し、手書きできる(`rect`、`line`、`circle`、`path`、`g`、`text`程度)
