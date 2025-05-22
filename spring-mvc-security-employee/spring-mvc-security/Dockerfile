FROM openjdk:21-jdk

WORKDIR /app

COPY target/spring-mvc-security-0.0.1-SNAPSHOT.jar /app/spring-mvc-security.jar

EXPOSE 8080

CMD ["java", "-jar", "spring-mvc-security.jar"]