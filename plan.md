# Todoリスト実装計画 (Laravel + Vue)

Laravel 11 と Vue.js (Inertia.js) を使用したシンプルなCRUD Todoアプリの実装計画です。

## 技術スタック
- **Backend**: Laravel 11
- **Frontend**: Vue 3 (Inertia.js)
- **Database**: SQLite
- **Styling**: Vanilla CSS (`destyle.css` 使用)
- **追加機能**: 論理削除 (Soft Deletes)

## データベース設計 (`todos` テーブル)
- `id` (PK)
- `title` (string)
- `is_completed` (boolean)
- `created_at` / `updated_at`
- `deleted_at` (Soft Deletes)

## 実装ステップ
1. **初期設定**: `laravel/breeze` を使用して Vue + Inertia 環境を構築。
2. **DB作成**: `todos` テーブルのマイグレーションと `Todo` モデルの作成。
3. **ロジック実装**: `TodoController` でCRUD（論理削除含む）を実装。
4. **UI実装**: VueコンポーネントでCRUD操作画面を作成。
5. **デザイン**: Vanilla CSS でプレミアムなUIを適用。
