FROM qizhonglin/redis_base

ENTRYPOINT [ "redis-server", "--logfile /var/log/redis/redis-server.log", "--slaveof redisprimary 6379" ]
