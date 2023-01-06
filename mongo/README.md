# Mongo

Run mongo replica-set in the local

```bash
docker-compose up -d
docker exec -it mongo1 bash
mongo
rs.initiate()
```

set up /etc/hosts

```bash
127.0.0.1 mongo1
```

after all we can access mongodb replica-set via 127.0.0.1:27017
