FROM adoptopenjdk/openjdk11
VOLUME /tmp
ADD target/order-service.jar order-service.jar
ENTRYPOINT ["java","-jar","/order-service.jar"]
