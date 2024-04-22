## Angular のチュートリアルで作成した Web アプリケーション

チュートリアル
https://angular.jp/tutorial/first-app

### 前提

- Node.js がインストールされていること(v20.12.1 で動作確認)

### 使用方法

1. ダウンロードしたリポジトリのディレクトリに移動

2. json-server のインストールと起動

```
npm install -g json-server
json-server --watch db.json
```

3. Angular Web サーバーの起動

```
ng serve
```

4. http://localhost:4200/ にアクセス

- 検索窓で画像の下部の 2 行目に表示されている名称でフィルタ可能
- 各画像の`Learn More`リンクで詳細ページへ移動
- 詳細ページで`FIRST NAM`、`LAST NAME`、`EMAIL`を入力して`Apply Now`ボタンを押下すると、ブラウザのコンソールログに入力した内容が表示される。
