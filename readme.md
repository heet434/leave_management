# Leave Management System

This is a leave management system web application that allows students, instructors, and admins to manage leaves, leave applications and attendance. The system is built using Node.js and Express.js for the server side, and React with Typescript on the frontend.<br/>
This is the website for the report of the project: [report](https://lm-report.my.canva.site/)<br/>
Project proposal: [proposal](https://heet434.github.io/dbms_project/)<br/>
Link for A short description video of the project: [project description](https://iitgoffice-my.sharepoint.com/:v:/g/personal/p_niraj_iitg_ac_in/EShn4ozUFsxLkrNSUk-iP28BYZtHApAzStcgDXOY4a7Nhw?e=s8lYb0&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)<br/>
A short demo video of the project: [demo](https://iitgoffice-my.sharepoint.com/:v:/g/personal/p_niraj_iitg_ac_in/Ec6g084ckV1Mvqn-0CFB05QBSEKQaZ1zWRDmDCbom1rZyQ?e=nGVHSp&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)<br/>

## Frontend

I used React with Typescript for building a robust frontend for the application. The user can login as either a student, instructor, or admin. The user can view their leaves, attendance, and apply for leaves. If the user is authorized to, he/she can reject/accept leaves. The user can also view the attendance of the class. I used Axios for making API requests to the server. The frontend is built using React Router for navigation. Also, I used Material-UI and AntDesign for building the UI components.
### Setup
1. Clone the repository.<br/>
2. Once the server is running, run ```cd client``` <br/>
3. ```npm i react-scripts``` <br/>
4. ```npm start``` <br/>

## Backend

The server side code is built using Node.js and Express.js. The server side uses a mySQL database for the backend framework. The database of the project is built on mySQL on XAMPP server. The relevant exported database can be found in the sql file. The backend for this project was quite simple, so I created it in a single server file and initially created all the db tables in phpMyAdmin. I plan to grow this project and add more features in the future, so I will be using Sequelize for the database and will be creating a more structured backend.
### Setup
1. Clone the repository.<br/>
2. Install the dependencies listed in requirements.txt in backend folder.<br/>
3. In mysql, import the database from leave_management.sql file. This will create the structure of the database. Populate admin and auth data.<br/>
4. Go to the backend folder ```cd server```<br/>
5. Run ```npm start```<br/>
