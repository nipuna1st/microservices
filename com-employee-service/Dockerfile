FROM openjdk:8
EXPOSE 8080
ADD ./build/libs/com-employee-service-0.0.1.jar ./com-employee-service-0.0.1.jar
ENTRYPOINT ["java","-jar","-Duser.timezone=GMT+0530","com-employee-service-0.0.1.jar"]