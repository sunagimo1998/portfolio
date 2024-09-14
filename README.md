■Dockerコマンドメモ
# Docker 起動時
docker compose build --no-cache
docker compose up -d
docker compose exec frontend bash
# Docker 終了時
docker compose down
docker ps -aq | xargs docker rm
docker images -aq | xargs docker rmi
