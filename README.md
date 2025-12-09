# Todoアプリ

Todo管理アプリです。

Todoの作成・管理ができます。カテゴリを追加し、Todoをカテゴリ分けすることも可能です。Todo検索機能を使い、登録したTodoをTodo名・
カテゴリで検索することもできます。また、作成したTodoを更新・削除することも可能です。

## 環境構築

#### リポジトリをクローン

```
git clone git@github.com:ikemi-yuki/todo2.git
```

#### Laravelのビルド

```
docker-compose up -d --build
```

#### Laravelパッケージのダウンロード

```
docker-compose exec php bash
```

```
composer install
```

#### .envファイルの作成

```
cp .env.example .env
```

#### .envファイルの修正

```
DB_HOST=mysql

DB_DATABASE=laravel_db

DB_USERNAME=laravel_user

DB_PASSWORD=laravel_pass
```

#### キー生成

```
php artisan key:generate
```

#### マイグレーションを実行

```
php artisan migrate
```

## 使用技術（実行環境）

フレームワーク: Laravel:8.83.8

言語: HTML CSS PHP

Webサーバー: Nginx:1.21.1

データベース: MySQL:8.0.26

## ER図

![ER図](todo2.drawio.png)

## URL

アプリケーション：http://localhost/

phpMyAdmin：http://localhost:8080/
