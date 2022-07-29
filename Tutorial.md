database setup tutorial 

Postgres :- 

Add below properties :-

spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.PostgreSQLDialect
spring.datasource.url = jdbc:postgresql://localhost:5432/database?currentSchema=schema
spring.datasource.username = username
spring.datasource.password = password
spring.jpa.hibernate.ddl-auto = none