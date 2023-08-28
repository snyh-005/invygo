FROM openjdk:17-alpine
LABEL authors="saniahmathews"

EXPOSE 8080
ADD target/staff-scheduling-system.jar staff-scheduling-system.jar
ENTRYPOINT ["java", "-jar", "/staff-scheduling-system.jar"]