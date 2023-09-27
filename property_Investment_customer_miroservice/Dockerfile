FROM adoptopenjdk/openjdk11
VOLUME /tmp
ADD target/customer-service.jar customer-service.jar
ENTRYPOINT ["java","-jar","/customer-service.jar"]
