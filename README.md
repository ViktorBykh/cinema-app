# <h1 align="center"> <img src="https://em-content.zobj.net/thumbs/120/apple/354/movie-camera_1f3a5.png" width="35"/> Cinema-app <img src="https://em-content.zobj.net/thumbs/120/apple/354/movie-camera_1f3a5.png" width="35"/> </h1>
#### <h4 align="center"> [Project description](https://github.com/ViktorBykh/cinema-app#-project-description) • [Features](https://github.com/ViktorBykh/cinema-app#-project-structure) • [Project Structure](https://github.com/ViktorBykh/cinema-app#-project-structure) • [Hibernate UML diagram](https://github.com/ViktorBykh/cinema-app#-hibernate-uml-diagram) • [Technologies used](https://github.com/ViktorBykh/cinema-app#-technologies-used) • [Instructions for launching the project](https://github.com/ViktorBykh/cinema-app#-instructions-for-launching-the-project)

## <img src="https://em-content.zobj.net/thumbs/120/apple/354/light-bulb_1f4a1.png" width="25"/> **Project description:**
`A web application that offers the functionality of a cinema service for authentication, registration, and CRUD operations`

### <img src="https://em-content.zobj.net/thumbs/120/apple/354/direct-hit_1f3af.png" width="20"/> Features:
* register or authenticate as a user
* create and find cinema halls
* create and find movies
* create, update, delete and find available movie sessions
* creat and find shopping carts
* add tickets to shopping carts
* complete and find an orders
* find an information about user

### <img src="https://em-content.zobj.net/thumbs/120/apple/354/gear_2699-fe0f.png" width="20"/> Project Structure:
* config: Contains configuration files for Spring
* controller: Contains REST controllers and an exception handler
* dao: Contains data access objects for database operations, implemented using Hibernate
* dto: Contains data transfer objects, which are used to transfer data between layers of the application
* exception: Contains custom exception classes
* lib: Contains custom validation annotations and classes
* model: Contains domain models (entities), implemented using Hibernate annotations
* security: Contains a class related to security and authentication, implemented using Spring Security
* service: Contains business logic, mappers and services, implemented using Spring
* util: Contains a utility class
* resources: Contains a database configuration file

### <img src="https://em-content.zobj.net/thumbs/120/apple/354/card-file-box_1f5c3-fe0f.png" width="20"/> Hibernate UML diagram:
![](https://github.com/ViktorBykh/cinema-app/blob/main/img/img.png)

### <img src="https://em-content.zobj.net/thumbs/120/apple/354/clamp_1f5dc-fe0f.png" width="20"/> Technologies used:
* <img src="https://image.emojipng.com/677/13219677.jpg" width="30"/> Java 17
* <img src="https://avatars.githubusercontent.com/u/348262?s=280&v=4" width="30"/> Hibernate 5.6.14
* <img src="https://media.trustradius.com/product-logos/9B/8G/IMJEF6VWC74S.PNG" width="30"/> Spring Core 5.3.20
* <img src="https://media.trustradius.com/product-logos/9B/8G/IMJEF6VWC74S.PNG" width="30"/> Spring MVC 5.3.20
* <img src="https://media.trustradius.com/product-logos/9B/8G/IMJEF6VWC74S.PNG" width="30"/> Spring Security 5.6.10
* <img src="https://cdn.fs.teachablecdn.com/L2rtxPaRxa4am1VtNegg" width="30"/> Maven 3.1.1
* <img src="https://w7.pngwing.com/pngs/464/18/png-transparent-mysql-database-innodb-postgresql-column-marine-mammal-electric-blue-postgresql-thumbnail.png" width="30"/> MySQL 8.0.22
* <img src="https://img.icons8.com/color/100000/000000/tomcat.png" width="30"/> Tomcat 9.0.50

### <img src="https://em-content.zobj.net/thumbs/120/apple/354/nut-and-bolt_1f529.png" width="20"/> Instructions for launching the project:
* Make sure you have Java 17, Maven 3.1.1, MySQL 8.0.22 installed on your system
* Fork the project from the [repository](https://github.com/ViktorBykh/cinema-app)
* To clone the project, click on the "Code" button and select either the HTTPS or SSH URL
* Configure [Apache Tomcat](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/) version: 9.0.50 C:\Users\bykhv\IdeaProjects\cinema-app\src\main\resources\db.properties
* To set the necessary parameters, edit the [db.properties](https://github.com/ViktorBykh/cinema-app/tree/main/src/main/resources/db.properties) file:
  * [x] db.driver=YOUR_DRIVER 
  * [x] db.url=YOUR_DATABASE_URL 
  * [x] db.user=YOUR_USERNAME
  * [x] db.password=YOUR_PASSWORD
* Run the project
