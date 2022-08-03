# Authentication Server using Express and NodeJS

Authentication server provides a network service that applications use to authenticate the credentials, here, I've considered user-email and password. Now, when a client submits a valid set of credentials, it receives a cryptographic ticket that it can subsequently use to access various services. Otherwise, the access will be denied.

This allows an organization to keep their networks secure by permitting only authenticated users to gain access to their protected resources.

### Run this project:
In order to be able to use this project, we've to install a few modules.

Firsty, Nodemon will help us develop node.js applications by automatically restarting the node application when file changes in the directory are detected. 
- `npm install -g --force nodemon`

Express is a web application framework that provides broad features for building web applications
- `npm install express`

Ejs is templating language that lets us generate HTML with plain javascript
- `npm install ejs`
   
Bcrypt is used to encrypt the password to provide more security to the user in case the data is leaked
- `npm install bcrypt`

##### Now, we'll install the packages required for login page: 
- `npm install passport`

- `npm install passport-local`

express-flash displays the error messages, in case an user enters incorrect credentials
- `npm install express-flash`
- `npm install express-session`

.env file
- `npm install dotenv`


#### Now, we can start the server by using `nodemon [filename]`
`nodemon server.js`
