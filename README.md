# next-tutorial

## 環境構築
1. プロジェクトのディレクトリに移動
```
cd path/to/next-tutorial
```

2. （初回のみ）コンテナイメージのビルド
```
docker-compose build
```

3. コンテナの立ち上げ
```
docker-compose up -d
```

4. (コンテナの停止)
```
docker-compose down
```

- コンテナ内でコマンド操作
```
docker-compose exec node /bin/bash
```
or
```
Docker Desktop から nodeコンテナを指定し、「open in terminal」を押下
```
