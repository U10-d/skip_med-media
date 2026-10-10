# GitHub Pages 公開用ファイル

GitHub の `U10-d` アカウントに公開リポジトリ **`U10-d.github.io`** を作成し、このフォルダーの `index.html`、`privacy-policy.html`、`app-ads.txt`、`.nojekyll` をそのリポジトリのルートに配置します。`README.md` は配置不要です。

GitHub の Settings → Pages で `Deploy from a branch`、`main`、`/(root)` を選択します。公開後、次の URL をブラウザで確認します。

- `https://u10-d.github.io/`
- `https://u10-d.github.io/privacy-policy.html`
- `https://u10-d.github.io/app-ads.txt`

`app-ads.txt` の応答本文は次の1行である必要があります。

```text
google.com, pub-5411827831776005, DIRECT, f08c47fec0942fa0
```

App Store Connect の対象アプリの iOS バージョン情報で **マーケティング URL** を `https://u10-d.github.io/` に設定し、公開ページ下部の「デベロッパWebサイト」がその URL を開くことを確認します。「App のプライバシー」にあるプライバシーポリシー URL は `https://u10-d.github.io/privacy-policy.html` に設定します。アプリ内のプライバシーポリシーリンクも同じ URL を使用します。

`skip_med` リポジトリの GitHub Pages は通常 `https://u10-d.github.io/skip_med/` に公開されます。この場所の `app-ads.txt` は AdMob が確認するホスト直下の `https://u10-d.github.io/app-ads.txt` とは異なります。

公開ページと App Store のリンクが反映されたら、AdMob の「アップデートを確認」を実行します。反映には時間がかかる場合があります。
