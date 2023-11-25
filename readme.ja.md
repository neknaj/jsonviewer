# Neknaj JSON_Viewer.js
JSONデータをHTMLとCSSでいい感じに表示します  

## 使い方
1. `jsonviewer.js`と`jsonviewer.css`を読み込みます
```html
<script src="./jsonviewer.js"></script>
<link href="./jsonviewer.css" rel="stylesheet">
```
2. `showJSON`関数を呼び出します
```ts
showJSON( obj:object, elm:HTMLDivElement, defaultopen:boolean=false )
```

## サンプル
[./sample.html](./sample.html)

## ライセンス
MIT LICENSE