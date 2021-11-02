FROM openjdk:11
VOLUME /tmp
EXPOSE 9888
ADD ./target/cjava_config_server-0.0.1-CJAVA.jar config-server.jar
ENTRYPOINT ["java","-jar","/config-server.jar"]