FROM java:8-jre
MAINTAINER reinwind

ADD ./target/cps_user.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/cps_user.jar"]

EXPOSE 8080