# 基本的な使い方
- `docker compose up` でコンテナを起動する。
- `docker compose down` でコンテナを停止する。
- `docker compose down -v` でコンテナを停止し、ボリュームを削除する。
  - ボリュームを削除すると、データベースのデータも削除されるので注意。
  - paAdminでデータベースのデータをダンプしておくこと。

# Dockerコンテナの構成
- `docker-compose.yml` で定義されている。