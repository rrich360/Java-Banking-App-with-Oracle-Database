# Project-Java-Banking-App

# Description:


This application simulates an instance where a customer registers for an account with a bank. The following details below describes how I set up the Oracle database to the java banking application :


 	Created SQL scripts that creates users in Oracle database and table schemas for storing your bank users' account information.
  
 	Implemented Hash Code method in my JavaBeans API to generate account ID for users in my account table in Oracle.

 	This database includes at least 1 or more stored procedures for efficiency in time and space complexity.

 	This bank application connects to the SQL database using JDBC and stores all information that way.

 	I chose to use the Data Access Object(DAO) design pattern in java application for data connectivity.




# How it works for customers :


•		Customers of the bank are able to register with a username and password, and apply to open an account.

•		Customers are able to apply for joint accounts.

•		Once the account is open, customers are able to withdraw, deposit, and transfer funds between accounts (Savings account).

•		All basic validation is checked thoroughly, such as trying to input negative amounts, overdrawing from accounts etc.

# How it works for employees :

•		Employees of the bank should be able to view all of their customers information.

•		This includes, account information, Account balances, and Personal information.

•		Employees should be able to approve/deny open applications for accounts.


# How it works for Bank admins : 

• Should be able to view and edit all accounts.

•	Approving/denying accounts.

•	Withdrawing, depositing, transferring from all accounts.

•	Canceling/deleting accounts.

•	JUnit testing is expected.

•	Log each session (Log4J) so ALL transactions are logged.


# Customer registers for a Checking account with Roger's Bank of America

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

The following picture below shows confirmation that the customer's accounts have been created, both Checking and Savings. (Checking account ID =6; Savings account =7) : 

![1 6-Customer'sChckng SvngsAcctIDs](https://user-images.githubusercontent.com/20470279/60502767-64ae2680-9c8c-11e9-9f36-cd00dfd4b950.JPG)

The following picture below shows the money deposited in the Oracle Database for the checking account :

![1 6-moneyDeposited](https://user-images.githubusercontent.com/20470279/60502774-67108080-9c8c-11e9-9774-5b70a75c2dcc.JPG)

The following picture below exemplifies when a customer decides to transfer funds from their Checking account to their Savings
account :
![1 7-customerTransferToSavings](https://user-images.githubusercontent.com/20470279/60502780-6aa40780-9c8c-11e9-8673-7df72ec08d69.JPG)

The following picture below shows confirmation that the funds were transferred and the correct amount is displayed in the Checking account and in the Savings account : 

![1 7-MoneyTransferred](https://user-images.githubusercontent.com/20470279/60502790-6d066180-9c8c-11e9-962f-53c41138e22a.JPG)

The following picture below displays an action when the Admin decides to view all accounts or see all accounts available : 

![1 8-AdminViewAllAccts](https://user-images.githubusercontent.com/20470279/60503485-d9ce2b80-9c8d-11e9-962e-c8fd22882ce5.JPG)

The following picture below is an example of when the administrator is transferring money for a customer between two bank accounts. In this case the Admin is transferring $44.50 to the customer's Savings account(Account ID :7) from the customer's Checking Account(Account ID: 6) :

![1 9-AdminTransferMoneyToSavngsForCustomer](https://user-images.githubusercontent.com/20470279/60503493-dc308580-9c8d-11e9-926f-c0f8e0378e20.JPG)

The following picture is the result of when the Admin transferred the $44.50 to the customer's Savings account from their Checking Account. Circled in red, you will see that $44.50 was added to the Savings account :

![1 9-AdminTransferredMoneyDB](https://user-images.githubusercontent.com/20470279/60503498-df2b7600-9c8d-11e9-8140-3116bb5ab068.JPG)

The following picture below is an example of a event where the Admin needs to cancel the user's account whether it be due to inactivity, insufficient funds, or fraudulent activity :

![2 0-AdminDeletingUser](https://user-images.githubusercontent.com/20470279/60503499-e18dd000-9c8d-11e9-9ffb-e19655e31960.JPG)

The following picture below is just confirmation displaying that the user's account no longer exists in the database for reference : 

![2 1-UserGoneAdminDeletedUser](https://user-images.githubusercontent.com/20470279/60503504-e3f02a00-9c8d-11e9-9fbf-1ab203f390a5.JPG)












