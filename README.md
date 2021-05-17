# Atm_Database_System

The ATM-Database System is the project which is login based for user and used to access their bank accounts in order to make cash 
withdrawals, display Account Balance, transfer Money and other operations. The ATM System is developed in JavaFX and a back-end 
database as SQLIte. JavaFX is the one of the powerful versions of Java-Based Open Source Framework, Hence we used this software.

The ATM will service one customer at a time. A customer will be required to enter username, password – both of which will be sent 
to the database for validation as part of each transaction. The customer will then be able to perform one or more transactions. 
Also customers must be able to make a balance inquiry of any account linked to that Account. The ATM will communicate each transaction
to the database and obtain verification that it was allowed by the database and display it on Screen. In the case of a cash withdrawal,
a second message will be sent after the transaction has been completed (cash withdrawn). If the database determines that the customer’s 
password is invalid, the customer will be required to re-enter the password before a transaction can proceed. If Transaction is failed 
for any other reasons other than password it will be displayed on screen. The User can change Password by entering old Password and 
validating new Password. There will be admin login so as to perform various transactions like add, remove, delete or update details 
of the User from database as well as reset user Password and mail it to User Email-ID.

**Note: The Project is Run on Eclipse and is Maven-based JavaFX Project so ensure you have a stable internet connection and suitable jre version.**
