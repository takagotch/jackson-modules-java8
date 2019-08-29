### jackson-modules-java8
---
https://github.com/FasterXML/jackson-modules-java8

```java
ObjectMapper mapper = new ObjectMapper()
  .registerModule(new ParameterNamesModule())
  .registerModule(new Jdk8Module())
  .registerModule(new JavaTimeModule());
  
ObjectMapper mapper = JsonMapper.builder()
  .registerModule(new ParameterNamesModule())
  .registerModule(new Jdk8Module())
  .registerModule(new JavaTimeModule())
  .build();

ObjectMapper mapper = new ObjectMapper();
mapper.findAndRegisterModules();
```

```
```

```
```


