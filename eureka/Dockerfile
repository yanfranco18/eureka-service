FROM openjdk:11.0-oracle
VOLUME /tmp
EXPOSE 8091
ADD ./target/eureka-0.0.1-SNAPSHOT.jar eureka-server.jar
ENTRYPOINT ["java","-jar","/eureka-server.jar"]