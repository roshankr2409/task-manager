# Employee Task Management System
This project is a mini SaaS-style Employee Task Management System built as part of a Full-Stack Developer Intern assignment.
The system allows administrators to create and assign tasks to employees, and employees can view and update their assigned tasks.

## Tech Stack Used :-
Frontend
* HTML
* Tailwind CSS
* JavaScript (Fetch API)

Backend
* Node.js
* Express.js
* JWT Authentication
* bcrypt password hashing

Database
* MySQL

##Features Implemented :-
Authentication
* User login with JWT
* Role-based access (Admin / Employee)
* Secure password hashing

## Admin Capabilities :-
* Create new tasks
* Assign tasks to employees
* View all tasks
* Logout functionality

## Employee Capabilities :-
* View assigned tasks
* Update task status
* Logout functionality

## Task Fields :-
* Title
* Description
* Priority
* Deadline
* Status

 ## Database Tables :-
* Users
* Tasks

## How to Run the Project :-
1️.Start Backend
cd server
npm install
npx nodemon app.js
Server runs on: http://localhost:5000

2️.Run Frontend
Open:client/login.html
Using Live Server or browser.

## Test Credentials :-
Admin
email: kumarroshan4200@gmail.com
password:Roshan@123

Employee
email: surajkrbksc2409@gmail.com
password: Suraj@123

email: aditya@gmail.com
password: Aditya@123

