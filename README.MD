# 项目文档

## 项目启动

1. 打开本地docker，运行rabbitmq
    
```shell script
docker start rabbitmq
```

2. 通过ssh打开redis

```shell script
docker start redis

docker exec -it redis /bin/bash

redis-cli

config set requirepass "123"

Ctrl+c

redis-cli -a 123

config get requirepass
```

## 后端默认访问地址
http://localhost:8081/index.html#/

