FROM maven:3.5-jdk-8-alpine AS builder
WORKDIR "/app/worker"
ADD ./app/pom.xml /app/worker
RUN mvn dependency:resolve && mvn package

FROM openjdk:8-jre-alpine
WORKDIR "/app/worker"
COPY --from=builder /app/worker/target ./target
CMD java -jar ./target/worker-jar-with-dependencies.jar