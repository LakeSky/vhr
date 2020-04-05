# 项目文档

## 项目启动

1. 通过docker，运行rabbitmq
    
```shell script
docker start rabbitmq
```

2. 通过docker打开redis

```shell script
docker start redis

docker exec -it redis /bin/bash

redis-cli

config set requirepass "123"

Ctrl+c

redis-cli -a 123

config get requirepass
```

3. 通过docker打开mysql

```shell script
docker start msyql-test
```
## 后端默认访问地址
http://localhost:8081/index.html#/

