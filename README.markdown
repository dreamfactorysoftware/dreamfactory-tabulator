# DreamFactory and Tabulator

## Installation

1. Import the [MySQL Employees](https://dev.mysql.com/doc/employee/en/) sample database into a MySQL database 
2. Generate an API for this database

![alt text](./createservice.png)

3. Create a [role and API key](http://guide.dreamfactory.com/docs/chapter03.html#creating-a-role) capable of talking to this database.

![alt text](./createrole.png)
![alt text](./createapikey.png)

4. Copy config.js.example to config.js and update the apiKey and url with the API Key we just generated. The URL will look like http(s)://<YOUR_URL>/api/v2/<SERVICE_NAME>

5. Install the [http-server NPM package](https://www.npmjs.com/package/http-server) `npm install http-server -g`
  - http-server is a simple, zero-configuration command-line http server for testing, local development, and learning.

6. Run http-server from inside the project root directory and load the specified URL to the browser.
  - Port defaults to 8080

## Troubleshooting

If any issues arise creating the API, Key, or Role please reference our new and [improved guide](http://guide.dreamfactory.com/docs/#about-this-guide). 
