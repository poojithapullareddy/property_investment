FROM adoptopenjdk/openjdk11
VOLUME /tmp
ADD target/property-service.jar property-service.jar
ENTRYPOINT ["java","-jar","/property-service.jar"]
