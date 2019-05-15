# my-personal-chef
a nodejs server to fetch a json api  
uses Express / Expressjs framework to get and post operations to spit the data on static hosted pages in temp folder
it performs CRUD operations on database named mypersonalchef some of the features include getting all users , recipes , ingredients,
delete an user by id.
more features will be added soon


for using this you need a node lts version installed and dependencies as per in package.json which are
"dependencies": {
    "body-parser": "^1.19.0",
    "cors": "^2.8.5",
    "express": "^4.16.4",
    "morgan": "^1.9.1",
    "mysql": "^2.17.1",
    "nodemon": "^1.18.11"
  }
  
  you need to create database mypersonalchef in mysql tested on mysql 5.7
  can be done by running create and insert files in database folder



finally run as nodemon chefserve.js in cli in root folder of the file

check for localhost:3333/
