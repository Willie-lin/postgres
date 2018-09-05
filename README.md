# postgres
Building RESTful APIs with Spring Boot, PostgreSQL, JPA and Hibernate

Steps to Setup
1. Clone the repository

git clone https://github.com/callicoder/spring-boot-postgresql-jpa-hibernate-rest-api-demo.git
2. Configure PostgreSQL

First, create a database named postgres_demo. Then, open src/main/resources/application.properties file and change the spring datasource username and password as per your PostgreSQL installation.

3. Run the app

Type the following command from the root directory of the project to run it -

mvn spring-boot:run
Alternatively, you can package the application in the form of a JAR file and then run it like so -

mvn clean package
java -jar target/postgres-0.0.1-SNAPSHOT.jar
