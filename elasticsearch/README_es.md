## hub.docker.com
https://hub.docker.com/_/elasticsearch?tab=tags&page=1&ordering=last_updated
https://hub.docker.com/_/kibana?tab=tags&page=1&ordering=last_updated
[参考视频](https://www.bilibili.com/video/BV1Qz411e7yx?p=5)

## tag
elasticsearch:6.5.4
kibana:6.5.4

## cmd
```shell
docker-compose up -d

# 启动很慢 查看日志
docker-compose logs -f
```

## 问题
### elasticsearch exited with code 78 on Ubuntu 20.04 LTS
elasticsearch    | ERROR: [1] bootstrap checks failed
elasticsearch    | [1]: the default discovery settings are unsuitable for production use; at least one of [discovery.seed_hosts, discovery.seed_providers, cluster.initial_master_nodes] must be configured
