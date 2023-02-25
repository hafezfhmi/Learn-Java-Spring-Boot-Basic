# Learn: Java Spring Boot Basic

## Purpose:
The purpose of this repository is to acquire a fundamental understanding of Java Spring Boot. Although I have primarily utilized Node.js and Express as a framework to develop REST APIs, I am eager to investigate how other languages and their frameworks implement backend applications. So why did I select Java and Spring Boot? In the past, I had studied Java for my university coursework and wanted to learn an enterprise language that is commonly used to develop the backend of an application. 

## Tutorial link: 
https://youtu.be/9SGDpanrc8U

## Starting the app: 
1. Run docker containers for postgres database: docker-compose up
2. Run the app (must be in target folder): java -jar .\demo-0.0.1-SNAPSHOT.jar
3. Visit http://localhost:8080/api/v1/student

## Available REST API endpoint:
- GET http://localhost:8080/api/v1/student (List all students)
- POST http://localhost:8080/api/v1/student (Create a student, {name, email, dob})
- DELETE http://localhost:8080/api/v1/student/:studentId (Delete a student)
- PUT http://localhost:8080/api/v1/student/:studentId?name&email (Update a student's name or email)
