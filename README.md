The main objective of this tutorial is to understand how Node.js, Express and MongoDB work together to deliver web applications where front-end WebPages interact with server and then server connects with database to perform CRUD operations. 

Inventory Management system through CRUD

1.Create Database with Mongo Compass
  1.1. Run Mongo.exe on your desktop
  1.2.Open Mongo Compass Application
  1.3.Click on Connect(U’ll be directed to a UI frontend of your existing records in your database)
  1.4.Click on Create Database and give a Database name and a Collection Name and click on the “Create Database” icon
  1.5.You see that a new database is added to your existing records and click on that and click on “collection name”
And import your .csv file which has been created on excel.
 
2.Create a new Folder with two Subfolders public and view 
 2.1. add.ejs, delete.ejs, homepage.ejs, update.ejs to be kept in “views”
 2.2. styles.css to be kept in “public”
 2.3.the .csv file and server.js can be kept in the root folder separately 

3.Open the Root Folder on VSCode and install the following packages
 3.1. npm init(continue to enter till you reach “yes”), npm i express,  npm i ejs, npm i mongodb
 3.2. changes to be made in the server.js code 
    Change wherever “collections” is present to YOUR DATABASE’s name
    Change wherever “shoes” is present to YOUR COLLECTION’s name

4.Proceed node server.js
5.Open your browser and “http://localhost:5000/“ and check for Add, Update and Delete
