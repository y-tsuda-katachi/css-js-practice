# CSS JavaScriptの練習問題

**_※随時追加予定_**

## 使い方について

CSSとJavaScriptを組み合わせたUIデザイン・操作について、各部品ごとに、以下のようなルールで問題を出題します。<br>
JavaScript用のコードを追加し、実行結果の通りになるように記述してください。

**_(例)　以下のHTML/CSSをみて、実行結果の通りになるようJavaScriptコードを追加してください。_**

```HTML
<!doctype html>
<html>
  <head>
    <title>Button_1</title>
    <link rel="stylesheet" href="style.css" />
    <script src="script.js" defer></script>
  </head>

  <body>
    <button id="inquiry-button">お問い合わせ</button>
  </body>
</html>

```

```CSS
#inquiry-button {
    padding: 1rem 1.5rem;
    font-size: 1rem;
    border: none;
    border-radius: 8px;
    background-color: #07f;
    color: #fff;
    cursor: pointer;
    transition: background-color 0.1s ease;
}
```

[実行結果]
<br>
![](./01_Button/01_1/01_1.gif)

> [!WARNING]
> カーソル周辺の黄色いエフェクトは練習問題とは関係ありません。<br>
> クリックを視認しやすくするために表示しています。

## 練習問題について

問題を解く際は次の方法で行うことを推奨します。
- リポジトリごとダウンロードしてJSファイルを追加する
    - ダウンロードは[こちら](https://github.com/y-tsuda-katachi/css-js-practice/archive/refs/heads/main.zip)
- 問題に書かれているHTML/CSSを直接コピー&ペーストして、JSファイルを追加する

### 解答例について

実行結果のとおり動作されれば、UIの色や形・コードの書き方などは問いませんので、各々で自由にアレンジして取り組んで下さい。

### 練習問題一覧

これらの問題はすべて取り組まなくても大丈夫です。

各問題には、頻出度合いに応じて**重要度**を三段階で付けています（⭐１～⭐⭐⭐３）。

また同時に**難易度**についても三段階で付けています（🔥１～🔥🔥🔥３）ので、各人のレベルに応じて柔軟に選んで解答してください。

|カテゴリ|問題|重要度⭐|難易度🔥|
|---|---|---|---|
|ボタン|[練習問題1](./01_Button/01_1/.md)|⭐⭐⭐３|🔥１|
||[練習問題2](./01_Button/01_2/.md)|⭐１|🔥🔥２|
||[練習問題3](./01_Button/01_3/.md)|⭐１|🔥🔥🔥３|
||[練習問題4](./01_Button/01_4/.md)|⭐⭐⭐３|🔥１|
|フォーム|[練習問題1](./02_Form/02_1/.md)|⭐⭐⭐３|🔥１|
||[練習問題2](./02_Form/02_2/.md)| ⭐⭐⭐３|🔥１|
|ユーティリティ|[練習問題1](./03_Utility/03_1/.md)|⭐⭐２|🔥🔥２|
|アニメーション|[練習問題1](./04_Animation/04_1/.md)|⭐⭐⭐３|🔥１|
||[練習問題2](./04_Animation/04_2/.md)|⭐１|🔥🔥２|
||[練習問題3](./04_Animation/04_3/.md)|⭐１|🔥🔥２|
||[練習問題4](./04_Animation/04_4/.md)|⭐１|🔥🔥🔥３|
||[練習問題5](./04_Animation/04_5/.md)|⭐⭐２|🔥🔥２|

## 参考

Mana [『1冊ですべて身につくJavaScript入門講座』](https://www.sbcr.jp/product/4815615758/)（2023）<br>
Mana [『CSSとJavaScriptで作る動くUIアイデアレシピ』](https://book.impress.co.jp/books/1123101113)（2025）<br>
MDN [JavaScript リファレンス](https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference)
