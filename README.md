# COLOR HUNT PWA

## 内容
- `index.html`: ゲーム本体
- `manifest.json`: PWA設定
- `service-worker.js`: オフラインキャッシュ
- `icons/`: アプリアイコン

## 公開方法（無料の例: GitHub Pages）
1. GitHubにログインし、新しいPublicリポジトリを作成（例: `color-hunt`）。
2. このZIPを解凍し、中のファイルと`icons`フォルダをリポジトリ直下にアップロード。
3. リポジトリの Settings → Pages を開く。
4. Build and deployment で `Deploy from a branch` を選び、`main` と `/ (root)` を指定して保存。
5. 数分後に表示される `https://ユーザー名.github.io/color-hunt/` のURLをSafariで開く。

## iPhoneへの追加
1. Safariで公開URLを開く（HTTPSが必要）。
2. 共有ボタン →「ホーム画面に追加」。
3. 表示名を確認して「追加」。追加後はアイコンから起動できます。

## 注意
- このZIPを作成しただけではインターネット公開されません。GitHub Pagesなどへのアップロードが必要です。
- 初回アクセス後にキャッシュされると、次回以降はオフラインでも基本的なゲームを起動できます。
- 現在のスコアは画面表示のみで、端末をまたぐランキングや永続保存はまだありません。
