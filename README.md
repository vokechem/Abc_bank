# springboot-postgresql-hibernate-crud
1.Creating projects using https://start.spring.io/ - Generate: Maven Project ,Java Version, Spring Boot, Dependencies: Web, JPA,PostgreSQL
2. import with your idea of choose (IntelliJ IDEA )
3.Configuring PostgreSQL-
spring.datasource.url=jdbc:postgresql://localhost:5432/employees
spring.datasource.username=--your username--
spring.datasource.password=--your password
spring.jpa.show-sql=true
3. Run application 
4.Testing REST APIs via Postman Client
- HTTP Method: POST - URL: http://localhost:8080/api/v1/employees 
- HTTP Method: GET by id - URL: http://localhost:8080/api/v1/employees/1
- HTTP Method: GET all - URL: http://localhost:8080/api/v1/employees
- HTTP Method: put - updating  http://localhost:8080/api/v1/emploees/7
- HTTP Method: DELETE  http://localhost:8080/api/v1/employees/11



