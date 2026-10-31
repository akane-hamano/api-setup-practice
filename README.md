# api-setup-practice

## 概要
COACHTECH 教材 Tutorial 11-1「API開発環境の構築と疎通確認」で作成した成果物です。API開発専用のプロジェクトをセットアップし、「Hello World」レベルの疎通確認を行いました。


## 使用技術
- PHP 8.x
- Laravel 10.x
- REST API（JSONレスポンス）
- Postman（動作確認）

## 学んだこと
- API用のルートを定義するファイル（routes/api.php）についてとその書き方
- Poatman（APIテストツール）の基本的な使い方
- 

## 動作確認
今回はPostmanで動作確認を行います。以下の手順を参考に動作確認を行ってください。

### 1. Postmanを起動する

### 2. 「＋」タブをクリックして、新規リクエストを作成する

### 3. メソッドをGETにする

### 4. URLに http://localhost/api/hello を入力する

### 5. 「Send」ボタンをクリックする

### 確認ポイント
- ステータスコード：200OK
- Content-Type：application/json
- レスポンスボディ：{"message": "Hello, API!"}
