# sillyhat-docker-redis

## 部署
```
docker stack deploy -c docker-compose.yml sillyhat
```

## redis.conf

### 设置最大内存
```
maxmemory 512MB
```