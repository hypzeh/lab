# Run

```shell
sudo chown -R 5050:5050 ./data/pgadmin
sudo chmod -R u+rwx ./data/pgadmin

docker network create postgres-network
docker compose up -d
docker compose logs -f --tail=200
```