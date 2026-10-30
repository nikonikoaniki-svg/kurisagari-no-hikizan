# かんたん！くりさがりのひき算

減加法を6段階で学ぶ、タコまるの学習アプリです。通常練習・連続正解チャレンジ・タイムチャレンジ・教師用設定・記録を搭載しています。

## GitHub Pagesで公開する

1. このZIPをパソコン上で展開します。
2. GitHubで新しいリポジトリを作ります（例：takomaru）。GitHub Freeでの公開はPublicのリポジトリを使用します。
3. リポジトリの「Add file」→「Upload files」で、展開したフォルダーの**中身**をアップロードし、コミットします。ZIPそのものや外側のフォルダーをアップロードしないでください。
4. リポジトリ直下に index.html、style.css、app.js、takomaru-clear.png が並ぶことを確認します。
5. 「Settings」→「Pages」を開きます。
6. 「Build and deployment」の「Source」を「Deploy from a branch」に設定します。
7. 「Branch」で「main」、フォルダーで「/(root)」を選び、「Save」を押します。
8. 公開が完了したら、Pages設定画面に表示されるURLから開きます。

GitHub PagesではChatGPTへのログインは不要です。

## 同梱ファイル

- index.html：アプリ画面
- style.css：デザイン
- app.js：学習処理・設定・記録
- takomaru-clear.png：背景透過済みのタコまる
- .nojekyll：静的ファイルをそのまま公開する指定（隠しファイルが表示されなくても、基本の4ファイルで動きます）

外部ライブラリやビルド作業は不要です。画像とプログラムは相対パスで参照しているため、リポジトリ名が付くURLでも使用できます。

## 学習記録について

記録は端末・ブラウザー・公開URLごとに保存されます。以前のChatGPT側のアプリから、GitHub Pagesへ記録は自動で移りません。JSON出力は保管用で、この版にはインポート機能はありません。

氏名は入力せず、児童番号等で利用してください。ブラウザーの保存データを消すと記録も消えます。GitHubへ児童の学習記録をアップロードする必要はありません。

## 指導について

「10から引く → 残りを足す」減加法に統一しています。通常練習は速さより理解と正確さを優先します。詳しい説明はアプリ内「先生のページ」→「このアプリについて」をご覧ください。

## 公式手順

https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
