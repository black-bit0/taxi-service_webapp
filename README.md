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
