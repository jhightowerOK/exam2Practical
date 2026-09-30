## CSCE 41333: Exam 2: Practice

### Instructions

Create a **Single Page Application(SPA)** using *HTML/JavaScript/BootStrap CSS* that interface with NodeJS/Express/MySQL2 Web API.  Your main page, **index.html** and *all of your JavaScript and CSS files* should be in the **public** directory.  Your application will provide a **User Management page** that calls the Web API to **display the list of users*, and a **form that allows you to add a new user** using the Web API.  Test your application in the browser to ensure it works correctly.


### REST API Endpoints

| HTTP Method | Endpoint | Description | Payload Body (JSON) |
| ----------- | -------- | ----------- | ------------------- |
| GET | /api/users | **R**etrieve all users | None |
| POST | /api/users | **C**reate new user | "{ ""username"", ""lastname"", ""firstname"", ""passwd"", ""email"", ""urole"" }" | 

#### Create MySQL Database
```
sudo mysql < exam1Practice.sql
```

## CSCE 41333: Web API - CRUD Example (NodeJS/Express/MySQL2)

Create MySQL Database
```
sudo mysql < webapicrud.sql
```
### REST API Endpoints

| HTTP Method | Endpoint | Description | Payload Body (JSON) |
| ----------- | -------- | ----------- | ------------------- |
| GET | /api/users | **R**etrieve all users | None |
| GET | /api/users/:id | **R**etrieve single user | None |
| POST | /api/users | **C**reate user | "{ ""username"", ""lastname"", ""firstname"", ""passwd"", ""email"", ""urole"" }" |
| PUT | /api/users/:id | **U**pdate user | "{ ""username"", ""lastname"", ""firstname"", ""passwd"", ""email"", ""urole"" }" |
| DELETE | /api/users/:id | **D**elete user | None |
