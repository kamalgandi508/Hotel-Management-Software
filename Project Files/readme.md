📌 Project Title

Hotel Management System

📖 Description

This project is a Hotel Management System developed using Spring Boot + MySQL.
It provides features like booking rooms, managing customers, and handling payments.

🚀 Features
User Registration & Login
Room Booking
Customer Management
Payment Handling
Admin Dashboard

🛠️ Technologies Used
Java
Spring Boot
MySQL
HTML, CSS, JavaScript
Postman (API Testing)


⚙️ Prerequisites

Before running the project, install:

Java (JDK 8 or above)
MySQL Server
Maven
IDE (Eclipse / IntelliJ)

▶️ How to Run the Project
1. Clone the Repository
git clone https://github.com/your-username/hotel-management.git
cd hotel-management
2. Configure Database
Open MySQL
Create database:
CREATE DATABASE hotel_db;
Update application.properties:
spring.datasource.url=jdbc:mysql://localhost:3306/hotel_db
spring.datasource.username=root
spring.datasource.password=yourpassword
3. Run the Project

Using Maven:

mvn spring-boot:run

OR run main class:

HotelManagementApplication.java
4. Access the Application
Backend API:
http://localhost:8080
Test APIs using Postman
📂 Project Structure
src/
 ├── controller
 ├── service
 ├── repository
 ├── model
 └── config
 )

👨‍💻Author
Gandi kamal
