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


# Customer registers for a new checking account and is pending active :


![Customer_registers-demo](https://user-images.githubusercontent.com/20470279/103751277-09be6380-4fd6-11eb-95f2-3197fa2349d9.gif)


# Administrator approves the customer's checking account :


![Admin-approves](https://user-images.githubusercontent.com/20470279/106399033-5124ed80-63e4-11eb-8555-c58e0450fbcc.gif)



# Customer now has access to their account and decides to add Savings account :
(Savings account is automatically approved because their checking account is verified)


![savings-account-created](https://user-images.githubusercontent.com/20470279/106399352-17ed7d00-63e6-11eb-9014-bc3c494236fb.gif)



# Customer deposits money into their Checking account : 


![checkings-deposit](https://user-images.githubusercontent.com/20470279/106399651-f9888100-63e7-11eb-9b1e-0c6543c72570.gif)



# Customer decides to transfer funds from their Checking account to their Savings account :

![1 7-customerTransferToSavings](https://user-images.githubusercontent.com/20470279/60502780-6aa40780-9c8c-11e9-8673-7df72ec08d69.JPG)



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












