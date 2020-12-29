# install apache storm


#
version 0.9.4



```bash
mvn clean install

# go the nimbus container
storm jar hello-world-1.0-SNAPSHOT.jar storm.cookbook.HelloWorldTopology hoang
# check http://localhost:49080
```
