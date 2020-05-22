### Incompatibility of [log4jdbc-spring-boot-starter](https://github.com/candrews/log4jdbc-spring-boot-starter) ver. 2.0.0 and Spring Cloud
 
Successful run without Spring Cloud dependencies

```
mvn spring-boot:run
```

Any Spring Cloud dependencies lead to the crash

```
mvn spring-boot:run -P cloud
``` 

---

[Issue #13](https://github.com/candrews/log4jdbc-spring-boot-starter/issues/13)