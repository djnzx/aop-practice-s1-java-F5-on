### Java Template Repository

### compile

```shell
mvn compile
```

### clean

```shell
mvn clean
```

### test

```shell
mvn test
```

### reformat code

```shell
mvn spotless:apply
```

### check formatting

```shell
mvn spotless:check
```


### Required Java version

This project requires JDK 25, as configured by `maven.compiler.release`
in `pom.xml`. Before building, check:

```shell
java -version
javac -version
mvn -version
```

Maven must run with JDK 25. If it uses another version, configure `JAVA_HOME`.
