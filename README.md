# Spring Boot Microservices System
This is a Spring Boot microservices system built to users to order products and get notifications.
## Architecture
<img width="1621" alt="image" src="https://github.com/bl-liu6/Ordering-Microservice-System/assets/111820499/e286b67e-bc78-4a54-9a6c-b3f457dce489">

## Run the application using Docker

1. Run `mvn clean package -DskipTests` to build the applications and create the docker image locally.
2. Run `docker-compose up -d` to start the applications.

## Run the application without Docker

1. Run `mvn clean verify -DskipTests` by going inside each folder to build the applications.
2. After that run `mvn spring-boot:run` by going inside each folder to start the applications.

