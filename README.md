# redis-db

## Setup redis using docker

###redis/redis-stack
* To start a Redis Stack container using the redis-stack image, run the following command in your terminal:
```
docker run -d --name redis-stack -p 6379:6379 -p 8001:8001 redis/redis-stack:latest
```