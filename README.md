Spring Boot sample from : https://spring.io/guides/gs/spring-boot/
Enabled for mutual SSL authentication. The server is configured to use a self-signed certificate.
The client is configured to trust the server certificate and also supply its own self-signed certificate during the handshake

Required Software:
1.gradle
2.java 11
3.curl

make sure JAVA_HOME property is set

Running the Sample Server and Client(curl):

1. cd gs-spring-boot-ssl
2. cd initial
3. ./gradlew bootRun
4. In another terminal
5. cd gs-spring-boot-ssl/certs
6. ./run.sh 
