# Project-Banking-App

Description:


Leveraging Java 8, this application simulates a customer registering for an account with a bank.


Details:


-	Built this application using Java 8;
-	All interaction with the user should be done through the console using the Scanner class.
-	Customers of the bank should be able to register with a username and password, and apply to open an account.
-	Customers should be able to apply for joint accounts
-	Once the account is open, customers should be able to withdraw, deposit, and transfer funds between accounts (Savings account)
-	All basic validation should be done, such as trying to input negative amounts, overdrawing from accounts etc.
-	Employees of the bank should be able to view all of their customers information
-	This includes, account information, Account balances, and Personal information
-	Employees should be able to approve/deny open applications for accounts


Bank admins should be able to view and edit all accounts
This includes:

•	Approving/denying accounts
•	withdrawing, depositing, transferring from all accounts
•	canceling accounts
•	JUnit testing is expected
•	Logging was accomplished using Log4J
•	All transactions are logged

-	Create an SQL script that will create a user in an SQL database and a table schema for storing your bank users and account information.
-	Your database should include at least 1 stored procedure.
-	Have your bank application connect to your SQL database using JDBC and store all information that way.
-	You should use the DAO design pattern for data connectivity.


This output includes an example of a customer's information being stored in a database after registering for an account with Roger's Bank of America :

![1 0-customerRegisterForChecking](https://user-images.githubusercontent.com/20470279/60501872-c1104680-9c8a-11e9-997e-be1146b75d96.JPG)


The following picture below is an example of a customer's account pending after registering for the account : 

![1 1-customer'sAcctPending](https://user-images.githubusercontent.com/20470279/60501883-c7062780-9c8a-11e9-812e-1c6e35e42f70.JPG)

The following picture below exemplifies when the Administrator approves the customer's account :

![1 3-AdminApprovesCustomer'sAcct](https://user-images.githubusercontent.com/20470279/60501891-ccfc0880-9c8a-11e9-81b1-756fd1744251.JPG)

The following picture below is an example of when the customer has access to his or her account and is able to make changes to the account whether it be deposit, withdraw, transfer or add another account :

![1 4-CustomerAbleUseAcctAfterApprove](https://user-images.githubusercontent.com/20470279/60501900-cff6f900-9c8a-11e9-80cc-33a7b3baae7b.JPG)

The following picture below is an example of when a customer chooses to add a Savings account with their Checking account. This is typical behavior so logic for this option should be added by default for users in a bank :

![1 5-customerAddSavingsAcct](https://user-images.githubusercontent.com/20470279/60501938-deddab80-9c8a-11e9-92cf-9d6a5e6227f1.JPG)

The following picture below is an example of when a customer deposits money into their Checking account : 
![1 6-CustomerDeposits](https://user-images.githubusercontent.com/20470279/60501948-e2713280-9c8a-11e9-94b8-6b2648ae1d75.JPG)
















