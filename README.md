﻿# TicketCine

### Project description:

This project is the back-end part of a simple movie service for ticket reservation, with the possibility of user registration and authentication, as well as a set of CRUD operations and REST principals.

I made this project during an online Java course at Mate Academy. The goal of the project is to consolidate the acquired knowledge in Java Hibernate and Spring.

### Features:
Functionality of the service is based on two roles – ADMIN & USER

| ADMIN  features: | USER  features: |
| ---              |-----------------|
| login | register or login         |
| creat or find movie | find movie or cinema-hall |
|creat or find cinema-hall| find available movie-session |
| create, update or delete movie-session | add tickets to shopping cart |
|find registered user | complete order |

### Project Overview:

After launching the program, you need to log in or register.
Depending on the role, the actions described above in the "features" section will be available, so you can send your requests to the corresponding endpoints.
Output and input data to endpoints are provided in json format. The input data must meet certain requirements, otherwise the user will receive an error message with a description of the problem.

### Technologies used:
- Java 17
- Java Hibernate 5.6.14
- Javax Annotation API 1.3.2
- Javax Servlet API 4.0.1
- Maven 4.0.0
- Spring Framework 5.3.20
- Spring Security 5.6.10
- SQL
- Tomcat 9.0.50

### Steps to run the program on your computer:
1. Make sure that following programs are installed:
- Java 17 or higher is required;
- IDE to run the App. I used IntelliJ IDEA Ultimate;
- Maven 4.0.0;
- Tomcat 9.0.50;
- SQL database. For example mySQL;
2. Make fork and open the App in your IDE;
3. Create new schema in your DB.
4. Enter all necessary information in the resources/db.properties;
5. Configure webdriver Tomcat;
6. Run the App in your IDE (you can find an admin's data or add your own in util/DataInitializer);
