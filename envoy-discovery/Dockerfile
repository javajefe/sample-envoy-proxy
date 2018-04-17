FROM openjdk:alpine
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD build/libs/envoy-discovery-1.0.0.jar envoy-discovery.jar
ENTRYPOINT ["java", "-jar", "/envoy-discovery.jar"]
EXPOSE 9200