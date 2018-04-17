## Envoy Proxy with Microservices

This is a fork of https://github.com/piomin/sample-envoy-proxy repository.
Detailed description can be found here: [Envoy Proxy with Microservices](https://piotrminkowski.wordpress.com/2017/10/25/envoy-proxy-with-microservices/)

How to build and run:

1. Open root folder in console
2. `gradlew bootRepackage` builds all Spring Boot applications
3. `docker-compose up -d --build` builds and runs all Docker containers

After that you can use URLs:
- http://localhost:9901 - Envoy admin endpoint
- http://localhost:10000/person and http://localhost:10000/product - simple CRUD applications
- http://localhost:9411 - Zipkin control panel