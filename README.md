# service-introduction

Akiraが公開しているアプリ・サービスを紹介する GitHub Pages サイトです。

## ローカル確認

そのまま `index.html` を開くか、簡易サーバで確認できます。

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## GitHub Pages 公開手順

1. このリポジトリを GitHub に push する
2. GitHub の **Settings → Pages** を開く
3. **Source** を `Deploy from a branch`、**Branch** を `main` / `/ (root)` に設定して Save
4. 数十秒後、`https://<username>.github.io/service-introduction/` で公開される

独自ドメインを使う場合は、リポジトリ直下に `CNAME` ファイル（例: `example.com` のみ記載）を追加してください。

## ファイル構成

- `index.html` — ランディングページ本体
- `styles.css` — スタイル
- `app-ads.txt` — 広告ネットワーク検証用ファイル（現在は空。必要になったら記述を追加）
- `.nojekyll` — GitHub Pages の Jekyll 処理を無効化
