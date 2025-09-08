Movie Ticket Management System

This project is a simple Movie Ticket Management System built to demonstrate CRUD operations, REST APIs, and database integration. It allows users to manage movies, show timings, and ticket bookings.

📌 Features

Add, update, delete, and view movies.

Manage ticket bookings and cancellations.

Store and retrieve data from a relational database.

RESTful API integration for client-server communication.

Simple and easy-to-use structure.

🛠️ Technologies Used

Backend: Spring Boot, Spring Data JPA, REST API

Database: MySQL

Testing/Interface: Postman

Tools: Maven, IntelliJ/Eclipse

⚡ CRUD Operations

Create – Add movies, shows, and tickets.

Read – Fetch all movies, booked tickets, and show details.

Update – Modify movie details or reschedule a show.

Delete – Cancel a booking or remove a movie.

📂 Project Structure

Controller – Handles incoming REST API requests.

Service – Business logic of the application.

Repository – Data access layer using Spring Data JPA.

Entity – Defines database tables and relationships.

▶️ How to Run

Clone this repository:

git clone https://github.com/your-username/movie-ticket-management.git


Configure MySQL Database in application.properties.

spring.datasource.url=jdbc:mysql://localhost:3306/moviedb
spring.datasource.username=root
spring.datasource.password=yourpassword


Run the project using:

mvn spring-boot:run


Test APIs using Postman (example endpoints):

POST /movies → Add new movie

GET /movies → Get all movies

PUT /movies/{id} → Update movie details

DELETE /movies/{id} → Delete a movie

🎯 Learning Outcomes

Understood Spring Boot and REST API development.

Implemented CRUD operations using JPA.

Connected application with MySQL database.

Tested endpoints using Postman.

✨ This project demonstrates backend development skills using Spring Boot + JPA + MySQL.
