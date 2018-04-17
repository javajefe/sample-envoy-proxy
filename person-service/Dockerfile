FROM openjdk:alpine
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD build/libs/person-service-1.0.0.jar person-service.jar
ENV PORT 9300
ENV DISCOVERY_URL http://192.168.99.100:9200
ENTRYPOINT ["java", "-jar", "/person-service.jar"]
EXPOSE ${PORT}