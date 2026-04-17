Employee Management API

This project is a simple RESTful API built using Node.js, Express, and MongoDB. It allows basic CRUD (Create, Read, Update, Delete) operations for managing employee records.

 Features

* Add new employees
* View all employees
* Get employee details by ID
* Update employee information
* Delete employee records

Tech Stack

* Node.js
* Express.js
* MongoDB
* Mongoose
* CORS

 Project Structure

project-folder/
│── index.js
│── package.json

 Installation & Setup

1. Clone the repository:


git clone https://github.com/your-username/employee-management-api.git


2. Navigate to project folder:


cd employee-management-api


3. Install dependencies:


npm install


4. Start MongoDB locally

5. Run the server:


node index.js


API Endpoints

 Create Employee

POST /api/employees

 Get All Employees

GET /api/employees

 Get Employee by ID

GET /api/employees/:id

 Update Employee

PUT /api/employees/:id

 Delete Employee

DELETE /api/employees/:id


 Example JSON
{
  "name": "Rahul",
  "department": "IT",
  "salary": 50000
}

Notes

* Ensure MongoDB is running on your system
* Default database: employee_management
* Port used: 5000

 Author

Jasmine
MCA Student, Chandigarh University

