AIM: 
 To execute Transactional Control Commands such as Commit, Rollback and Savepoint. 
ALGORITHM: 
STEP 1: Start the DMBS. 
STEP 2: Connect to the existing database (DB)  
STEP 3: Create the table with its essential attributes. 
STEP 4: Insert record values into the table or perform any kind of DML operation. 
STEP 5: Create the SAVE POINTs for some set of statement on the transaction of database object. STEP 6: Use the COMMIT command to save the effect of the previous command operation except DDL command 
STEP 7: Use the ROLLBACK TO SP_LABLE / ROLLBACK command for restore the database status up to the save point STEP 8: Check the status of the database.  
STEP 9: Stop the DBMS. 
THEORY: 
Transaction Control Language(TCL) commands are used to manage transactions in the database.These are used to manage the changes made to the data in a table by DML statements. It also allowsstatements to be grouped together into logical transactions. 
COMMIT command 
COMMIT command is used to permanently save any transaction into the database. 
To avoid that, we use the COMMIT command to mark the changes as permanent. 
Syntax: 
COMMIT; 
ROLLBACK command 
This command restores the database to last commited state. It is also used with SAVEPOINT 
command to jump to a savepoint in an ongoing transaction. 
Syntax: 
ROLLBACK TO savepoint_name; 
SAVEPOINT command 
SAVEPOINT command is used to temporarily save a transaction so that you can rollback to that point when ever required. 
Syntax: 
SAVEPOINT savepoint_name; 
