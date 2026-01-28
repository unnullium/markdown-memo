# Project Guidelines

GitHub Pagesで公開する個人用ツールサイト

## ファイル構成

- `index.html` - 目次ページ（ポータル）
- `*.html` - 各種ツール

## ツール作成ルール

新しいHTMLツールを作成した場合、必ず `index.html` の目次リストにも追加すること。

### 追加する形式

```html
<li>
  <a href="ファイル名.html">
    <div class="tool-name">絵文字 ツール名</div>
    <div class="tool-desc">ツールの説明</div>
  </a>
</li>
```

### 手順

1. 新しいHTMLファイルを作成
2. `index.html` の `<ul class="tools-list">` 内にリンクを追加
3. 両方のファイルをコミット
