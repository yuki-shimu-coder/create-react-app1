# react-spa-project
react18の環境構築

# はじめに

以下のツールを事前にインストールしてください

- Docker

## 開発の手順

ルートディレクトリで、下記コマンドを実行してください

```
docker compose build
```

ビルドが完了したら、下記コマンドでDockerコンテナを起動してください

```
docker compose up -d
```

http://localhost:3000 にアクセスし、reactアプリが起動していることを確認してください。※起動には時間がかかります。