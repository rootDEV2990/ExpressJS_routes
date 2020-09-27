## Express JS and mySQL 

Use this as a resource as i document my adventure with restAPI using JS. I will be using mySQL so your milage may vary. 

## What you need
node
npm
express
nodemon
mysql

## Install 

1. make a direcotry that will hold your project. in terminal navicate to path of choice and interminal run 
    mkdir appname

2. change into that directory in terminal type  
    cd appname/

3. once in folder use npm to initialize project in terminal run the following commands filling in the information like name and so fourth.
    npm init

4. add express and mysql
    npm install --save mysql express

5. install nodemon to run node server   
    npm install -g nodemon

6. in package.json change name of main file target to 
    "main": "app.js",

7. create a app.js file in project folder interminal you can use touch if needed
    touch app.js

8. construct live server in app.js add this code to reference mysql and express
    const express = require('express');
    const mysql = require('mysql');

    const app = express();

    app.listen('3000', () => {
        console.log('Server started on port 3000');
    });

9. in terminal run nodemon and in your browser got o localhost:3000 and you should be running.




