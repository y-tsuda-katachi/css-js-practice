# Javascript UIの練習問題

**_※随時追加予定_**

## 使い方について

CSSとJavascriptを組み合わせたUIデザイン・操作について、各部品ごとに、以下のようなルールで問題を出題します。<br>
Javascript用のコードを追加し、実行結果の通りになるように記述してください。

**_(例)　以下のHTML/CSSをみて、実行結果の通りになるようJavascriptコードを追加してください。_**

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

## 練習問題はコチラ

### 解答例について

実行結果のとおり動作されれば、UIの色や形・コードの書き方などは問いませんので、各々で自由にアレンジして取り組んで下さい。<br>
下記は解答例になります。<br>

### ボタン

[練習問題1](./01_Button/01_1/.md)

[練習問題2](./01_Button/01_2/.md)

[練習問題3](./01_Button/01_3/.md)

[練習問題4](./01_Button/01_4/.md)

### フォーム

[練習問題1](./02_Form/02_1/.md)

## 参考

Mana [『1冊ですべて身につくJavaScript入門講座』](https://www.sbcr.jp/product/4815615758/)（2023）<br>
Mana [『CSSとJavaScriptで作る動くUIアイデアレシピ』](https://book.impress.co.jp/books/1123101113)（2025）<br>
MDN [JavaScript リファレンス](https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference)
