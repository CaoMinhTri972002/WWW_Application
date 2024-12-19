spring.application.name=onCK

spring.datasource.driver-class-name=org.mariadb.jdbc.Driver
spring.datasource.url=jdbc:mariadb://localhost:3306/cuoiky?useSSL=false&serverTimezone=UTC
spring.datasource.username=root
spring.datasource.password=sapassword

# Cấu hình JPA
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true
# Sử dụng MariaDB55Dialect thay vì MariaDB103Dialect
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MariaDBDialect

spring.jpa.properties.hibernate.transaction.jta.platform=org.hibernate.engine.transaction.jta.platform.internal.NoJtaPlatform
spring.jpa.properties.hibernate.packagesToScan=iuh.fit.se.entities

# Thymleaf (nếu cần thiết)
#spring.thymeleaf.cache=false
#spring.thymeleaf.prefix=classpath:/templates/
#spring.thymeleaf.suffix=.html

