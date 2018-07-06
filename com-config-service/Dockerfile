FROM openjdk:8
EXPOSE 8080
ADD ./build/libs/com-config-service-0.0.1.jar ./com-config-service-0.0.1.jar
ENTRYPOINT ["java","-jar","-Duser.timezone=GMT+0530","com-config-service-0.0.1.jar"]