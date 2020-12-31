# install apache storm


#
version 0.9.4



```bash
mvn clean install

# go the nimbus container
storm jar hello-world-1.0-SNAPSHOT.jar storm.cookbook.HelloWorldTopology hoang
# check http://localhost:49080
```

## Resources
Very good explaination
https://www.freecodecamp.org/news/apache-storm-is-awesome-this-is-why-you-should-be-using-it-d7c37519a427/

https://www.simplilearn.com/apache-storm-advanced-concepts-tutorial-video
