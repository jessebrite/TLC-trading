FROM adoptopenjdk/openjdk11:alpine-jre

ARG APP_NAME="order-service"
ARG APP_VERSION="0.0.1"
ARG JAR_FILE="/target/${APP_NAME}-${APP_VERSION}.jar"

COPY ${JAR_FILE} order-service-0.0.1.jar
ENTRYPOINT ["java", "-jar", "order-service.jar"]