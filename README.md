# Simple-taxi-service
This simple application is for storing cars, drivers and manufacturers models with relations between them.
# Features
Registration and authentication for drivers (log in, log out).<br>
CRUD operations for three models (driver, car, manufacturer).<br>
Possibility to add drivers to car.<br>
Possibility to display all drivers for car and all cars for authenticated driver. 
# Structure
Database with relations between tables one-to-one, one-to-many, many-to-many.<br>
N-tier structure (DAO, Service, Controller).
# Technologies
Java<br>
Java (javax.servlet)<br>
MySQL<br>
JDBC<br>
Tomcat<br>
Maven<br>
# How to launch the project
Fork and clone this project from repository to your laptop.<br>
Set up MySQL and create necessary tables by using file resources/init_db.sql.<br>
Edit file taxi/util/ConnectionUtil with your field (USERNAME, PASSWORD), and you can change URL if it is needed.<br>
Install and add Tomcat 9.0.65 to configuration.<br>
Run project. 