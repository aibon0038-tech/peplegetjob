# 業界別 採用市場分析ツール

業界を選択すると、採用市場分析、求職者の悩み、応募訴求、競合求人の傾向、Indeedで応募が獲得できている求人票の傾向、求人票テンプレートを確認できる静的HTMLツールです。

## GitHub Pagesで公開する方法

1. GitHubで新しいリポジトリを作成します。
2. このフォルダ内の以下ファイルをリポジトリ直下にアップロードします。
   - `index.html`
   - `app.js`
   - `styles.css`
   - `README.md`
   - `.nojekyll`
3. GitHubのリポジトリ画面で `Settings` を開きます。
4. 左メニューの `Pages` を開きます。
5. `Build and deployment` の `Source` を `Deploy from a branch` にします。
6. `Branch` を `main`、フォルダを `/root` にして保存します。
7. 数十秒から数分後に、GitHub Pagesの公開URLが表示されます。

## 公開後のURL例

`https://ユーザー名.github.io/リポジトリ名/`

## 注意

このツールは静的サイトなので、サーバーやデータベースは不要です。`index.html`、`app.js`、`styles.css` が同じ場所にあれば動作します。
