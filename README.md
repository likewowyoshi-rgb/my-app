# Dream Catcher Pro LP

静的なランディングページ（HTML 1枚 + 画像/動画アセット）です。GitHub Pagesでそのまま公開できます。

## 構成

- `index.html` … CSS/JSを**1ファイルに統合**済み
- `assets/` … 画像・動画素材

## ローカルで確認

ブラウザで `index.html` を開くだけでOKです（ローカル再生できる環境であれば動画も再生されます）。

## GitHub Pages で公開する手順

1. GitHubで新しいリポジトリを作成（例: `dream-catcher-pro-lp`）
2. このフォルダ一式をpush
3. GitHubの **Settings → Pages**
4. **Build and deployment → Source** を `Deploy from a branch`
5. Branch を `main` / Folder を `/ (root)` にして保存
6. 数十秒後に表示されるURLにアクセス

## 注意

- 動画ファイルが大きい場合、GitHubの容量制限に注意してください（必要なら圧縮 or 外部ホスティング）。
