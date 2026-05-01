# Trading Journal GitHub Pages

これは、GitHub Pagesで公開するための静的トレード日誌サイトです。

## ファイル構成

```text
.
├── index.html              # トップページ / レポート一覧
├── reports/
│   └── 2026-W18.html       # 週次トレードレポート
├── .nojekyll               # GitHub PagesでJekyll処理を無効化
└── README.md
```

## GitHub Pagesへの公開手順

1. GitHubで新しいリポジトリを作成します。
   - 例: `trading-journal`
2. このフォルダ内のファイルをすべてアップロードします。
3. GitHubのリポジトリ画面で `Settings` → `Pages` を開きます。
4. `Build and deployment` で以下を選びます。
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Saveします。
6. 数十秒後、GitHub PagesのURLが表示されます。

## 新しいレポートの追加方法

1. 新しいHTMLレポートを `reports/` フォルダに追加します。
   - 例: `reports/2026-W19.html`
2. `index.html` にレポートカードを1枚追加します。
3. GitHubにcommitすると、サイトに反映されます。

## 注意

GitHub Pagesは基本的にWeb上で公開されます。口座番号、個人情報、証券会社ログイン情報などは絶対に入れないでください。
