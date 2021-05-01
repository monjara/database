# mysql5.7
## 使い方

- 起動
```
docker-compose up -d
```

- コンテナ内でコマンド実行
```
docker exec -it mysql57_db_1 bash
```

サービスの停止
```
docker-compose stop
```

コンテナの停止、削除、記憶領域削除
```
docker-compose down
```

## .env
こちらにmusqlの設定を記述

