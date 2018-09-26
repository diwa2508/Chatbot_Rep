Web sample with JSW Token 
https://scotch.io/tutorials/authenticate-a-node-js-api-with-json-web-tokens


Folder Structure:

- app/
----- models/
---------- user.js
- config.js
- package.json
- server.js

$ npm install express body-parser morgan mongoose jsonwebtoken --save
--save modifier will also save these packages to our package.json

express is the popular Node framework
mongoose is how we interact with our MongoDB database
morgan will log requests to the console so we can see what is happening
body-parser will let us get parameters from our POST requests
jsonwebtoken is how we create and verify our JSON Web Tokens

Tip: Use nodemon to have your server restart on file changes. Install nodemon using npm install -g nodemon.

MongoDB
Acc domain : local
Acc name : shanavas
Acc password : 12345Welcome

Data_Directory : E:\Chatbot_Dailogflow\MongoDB\data\db
Log_Directory : E:\Chatbot_Dailogflow\MongoDB\data\log
Running on port :  port 27017

Mongo exe : C:\Program Files\MongoDB\Server\4.0\bin\mongo.exe

Use mongo.exe to create DB
Create DB : use $DB_Name

