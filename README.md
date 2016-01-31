## RESTful web service with Spring

Build the JAR file with 
```
mvn clean package 
```

and run the JAR by:
```
java -jar target/gs-rest-service-0.1.0.jar
```
Visit:
> http://localhost:8080/greeting

{"id":1,"content":"Hello, World!"}

> http://localhost:8080/greeting?name=Anna

{"id":1,"content":"Hello, Anna!"}
<br>
<br>
<br>
<br>
<br>
reference:
https://spring.io/guides/gs/rest-service/
