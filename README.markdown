# DreamFactory and Tabulator

## Installation

1. Import the MySQL Employees sample database into a MySQL database (https://dev.mysql.com/doc/employee/en/)

2. Generate an API for this database

![alt text](./createservice.png)

3. Create a role and API key capable of talking to this database.

![alt text](./createrole.png)
![alt text](./createapikey.png)

4. Copy config.js.example to config.js and update the apiKey and url
5. Install the [http-server NPM package](https://www.npmjs.com/package/http-server)
6. Run http-server from inside the project directory and load the specified URL to the browser.
