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
```

3. 通过docker打开mysql

```shell script
docker start msyql
```
如果是第一次运行该项目，要先在MySQL中创建一个名为vhr的空数据库。

## 后端默认访问地址
http://localhost:8081/index.html#/

