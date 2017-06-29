FROM java:8-jre
MAINTAINER reinwind

ADD ./target/cps_comment.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/cps_comment.jar"]

EXPOSE 8082