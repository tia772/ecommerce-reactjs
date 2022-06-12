# ecommerce-reactjs
IMPORTANT NOTE -
This project does not have a mongoDB connection setup. Setup the connection based on the environments below.
local development: create a config file (make sure to name it .env) .
production: Since the config file is not pushed when you deploy your app, you must specifiy your db. Make sure you name the environement variable "MONGO_URL"


Since this project will hold both the client application and the server application there will be node modules in two different places. First run npm install from the root. After this you will run npm run-script install-all from the root. From now on run this command anytime you want to install all modules again. This is a script we have defined in package.json .

In the project directory, you can run yarn start
