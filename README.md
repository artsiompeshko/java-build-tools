# java-build-tools

## Maven

### Test
```
mvn test
```

### Create jars and war
Jars and war can be found in target/

```
mvn package
```

### Running admin jar
```
cd admin
mvn exec:java
```

### Running admin jar
```
cd web
mvn jetty:run
```

Navigate to localhost:8080