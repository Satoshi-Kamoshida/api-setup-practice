# api-setup-practice

## 概要

COACHTECH 教材 Tutorial 11-1「API開発環境の構築と疎通確認」で作成した成果物です。<br>
**API開発専用のプロジェクトをセットアップし、「Hello World」レベルの疎通確認**

## 使用技術

- PHP 8.x
- Laravel 10.x
- REST API（JSONレスポンス）
- Postman（動作確認）

## 学んだこと

## .env（環境変数）について

### 1. `.env`とは？

`.env` の `env` は **environment（環境）** の略です。

Laravelでは、`.env` にアプリケーションの**環境によって変わる設定値**を記述します。

```text
.env
＝ アプリの環境依存の設定値を、コードの外から与えるためのファイル

```

## 動作確認

1. 'http://localhost/api/hello'へGETリクエストを送信<br>
2. Postman Desktopにて疎通確認：ステータスコード（200 OK）
