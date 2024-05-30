# sample redis replication

## description

this docker componse file creates two containers from redis nodes. one of them is master and the other is slave.

## run the docker comopse

```shell
docker-compose up
```

## run commands in the redis-master container shell

from the host
```shell
docker exec -it redis-master /bin/bash
```


