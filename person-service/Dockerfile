FROM maven:3.6.3-adoptopenjdk-11
COPY . /person-service
WORKDIR /person-service
RUN mvn clean package
CMD ["java" , "-jar", "target/person-service-1.0.0.jar"]
EXPOSE 80
