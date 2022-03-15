FROM maven:3.8.4-jdk-11-slim AS builder
WORKDIR "/app/worker"
ADD ./app/pom.xml /app/worker
RUN mvn dependency:resolve && mvn package

FROM openjdk:11-jre-slim
WORKDIR "/app/worker"
COPY --from=builder /app/worker/target ./target
CMD java -jar ./target/worker-jar-with-dependencies.jar