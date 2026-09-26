# SENSU システム設計

## 技術構成

- Backend: Django
- Database: SQLite
- Frontend: Django Templates
- Authentication: Django Auth

## 主要機能

- ネタ登録
- ネタ一覧
- ネタ詳細
- ネタ編集
- ネタ削除
- タグ
- 検索

## データモデル

```text
User
  ↓
Neta
  ↓
Tag
