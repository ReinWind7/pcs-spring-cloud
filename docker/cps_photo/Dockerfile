FROM java:8-jre
MAINTAINER reinwind

ADD ./target/cps_photo.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/cps_photo.jar"]

EXPOSE 8081