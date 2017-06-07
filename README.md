[![Build Status](https://travis-ci.org/ctco-dev/spring-boot-graphql-template.svg?branch=master)](https://travis-ci.org/ctco-dev/spring-boot-graphql-template)

# spring-boot-graphql-template

Spring Boot, GraphQL template project with batteries included.

## Features
​
- Configuration with [dotenv](https://12factor.net/config)
  - Logging level, e.g. `LOGGING_LEVEL_ROOT=DEBUG`
  - App properties, e.g. `APP_DEPENDENCY_API_HOST=example.com`

## Required Software
- JDK 1.8

### Lombok

#### IntelliJ 

- Download and install Lombok [plugin](https://plugins.jetbrains.com/plugin/6317-lombok-plugin)
- Enable Annotation Processors
  -  Go to Setting->Build, Execution, Deployment-> Compiler->Annotation Processors
  -  Check _Enable annotation processing_
  
### GraphQL Tools
  
#### IntelliJ

- Download and install GraphQLJs [plugin](https://plugins.jetbrains.com/plugin/8097-js-graphql)

## Develop

`$ gradlew bootRun`

## Test

`$ gradlew test`

## Build

`$ gradlew buld`

## Tech Stack
- [Spring Boot](https://projects.spring.io/spring-boot/) : Application framework
- [Feign](https://github.com/OpenFeign/feign) : HTTP Client library
- [Lombok](https://projectlombok.org/features/index.html) : Utility library for Java language
- [GraphQL](http://graphql.org/learn/) : API query runtime
  - [GraphQL and GraphiQL Spring Framework Boot Starters](https://github.com/graphql-java/graphql-spring-boot)
  - [GraphQL Java Tools](https://github.com/graphql-java/graphql-java-tools)
  
## Cloud Deployment  

- [Azure](https://github.com/ctco-dev/spring-boot-graphql-template/blob/master/cloud/azure/README.md)

