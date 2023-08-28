# Staff Scheduling System

## Brief: 
Write a backend application for the staff scheduling system.
Users must be able to create an account and log in. Implement 2 roles with different
permission levels:

#### Staff User:
* Can view his/her schedule for any period of time (up to 1 year)
* Can see his/her coworker schedules

#### Admin:
* Can edit/delete all users,
* Can create/edit/delete schedule for users
* Can order users list by accumulated work hours per arbitrary period (up to 1 year)

### Schedule should have:
* Work date
* User
* Shift length in hours

### Deliverables:
* Create relevant REST endpoints that can be accessed and interacted via Postman or
other similar software.
* Add Relevant unit tests.
* Create a documentation page using Open API specifications.
* Dockerize application and add README file describing how to run the project.

## Technologies used:
* Java 17
* Maven
* Docker

## Local development setup
* Install JDK 17
* Install Maven
* Download and install Docker Desktop / setup docker.
* Run the maven: 'mvn clean install'
* Run the Dockerfile 
* Find the api documentation on 'http://localhost:8080/api-docs'
* Swagger can be accessed via 'http://localhost:8080/swagger-ui/index.html'
