FROM openjdk:21-jdk
EXPOSE 8881
ARG JAR_FILE=target/accounting-*.jar
ADD ${JAR_FILE} accounting.jar
ENTRYPOINT ["java", "-jar", "/accounting.jar"]
