# <h1>Taxi-Service</h1>

![](taxi.gif)

This is a prototype of taxi service.

This project was created with the aim to show my skills in Java,
OOP and SOLID principles, JDBC, Web.

The project is written using N-tier architecture,
used Custom Injector to achieve loose coupling.

As a user you can register yourself as a driver.
After registration, you will be able to log in (using login and password) and see information 
about another drivers, cars, drivers cars, assign driver to a car. 

After logging, driver can do next activites:
1. Add new, delete, update cars and manufacturers
2. Register new drivers
3. Display all cars, drivers and manufacturers of our service
4. Display your cars as a driver
5. Link existing cars to your driver

# <h2>Project structure:</h2>
The structure of this taxi-service consists of 3 levels:
1. Data access layer (DAO)
2. Application layer (service)
3. Presentation layer (controllers)

# <h2>Technologies</h2>
1. Apache Tomcat 9.0.50 (to run app locally)
2. MySQL
3. JDBC
4. Javax servlet API
5. JSP
6. JSTL
7. HTML, CSS
8. Maven

# <h2>How to start the application</h2>
You have 2 options run the app:
* install MySQL
* Install and configure Local Tomcat 9.0.50 Server
(set "/" in Deployment - taxi-service:war exploded).
* fork this project and clone it
* initialize your database using init_db.sql file located in recources
* add your info to ConnectionUtil class
(put your DBUrl, username, password and JDBC Driver 
(left my data, find something similar, don't hack me please))
in util package to be able to connect to your database
* run this project using Tomcat's local server

Or you can just check it out following this link
https://mytaxi.herokuapp.com
