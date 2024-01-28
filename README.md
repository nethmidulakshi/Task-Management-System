# Task-Management-System 

## Trying to make it like asana Task manager
1. It has future like login sign up 
2. Assign task 
3. List all task those are assigned to you 
4. admin can see all task 
5. like or dislike ( backend is done ) from UI I need to be done 
### Under construction 

## How to run

Clone it
Go to todo branch 
Then go to root directory 
and then `npm i`

then npm start

demo vedio : 

Happy coding !!!



---for backend---
### How to run ( Project set up )

* ``` npm i ```
* ``` sudo npm install -g nodemon ``` if you have already installed no need to install
##### Now set up your Mongo db 
    * install mongo community in you machine or there are so many blogs or video in internet where you can find installation process. ( you can also take help from chat GPT)
    * Follow the below steps 
        * Type ```monog```
        * ```db.createUser(
       {
         user: "mongoadmin", // main admin user it could be anything
         pwd: "mongoadmin", // password against this could be anything 
         roles: [ { role: "userAdminAnyDatabase", db: "admin" } ]
       }
     )```
    * Now add user , password and roles config.json 

* ``` NODE_ENV=development nodemon app.js ```



