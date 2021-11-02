FROM openjdk:11
VOLUME /tmp
EXPOSE 9888
ADD ./target/cjava_servicio_productos-0.0.1-CJAVA.jar servicio-productos.jar
ENTRYPOINT ["java","-jar","/servicio-productos.jar"]