# MEAN CRUD

`npm i express`

`npm i morgan`

`npm i nodemon -D`

`"scripts": { "dev": "nodemon ./src/index.js",`

# DIR --> Routes with API

`app.use(require Routes)`

# Controllers

##### getEmployees

##### createEmployee

##### getEmployee

##### editEmployee

##### deleteEmployee

# Send object to Server

const object and use

# module.exports = employeeCtrl;

###### Use the string "/api/employees" for reduce code in requirement of routes

app.use("/api/employees", require("./routes/employee.routes"));
