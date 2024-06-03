# redis-db

## Setup redis using docker

###redis/redis-stack
* To start a Redis Stack container using the redis-stack image, run the following command in your terminal:
```
docker run -d --name redis-stack -p 6379:6379 -p 8001:8001 redis/redis-stack:latest
```

## Check redis status

You can then connect to the server using redis-cli, just as you connect to any Redis instance.

If you don’t have redis-cli installed locally, you can run it from the Docker container:
```
docker exec -it redis-stack redis-cli
```