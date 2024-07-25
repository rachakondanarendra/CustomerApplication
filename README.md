# Customer Application CRUD Operations
## How to Install and Run in Local

**Download the above 'Customer.war' file**

**Go to Eclipse IDE and make sure that Apche Tomacat 9 Server available in Eclipse"**

**Import the 'Customer.war' file in Eclipse**

**Then Click 'Next' and select the two jars(JSON Jar file and MySQL connector Jar file)"**

### DataBase Creation

**Create a Database 'customer_db'"**

**Username and Password of the data base should be this -> Username:root and Password:root**

**Create 'User' and 'Customer' tables by running following queries**

**CREATE TABLE User (
    UserId INT AUTO_INCREMENT PRIMARY KEY,
    Username VARCHAR(255) NOT NULL,
    Password VARCHAR(100) NOT NULL,
    Email VARCHAR(100) NOT NULL, 
    Address TEXT
);**

 **CREATE TABLE Customers (
    CustomerID VARCHAR(50) PRIMARY KEY,
    First_Name VARCHAR(50) NOT NULL,
    Last_Name VARCHAR(50) NOT NULL,
    Street VARCHAR(100) NOT NULL,
    Address VARCHAR(100) NOT NULL,
    City VARCHAR(50) NOT NULL,
    State VARCHAR(50) NOT NULL,
    Email VARCHAR(100) NOT NULL,
    Phone VARCHAR(15) NOT NULL
);**

**Now, In Eclipse right click on the project> Run As > Run on Server> Select Apace Tomcat 9 Server> Next> Finish**


**Project Will Automatically opens in Web Browser**





