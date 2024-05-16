## Increase vm.max_map_count
```
sudo sysctl -w vm.max_map_count=262144
```

## Get CA Certificate

```
docker compose cp es01:/usr/share/elasticsearch/config/certs/ca/ca.crt .
```

## ENV
```
ELASTIC_PASSWORD=
KIBANA_PASSWORD=
STACK_VERSION=8.13.4
CLUSTER_NAME=docker-cluster
LICENSE=basic
ES_PORT=9200
KIBANA_PORT=5601
MEM_LIMIT=2147483648
COMPOSE_PROJECT_NAME=es-replica
PUBLIC_IP=
```