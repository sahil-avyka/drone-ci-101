FROM registry.access.redhat.com/ubi8/openjdk-11
RUN mvn clean package -DskipTests
COPY target/*.jar /deployments/
