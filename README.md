# spring-boot-starter-sample-rest

Sample starter project for RESTful Services using Spring Boot

### To Test the service

- cd to root of the project
- Run the below maven command
```  
mvn test
```

### To Run the service

- cd to root of the project 
- Run the below maven command
```
mvn spring-boot:run
```

### Alternate way to package and run the service

- cd to root of the project
- Run the below maven command
``` 
mvn package
```
- cd to target directory
- Run the below command 
```
java -jar spring-boot-starter-sample-rest-0.0.1-SNAPSHOT.jar
```

### Manually testing the service
```
curl "http://localhost:8080/greeting"

curl "http://localhost:8080/greeting?name=Ramo"
```
