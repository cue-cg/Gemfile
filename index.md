<!DOCTYPE html><html lang="ja"><!-HTMLのお決まり文句 言語は日本語->
  <head><meta charset="utf-8"><!- 文字コードはUTF-8を使用->
  <meta name="viewport" content="width=device-width, initial-scale=1.0"><!- 見ているブラウザがスマホの時サイズを小さくするよ->
  <title>model-viewer demo</title><!- タイトル->
    <script type="module" src="https:<!- unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script><!- model-viewerというJavaScriptプログラムを読み込みます。->
    <script nomodule src="https:<!- unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script><!- model-viewerというJavaScriptプログラムを読み込みます。->
<style>model-viewer{width:100%;height:80vh;background-color:#FFF;}<!- model-viewerのCSS設定->
.mark{background-color: white;border-radius: 4px;border: none;position: absolute;bottom: 16px;right: 16px; }<!- ARボタン※ここでいうとmarkの設定->
footer{size:3em;text-align:center;color:gray;}</style></head><!- footerの設定->
<body><center><!- 真ん中揃え->
<model-viewer poster="img/load.jpg" src="img/cue_logo.glb" ios-src="img/cue_logo.usdz" auto-rotate camera-controls ar alt="サンプル"><!- loadingの画像指定・glbとusdzの指定。自動回転など->
<button slot="ar-button" class="mark">ARに切り替える</button></model-viewer></center></html></body><!- ボタンを文字ボタンに変更->
</html>
