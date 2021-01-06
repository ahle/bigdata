## Run cassandra by docker
```
docker run --name cassandra1 -p 7000:7000 -p 127.0.0.1:9042:9042 -p 127.0.0.1:9160:9160 cassandra -d
```

## Connect to cassandra
use VSCode with extension cassandra workbench. Attention: should open a workspace to generate the configuration.
