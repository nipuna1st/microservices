FROM openjdk:8
EXPOSE 8080
ADD ./build/libs/com-eureka-service-0.0.1.jar ./com-eureka-service-0.0.1.jar
ENTRYPOINT ["java","-jar","-Duser.timezone=GMT+0530","com-eureka-service-0.0.1.jar"]