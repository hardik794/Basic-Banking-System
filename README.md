# Basic Banking System

**Sparks Foundation Internship Project** : Basic Banking System

A Web Application used to transfer money between multiple users (Project contains 10 dummy users). A dummy user can also be created.

**Stack used:**

- Front-end : AngularJs, HTML, CSS, Bootstrap 

- Back-end : NodeJs , ExpressJs ,MongoDB

Database contains two Tables- Customers Table & Transaction History Table

Customers table have basic fields such as name, email & current balance.
Transaction History table records all transfers happened along with their time.
Flow of the Website: Home Page > View all Users > Select and View one User > Transfer Money > Select reciever > View all Users > View Transfer History.

**How To Run Project:-**

 1. Install NodeJs
 2. Install MongoDB And MongoDB Compass
    - Connect MongoDB Compass with localhost
    - Create Database with Name "myproject"
    - Collection Name "sparkbank"
    - Add Dummy data with field  
      - "name" dataType : String 
      - "email" dataType : String 
      - "balance" dataType : Int32
 3. In Project File Open Terminal/CMD/PowerShell
 4. type npm init
 5. type npm install mongoose
 6. type npm install express
 7. type node server.js
 8. Open Browser Use This Link to Run Project 'http://localhost:2800'.
