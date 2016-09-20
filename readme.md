RxVertx SpringBoot
====


### Package
```
> mvn clean package
```

### Run
```
> java -jar target/vertx-rx-springboot-${version}.jar
```

#### Docker
```
> docker run -t -i -p 8080:8080 --link postgres:postgres --link influxdb:influxdb tbk/postgres-metrics
```