FROM eclipse-temurin:17-jdk-alpine

WORKDIR /app

COPY target/TP33_Deploiement_app_SpringBoot_Kubernetes-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8084

ENTRYPOINT ["java","-jar","app.jar"]