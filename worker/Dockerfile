FROM maven:3.9.6-eclipse-temurin-21-alpine AS builder
COPY . /src
WORKDIR /src/
RUN mvn dependency:resolve
RUN mvn package

FROM eclipse-temurin:21-jre-alpine
COPY --from=builder /src/target/ /src/target/
WORKDIR /src/target
CMD java -jar worker-jar-with-dependencies.jar