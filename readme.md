# Leave Management System

This is a leave management system web application that allows students, instructors, and admins to manage leaves, leave applications and attendance. The system is built using Node.js and Express.js for the server side, and React with Typescript on the frontend.<br/>
This is the website for the report of the project: [report](https://lm-report.my.canva.site/)<br/>
Project proposal: [proposal](https://heet434.github.io/dbms_project/)<br/>
Link for A short description video of the project: [project description](https://iitgoffice-my.sharepoint.com/:v:/g/personal/p_niraj_iitg_ac_in/EShn4ozUFsxLkrNSUk-iP28BYZtHApAzStcgDXOY4a7Nhw?e=s8lYb0&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)<br/>
A short demo video of the project: [demo](https://iitgoffice-my.sharepoint.com/:v:/g/personal/p_niraj_iitg_ac_in/Ec6g084ckV1Mvqn-0CFB05QBSEKQaZ1zWRDmDCbom1rZyQ?e=nGVHSp&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)<br/>

I have deployed the backend using Railway, and the frontend using gh-pages in another repository [lm-deploy](https://github.com/heet434/lm-deploy). <br/>
Here's the link to the deployed website: [Leave Managmenet](https://heet434.github.io/lm-deploy/) <br/>Enter user name: 0 and password: 12345678 to login as a sample student.

## Frontend

Here are some snapshots of the UI of the frontend part of the project: <br/>
<img width="600" alt="Screenshot 2024-04-20 at 6 19 24 PM" src="https://github.com/heet434/leave_management/assets/118350153/049d3625-6312-4a5c-ad2f-470a57813885">
<img width="600" alt="Screenshot 2024-04-20 at 6 19 08 PM" src="https://github.com/heet434/leave_management/assets/118350153/dd5275d4-bb68-44eb-b36f-1d147bc474e1">
<img width="600" alt="Screenshot 2024-04-20 at 9 56 15 PM" src="https://github.com/heet434/leave_management/assets/118350153/13f00992-8e69-4f64-9d18-e073738295f6">
<img width="600" alt="Screenshot 2024-04-20 at 9 07 45 PM" src="https://github.com/heet434/leave_management/assets/118350153/3a7413fd-ef1a-47ef-98d7-577cc9f16fd4">
<img width="600" alt="Screenshot 2024-04-20 at 9 18 26 PM" src="https://github.com/heet434/leave_management/assets/118350153/84e5ff76-b54b-4c8b-af44-cc42ae495c7e">


I used React with Typescript for building a robust frontend for the application. The user can login as either a student, instructor, or admin. The user can view their leaves, attendance, and apply for leaves. If the user is authorized to, he/she can reject/accept leaves. The user can also view the attendance of the class. I used Axios for making API requests to the server. The frontend is built using React Router for navigation. Also, I used Material-UI and AntDesign for building the UI components.
### Setup
1. Clone the repository.<br/>
2. Once the server is running, run ```cd client``` <br/>
3. ```npm i react-scripts``` <br/>
4. ```npm start``` <br/>

## Backend

### The Relational Schema for the backend is as follows: <br/>
<img width="828" alt="erd" src="https://github.com/heet434/leave_management/assets/118350153/d97175c0-0357-4ec9-934b-9e39b108a223">

The server side code is built using Node.js and Express.js. The server side uses a mySQL database for the backend framework. The database of the project is built on mySQL on XAMPP server. The relevant exported database can be found in the sql file. The backend for this project was quite simple, so I created it in a single server file and initially created all the db tables in phpMyAdmin. I plan to grow this project and add more features in the future, so I will be using Sequelize for the database and will be creating a more structured backend.
### Setup
1. Clone the repository.<br/>
2. Install the dependencies listed in requirements.txt in backend folder.<br/>
3. In mysql, import the database from leave_management.sql file. This will create the structure of the database. Populate admin and auth data.<br/>
4. Go to the backend folder ```cd server```<br/>
5. Run ```npm start```<br/>
