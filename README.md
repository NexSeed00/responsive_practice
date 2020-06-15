## レスポンシブ ＆ flexbox 練習問題

* [レスポンシブの解説](https://github.com/NexSeed00/HTML_CSS/blob/master/doc/11_responsive.md)
* [flexboxの解説](https://github.com/NexSeed00/HTML_CSS/blob/master/doc/04_flexbox.md)

### 目標

* 四角の要素が３つ縦並びで配置されるCSSを書く
* 画面の横幅が780pxより大きい時、要素が横並びになるように書く（モバイルファースト）


### 開始手順

1. 新しいフォルダ「resonsive_flexbox」を作成し、`index.html`と`style.css`ファイルを作成してください。
2. 以下のコードをそれぞれのファイルに貼り付けます。
3. 上記の目標を達成できるように指定した箇所に、コードを加えてください。


index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <!-- <link rel="stylesheet" href="answer.css"> -->
</head>
<body>
    <div class="box"></div>
    <div class="box"></div>
    <div class="box"></div>
</body>
</html>
```

style.css
```css
* {
    margin: 0;
    padding: 0;
}
body {
    height: 100vh;
    width: 100%;
    border: 1px solid black;
    /* [以下を編集] 1. flexboxを使う */

}
.box {
    background-color: #1e50a2;
    border: 4px solid #103269;
    width: 30%;
    height: 30%;
}

/* [以下を編集] 2. メディアクエリを書く (ブレイクポイント：780px) */


```

* モバイルファーストなので、Chromeの画面の横幅を780pxより狭めた状態で、コードの実行結果を確認してください。
* 狭めた状態での見た目ができたら、メディアクエリで、画面幅が大きい場合のCSSを書きます。
