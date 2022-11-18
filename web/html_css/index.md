[トップ](../../) > [Web開発](../) > HTML・CSS

# HTML・CSS

## HTMLとは

Hyper Text Markup Language の略語です。

Webページのパーツに対して役割を決めます。

## CSSとは

Cascading Style Sheets の略語です。

HTMLで作った要素に色をつけたりサイズを決めたり配置を決めたり、つまりWebのデザインほぼ全てを担当しています。

## 学習の進め方

HTMLやCSSは「初心者はここから始めるべき」といった指標はほとんどなく、Webページを実際に作りながら学んでいくことになります。

自分のホームページを作るか、既存のサイトを真似するかしてみてください。

ただ、ある程度理解しないと思った通りのページを作れないので、最初は本や学習サイトなどから始めても良いかもしれません。

[MDNガイド](https://developer.mozilla.org/ja/docs/Learn/HTML)、[Progate](https://prog-8.com/courses/html)などがあります。

本は数多く出版されていますが、筆者は「本当によくわかるHTML&CSSの教科書」を読みました。

「1冊ですべて身につくHTML&CSSとWebデザイン入門講座/実践講座」も良さそうですが、読んだことはないです。

わからないことがあったら「HTML 〇〇 やり方」とかで検索をかけましょう。

エンジニア塾的なサイトはわかりやすいです。
MDNというサイトは仕様作ってる側の人々のサイトなので細かくて正確です。

## 目標

以下の項目が大体できたらまあ完璧でしょう。
全部が完璧でなくても、困った時に戻ってくる感じで大丈夫です。

それぞれについて細かいことはGoogleで検索してください。
(余裕があれば解説書きます...)

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
- CSSの`calc()`を使える

### 上級編

- CSSのpositionで`sticky`や`fixed`を使える
- CSSの擬似要素(`:before`、`:after`)を使える
- CSSの`filter`、`mix-blend-mode`を使って色を操作できる
- CSSの`transform`を使って回転・拡大・移動ができる
- Base64を使ってフォントファイルや小さな画像ファイルをコードに埋め込め、また、その利点が分かる(cf. [ネットワーク]()(未作成))
- png、jpeg、webp、svgの特徴を理解し、適切に使い分けられる

### 発展編

- 簡単なSVGを理解し、手書きできる(`rect`、`line`、`circle`、`path`、`g`、`text`程度)
