
# Simple CRUD Spring Boot Project

## Download the API Documentation
You can download the API documentation using the link below:

[API Documentation](https://github.com/jebasingh-wesley/java_crud_method_mysql)

## Introduction
This is a sample Spring Boot project for those who are seeking to learn how to create a simple Spring Boot CRUD application. This project implements all the CRUD operations in a straightforward manner, allowing you to understand how to perform CRUD operations in Spring Boot.

[Project Repository](https://github.com/KDVC/api-documents/tree/master/simple-crud-springboot-project)

## Technologies Used
- Spring Boot
- MySQL
- Hibernate

## IDE Used
- IntelliJ IDEA

## API Signatures
The application runs locally on port 8883. You can change the port if needed.

### Endpoints
- `POST /employee/save`
  - This API will save an employee in the employee database (inserts a record into the employee table).

- `GET /employee/getall`
  - This API will return details of all employees as a list.

- `GET /employee/getone/{employeeId}`
  - This API will return details of a specific employee based on the provided employee ID.

- `DELETE /employee/delete/{employeeId}`
  - This API will delete the employee with the provided employee ID (removes the record from the employee table).

- `PUT /employee/update`
  - This API will update the details of an employee (updates the employee table).

## Let's Test the API

### Import Project to IDE
First, clone the project from the GitHub repository and then open the project using IntelliJ:
- `File -> Open -> Select your project`

### Create the Database
Create a database named **employee** in your MySQL Workbench. You can create your own database; it doesn’t have to be named **employee**. If you create a different database, make sure to update the database name in the property file accordingly. Update the database **username** and **password** according to your MySQL configuration.

![Database Configuration](https://github.com/KDVC/images/blob/master/Capture5.PNG)

```diff
- NOTE: 
You only need to create the database; do not create the tables. 
When you run the application, Hibernate will create the tables in the employee database for you.
```

Build and run your project. You can test all the API routes using Postman. Below are screenshots of API calls using Postman.

### POST /employee/save
#### Request
![Save Request](https://github.com/KDVC/images/blob/master/Capture6.PNG)

#### Response
![Save Response](https://github.com/KDVC/images/blob/master/Capture7.PNG)

#### Database
![Database After Save](https://github.com/KDVC/images/blob/master/Capture8.PNG)

### GET /employee/getall
#### Database
![Database Before GetAll](https://github.com/KDVC/images/blob/master/Capture9.PNG)

#### Response
![GetAll Response](https://github.com/KDVC/images/blob/master/10.PNG)

### GET /employee/getone/{employeeId}
#### Database
![Database Before GetOne](https://github.com/KDVC/images/blob/master/Capture9.PNG)

#### Response
![GetOne Response](https://github.com/KDVC/images/blob/master/11.PNG)

### DELETE /employee/delete/{employeeId}
#### Database (Before Delete)
![Database Before Delete](https://github.com/KDVC/images/blob/master/Capture9.PNG)

#### Database (After Delete)
![Database After Delete](https://github.com/KDVC/images/blob/master/12.PNG)

### PUT /employee/update
#### Database (Before Update)
![Database Before Update](https://github.com/KDVC/images/blob/master/12.PNG)

#### Request
![Update Request](https://github.com/KDVC/images/blob/master/13.PNG)

#### Response
![Update Response](https://github.com/KDVC/images/blob/master/14.PNG)

#### Database (After Update)
![Database After Update](https://github.com/KDVC/images/blob/master/15.PNG)

---

Feel free to explore the code, contribute, and raise issues if you encounter any. Happy coding!
