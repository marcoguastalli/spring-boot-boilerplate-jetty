# Spring Boot Boilerplate Jetty
Spring Boot Boilerplate for Spring Boot MicroService with Jetty

### Prerequisites
- JDK v21
- Maven v3.9.6

### Build
- `setjdk21`
- `./mvnw clean package`
- `./mvnw clean test`

### Run
- `./mvnw spring-boot:run -Dspring-boot.run.profiles=dev`
- `./mvnw spring-boot:run -Dspring-boot.run.profiles=docker`

### Play
- http://localhost:8081/spring-boot-boilerplate-jetty/v1/version

### Api documentation
- http://localhost:8081/spring-boot-boilerplate-jetty/swagger-ui/index.html