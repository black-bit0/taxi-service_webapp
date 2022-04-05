# Taxi-service
This a simple web application
must have functionality, adding and retrieving data from the database, for further processing,
create modification and deletion of data from the database, display data and functionality in a web browser, and authentication functionality,
implement 3-level Dao architecture, services, controllers.

> ## Dao-layer
At this level it is necessary to create interfaces and to implement them in slats, for work with a database,
create methods for working with each database table, for reading, adding modifications and deleting information

> ## Service-layer
At this level it is necessary to create functionality in which methods of creation, modification and deletion of data from a DB will be caused.

> ## Layer of controllers
At this level, we need to link our functionality to the relevant jsp pages, here we receive data from the user and provide a response.


## Filter and Connection

Use the filter to prevent an unauthenticated user from accessing the functionality and redirect it to the Login page.

Using the connection class to access the database

## Technologies
* Java 11
* Maven 4.0.0
* MavenCheckstyle 3.1.1
* Tomcat 9.0.50
* MySQL 8.0.22
* Servlet 4.0.1
* JSTL 1.2
* JDBC

## How to start
1. Configure Apache Tomcat for your IDE
2. Install MySQL and MySQL Workbench
3. Use resources/init_db.sql for creating a Schema and tables
4. Configure ConnectionUtil.java with your URL, USERNAME, PASSWORD, JDBC_DRIVER
5. Configure the tomcat library path in the startup settings

## All functional
* create new Driver
* create new Car
* create new Manufacturer
* add driver to car
* display all Drivers
* display all Cars
* display all Manufacturers
* all cars by driver
