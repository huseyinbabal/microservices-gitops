FROM  amazoncorretto:17

WORKDIR /usr/src/app

COPY build/libs/*-SNAPSHOT.jar ./echo-server.jar

CMD ["java", "-jar", "/usr/src/app/echo-server.jar"]
