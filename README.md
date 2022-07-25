# CS257 Group Project (Hotel Management System)

This is a website designed for internal functioning of a hotel. It can be used for booking purposes by the receptionist. It also provides support system and utility for the guests. From management of housekeepers to restaurant , it provides a wide range of solutions.
##Project Screenshots
### Landing Page
![Screenshot (38)](https://user-images.githubusercontent.com/87379004/180840399-ccd0057c-39fa-4514-a154-21d46faff9a3.png)
### Receptionist-Home Page
![Screenshot (39)](https://user-images.githubusercontent.com/87379004/180840431-c7d07e6d-1947-4148-9e32-ffe61ef61511.png)
### Register Employee
![Screenshot (42)](https://user-images.githubusercontent.com/87379004/180840443-f48f144e-b1cf-4608-befa-7db200ea12cc.png)
### Profile Page
![Screenshot (43)](https://user-images.githubusercontent.com/87379004/180840446-177d84f0-6ba8-46ae-84bd-0064c647e70f.png)
### Contact Other Employees
![Screenshot (44)](https://user-images.githubusercontent.com/87379004/180840449-55118449-f9e4-45d4-a5d7-ed43c9769fd9.png)
### Check For Available Rooms
![Screenshot (45)](https://user-images.githubusercontent.com/87379004/180840451-95c3854c-3b8b-40e8-885d-5bdfa8d91e24.png)


## Requirements
For development you will need Node.js and packages like nodemon, express, express-session, pug , my-sql , express-mysql-session , body-parser.
You will also need my sql workbench installed on your system. You will get instructions at [official Mysql website](https://docs.oracle.com/cd/E19078-01/mysql/mysql-workbench/wb-installing.html)

- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
- #### Installing the required Node.js packages
  Use the package manager [npm](https://docs.npmjs.com/) to install following modules.

```bash
npm install nodemon express express-session pug my-sql express-mysql-session body-parser
```
- #### Creation of Database
  Open file named query.sql present in the root directory and run it in mysql workbench. \
 Default receptionist with id =1 and password= 1234 has been already created , you can use these credentials to login and create other users.
- #### Changing password of Database in server
  In the file named server.js change the password to the password of your Database
## Usage
- Open the root folder in VS code or any other IDE and run the application using the following command
```bash
nodemon ./app.js
```
- Open your browser and go to the address localhost:3000 

