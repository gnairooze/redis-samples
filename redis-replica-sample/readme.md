# sample redis replication

## description

this docker compose file creates two containers from redis nodes. one of them is master and the other is slave.

## run the containers

first create the network

```shell
docker network create --gateway 10.20.0.1 --subnet 10.20.0.0/24 redis-net
```

then run docker-compose

```shell
docker-compose up
```

to run as daemon

```shell
docker-compose up -d
```

## run commands in the redis-master container shell

from the host

```shell
docker exec -it redis-master /bin/bash
```
