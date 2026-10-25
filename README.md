# coder-yuuki.github.io

野久知 優希のiPhoneアプリの、サポートページとプライバシーポリシーをまとめた静的サイトです。
GitHub Pagesのユーザーサイト（`https://coder-yuuki.github.io/`）として公開する想定です。

## ページ

| URL | 内容 |
| --- | --- |
| `/` | アプリ一覧 |
| `/waripair/` | わりペア サポート |
| `/waripair/privacy.html` | わりペア プライバシーポリシー |
| `/shortidea/` | ShortIdea サポート |
| `/shortidea/privacy.html` | ShortIdea プライバシーポリシー |
| `/palettecount/` | PaletteCount サポート |
| `/palettecount/privacy.html` | PaletteCount プライバシーポリシー |

にゃんボイスは `nyanvoice.com`（別リポジトリ `nyanvoice_site`）にあります。

## 構成

- `assets/site.css` : 全ページ共通のスタイル。アプリごとの色は `body` の `data-app` で切り替えます
- `assets/img/` : アプリアイコンとApp Storeの画面画像
- `.nojekyll` : GitHub PagesでJekyllを使わない

## 手元での確認

```bash
python3 -m http.server 4174
```

`http://127.0.0.1:4174/` を開きます。

## 公開

1. GitHubに `coder-yuuki.github.io` という名前のリポジトリを作って push する
2. Settings → Pages で `main` ブランチ / `/(root)` を選ぶ

## 更新するとき

- プライバシーポリシーは、アプリが扱うデータを変えたら必ず見直し、「最終改定」の日付を更新します
- 価格はページに書かず、アプリ内とApp Storeの表示を案内します
