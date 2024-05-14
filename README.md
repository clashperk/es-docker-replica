## Increase vm.max_map_count
```
sudo sysctl -w vm.max_map_count=262144
```


## Get CA Certificate

```
docker compose cp es01:/usr/share/elasticsearch/config/certs/ca/ca.crt .
```
