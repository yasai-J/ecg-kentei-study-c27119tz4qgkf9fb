# 心電図検定3級ドリル

心電図検定3級対策の隙間時間学習アプリ（PWA）。GitHub Pagesで公開すると、スマホのホーム画面に追加してアプリのように使えます。一度開けばオフラインでも動きます。

## 公開手順（GitHub Pages）

1. GitHubで新しいリポジトリを作る（例：`ecg3-drill`、Public）
2. このフォルダの中身をすべてアップロード
   - 「Add file」→「Upload files」で、`index.html` `manifest.webmanifest` `sw.js` `.nojekyll` `README.md`、アイコン画像4つ（`icon-192.png` `icon-512.png` `icon-maskable-512.png` `apple-touch-icon.png`）をドラッグ
3. リポジトリの「Settings」→「Pages」
   - Source：`Deploy from a branch`
   - Branch：`main` / `/(root)` を選んで「Save」
4. 1〜2分後、`https://<ユーザー名>.github.io/ecg3-drill/` で開けます

## スマホのホーム画面に追加

- iPhone（Safari）：共有ボタン →「ホーム画面に追加」
- Android（Chrome）：メニュー →「アプリをインストール」または「ホーム画面に追加」

## 更新するとき

1. `index.html` を差し替える
2. `sw.js` 1行目の `ecg3drill-v8` の数字を上げる（例：`v9`）
3. アプリを一度閉じて開き直すと新しい版になります

## 注意

- 学習記録は各端末のブラウザ内（localStorage）に保存されます。端末をまたいでは共有されません。
- 問題と解説はオリジナルです。数値や基準は公式テキストで確認してください。
