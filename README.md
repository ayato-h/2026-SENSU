# 2026-SENSU

## セットアップ

### 1. 仮想環境を作成

```bash
python3 -m venv .venv
```
### 2. 仮想環境を有効化
```bash
source .venv/bin/activate
```

### 3. 必要なパッケージをインストール
```bash
pip install -r requirements.txt
```

### 4. Djangoのマイグレーション
```bash
python manage.py migrate
```

### 5. 開発サーバーを起動
```bash
python manage.py runserver
```
