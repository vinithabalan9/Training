FROM openjdk:8
ARG JAR FILE=target/hello-boot.jar
COPY ${JAR_FILE} hello-boot.jar
EXPOSE 8780
ENTRYPOINT ["JAVA", "-Jar","/hello-boot.jar"]