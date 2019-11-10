FROM openjdk
COPY ../spring-petclinic/src/target/petclinic*.jar /var/petclinic/petclinic.jar
CMD /usr/bin/java  -jar /var/petclinic/petclinic.jar --server.port=80
EXPOSE 80