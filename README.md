# Laravel + Vue Todo App (Docker)

学習用のシンプルなCRUD機能を備えたTodoアプリケーションです。Laravel 11 と Vue 3 (Inertia.js) を使用し、Docker (Laravel Sail) 環境で動作します。

## 主な機能
- Todoの作成・表示・編集・削除 (CRUD)
- 論理削除 (Soft Deletes)
- リアクティブなUI (Vue.js)

## 技術スタック
- **Backend**: Laravel 11
- **Frontend**: Vue 3 (Inertia.js), Vanilla CSS
- **Infrastructure**: Docker (Laravel Sail)
- **Database**: MySQL (Dockerコンテナ内)

## 開発環境のセットアップ (予定)
1. Docker Desktop の起動
2. `./vendor/bin/sail up -d` でコンテナ起動
3. `./vendor/bin/sail artisan migrate` でマイグレーション実行
4. `./vendor/bin/sail npm install && ./vendor/bin/sail npm run dev` でフロントエンドビルド
