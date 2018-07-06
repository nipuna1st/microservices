FROM openjdk:8
EXPOSE 8080
ADD ./build/libs/com-dashboard-service-0.0.1.jar ./com-dashboard-service-0.0.1.jar
ENTRYPOINT ["java","-jar","-Duser.timezone=GMT+0530","com-dashboard-service-0.0.1.jar"]