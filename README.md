Add database Configuration like creare crud database.
#server
server.port=8080

#Datasource of mysql
spring.datasource.url=jdbc:mysql://localhost:3306/crud
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.username=root
spring.datasource.password=admin

#hibernate Configuration
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQLDialect
