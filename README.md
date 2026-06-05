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

<details>
<summary>解答例</summary>

```JS
const btn = document.querySelector("#inquiry-button");
btn.addEventListener("click", () => {
    btn.style.backgroundColor = "#05b";
    setTimeout(() => {
        btn.style.backgroundColor = "#07f";
    }, 100);
});
```

</details>
<br>

[練習問題2](./01_Button/01_2/.md)<br>

<details>
<summary>解答例</summary>

```JS
const btn = document.querySelector("#lucky-color-button");
btn.addEventListener("click", () => {
    const randCode = Math.floor(Math.random() * 16777215).toString(16);
    const color = `#${randCode}`;
    btn.style.backgroundColor = color;
});
```

</details>
<br>

[練習問題3](./01_Button/01_3/.md)<br>

<details>
<summary>解答例</summary>

```JS
const btn = document.querySelector("#more-collection-button");
btn.addEventListener("mousemove", (e) => {
    const rect = btn.getBoundingClientRect();
    const x = ((e.clientX - rect.left) / rect.width) * 100;
    btn.style.backgroundPosition = `${x}% 0`;
});
btn.addEventListener("mouseleave", () => {
    btn.style.backgroundPosition = "0% 0";
});
```

</details>
<br>

## 参考
Mana [『CSSとJavaScriptで作る動くUIアイデアレシピ』](https://book.impress.co.jp/books/1123101113)（2025）<br>
MDN [JavaScript リファレンス](https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference)