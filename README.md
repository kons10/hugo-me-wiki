# Awesome-site (Hugo版)

既存の `awesome-site` をHugoに変換したもの。
iframeを廃止し、partialで共通化。コンテンツはMarkdownで管理できる。

## ディレクトリ構成

```
awesome-site/
├── hugo.toml                        # 設定（ナビ・SNSリンクはここで管理）
├── content/
│   ├── _index.md                    # トップページ
│   ├── profile.md
│   ├── links.md
│   └── downloads.md
├── static/
│   └── svg/                         # ← SVGをここにコピーする
└── themes/awesome/
    ├── layouts/
    │   ├── _default/
    │   │   ├── baseof.html          # 全ページ共通レイアウト
    │   │   └── single.html
    │   ├── partials/
    │   │   ├── header.html
    │   │   └── footer.html
    │   ├── index.html
    │   └── 404.html
    └── static/css/base.css
```

## セットアップ

### 1. SVGをコピー

```bash
cp -r /path/to/original/assets/svg/* static/svg/
```

### 2. Hugo未インストールの場合

```bash
# Ubuntu/Debian
sudo apt install hugo

# macOS
brew install hugo

# Windows
winget install Hugo.Hugo.Extended
```

### 3. 開発鯖起動

```bash
hugo server -D
# → http://localhost:1313 で確認
```

### 4. ビルド

```bash
hugo
# → public/ に出力される
```

## カスタマイズ

- **ナビ/SNSリンク変更** → `hugo.toml` を編集
- **新ページ追加** → `hugo new content hogehoge.md` するだけ
- **デザイン変更** → `themes/awesome/static/css/base.css` を編集

## 元との比較

| 項目 | 旧（静的HTML） | 新（Hugo） |
|------|--------------|-----------|
| ヘッダー/フッター | iframe埋め込み | partialで共通化 |
| 新ページ追加 | HTMLを手書き | mdファイル1個 |
| SNSリンク管理 | footer.htmlを直接編集 | hugo.tomlを1か所 |
| コンテンツ | HTML | Markdown |
| フッターの年号 | 手動更新 | 自動 |

## ライセンス

Unlicense @ 2025 こんせんと
