# Kafka

Run kafka-server and kafka-ui in the local

```bash
docker-compose up -d
```

set up /etc/hosts

```bash
127.0.0.1	kafka	zookeeper	kafka-ui
```

after service up we can access kafka-ui in the http://localhost:38080  and access kafka-clusters in the local with bootstrap-server 127.0.0.1:9092
