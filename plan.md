# Todoリスト実装計画 (Laravel + Vue)

## 技術スタック
- **Backend**: Laravel 11
- **Frontend**: Vue 3 (Inertia.js)
- **Infrastructure**: Docker (Laravel Sail)
- **Database**: MySQL
- **Styling**: Vanilla CSS (`destyle.css` 使用)
- **追加機能**: 論理削除 (Soft Deletes)

## 実装ステップ
1. **初期設定**: Laravel + Sail (Docker) 環境の構築。
2. **Breeze導入**: `laravel/breeze` で Vue + Inertia 環境を構築。
3. **DB作成**: `todos` テーブルのマイグレーションとモデル作成。
4. **ロジック**: CRUD（論理削除含む）の実装。
5. **UI**: Vueコンポーネント作成とスタイリング。
