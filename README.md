Project Components:

AccountStatement Spring Boot Microservice: This microservice handles the RESTful API for account statements and utilizes a gradle build system using H2 database.
AccountStatement Frontend Service: This service is developed using AngularJS 1.8.2 and runs on a separate HTTP server port (4200). The Spring Boot service listens on the default port (8080).
Additional Information:

An activity diagram for the project is also included in the attached zip file.


http port
http-server -p 4200 -c-1 .

URL
http://localhost:4200/public/#
