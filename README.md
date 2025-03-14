# 🛍️ ShopSphere - A Scalable E-Commerce Backend  

**ShopSphere** is a powerful and scalable **backend-only** e-commerce platform, designed to provide a seamless and efficient foundation for online shopping applications. Built with **Spring Boot** and **MySQL**, this project delivers a well-structured **REST API** that ensures smooth and secure transactions while maintaining flexibility for future enhancements.  

## ✨ Key Features  

🚀 **Backend-Focused Architecture** – A purely backend solution that prioritizes scalability, security, and efficiency.  
🛠 **Built with Spring Boot & MySQL** – Leverages Spring Boot's robust framework and MySQL's reliable database management for handling complex e-commerce operations.  
📦 **Product Category Management** – Allows users to browse, filter, and manage product categories efficiently.  
🛒 **Cart Functionality** – Supports adding, updating, and removing items from the shopping cart with ease.  
📦 **Order Management** – Handles order creation, tracking, and processing for a hassle-free shopping experience.  
🏡 **Address Handling** – Manages shipping and billing details to ensure accurate and timely deliveries.  

## 🔧 Setup Instructions  

### 1️⃣ Download Dependencies  
Before running the project, you need to download the necessary dependencies from **Spring Initializr** or ensure that your development environment includes:  
- **Spring Boot**  
- **Spring Web**  
- **Spring Data JPA**  
- **Spring Security**  
- **MySQL Driver**  
- **JWT Authentication (if applicable)**  

### 2️⃣ Configure `application.properties`  
To set up your database and other configurations, add the following properties in your `application.properties` file:  

```properties
# Application Name
spring.application.name=sb-ecom

# MySQL Database Configuration
spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
spring.datasource.username=your_username
spring.datasource.password=your_password

# JPA & Hibernate Configuration
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQLDialect

# JWT Configuration
spring.app.jwtSecret=your_secret_key
spring.app.jwtExpirationMs=your_expiration_time
spring.ecom.app.jwtCookieName=your_cookie_name

# Logging Configuration
logging.level.org.springframework=DEBUG
logging.level.org.hibernate.SQL=DEBUG
logging.level.org.springframework.security=DEBUG
logging.level.com.ecommerce.project=DEBUG
```

🔹 **Replace** `your_database_name`, `your_username`, `your_password`, values with your actual configurations.  

With **ShopSphere**, developers get a solid backend foundation to build their e-commerce platform, ensuring a smooth, secure, and scalable shopping experience. 🚀  
