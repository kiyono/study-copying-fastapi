# FastAPI Example

## Description

以下の写経

https://zenn.dev/sh0nk/books/537bb028709ab9

## TODO

- フロントの作成
- ユーザー登録 API の作成
- ユーザー認証 API の作成

## Usages

```console
$ docker compose up

# 初回（migrate）
$ docker compose exec demo-app poetry run python -m api.migrate_db
```

http://localhost:8000/docs にアクセス
