# SQL-database-management
This repository contains the files related to my SQL assignment for [Course Name/Number] at [University Name]. The assignment involves creating and querying databases using SQL and SQLite.

## Repository Structure
- task1.sqbpro: SQLite Browser project file for Task 1.
- task2_3.sqbpro: SQLite Browser project file for Tasks 2 and 3.
- clothesinc.db: SQLite database file for Task 1.
Task 1: ClothesInc Database Creation
Description
Task 1 involves creating a database for a fictitious online clothing store called ClothesInc. The relational model includes tables such as Store, StoreEmployee, Customer, Order, OrderDetail, Payment, Product, ProductSupplier, and Supplier. The SQL script builds the database schema according to the provided relational model, with the following key points:

Primary Keys are denoted by bold and underline.
Foreign Keys are denoted by italics.
All primary and foreign key attributes are strings comprising five digits.
PostCodes are strings comprising four digits.
Appropriate data types are used for each attribute (e.g., INTEGER for total, GST, etc., and TEXT for others).
Marking Criteria:
Successfully creating new tables (2 marks)
Including all attributes and correct data types (1 mark)
Correctly creating Primary Keys (1 mark)
Correctly creating Foreign Keys (1 mark)
Correctly creating other constraints (1 mark)
Files:
task1.sqbpro: Contains the SQL script and the execution details for the ClothesInc database creation.
clothesinc.db: The resulting SQLite database after running the script.
Task 2: Hotel Database Querying
Description
Task 2 involves querying a provided hotel database (Hotel IFN554 23s1 v1.db) to extract specific information. The SQL queries include:

Listing hotel numbers, room types, and prices for rooms that are either self or deluxe with a price greater than $200.
Listing hotel numbers that have 3 or more double rooms.
Counting the number of different guests who visited the Grand Chancellor hotel.
Calculating the total income from bookings for the Westin hotel.
Listing all guest names who have visited more than 3 times.
Marking Criteria:
Full marks for each query if it produces the correct result.
Files:
task2_3.sqbpro: Contains the SQL queries and the results for the Hotel database.
Task 3: Indexing and Security
Description
Task 3 involves performing specific database management tasks:

Creating an index on the guestName of the Guest table.
Providing SQL commands to grant or revoke access based on specific requirements for database administrators Nikki and Phil.
Marking Criteria:
Creating an index on guestName (1 mark)
Granting/Revoke access to the Booking and Guest tables (4 marks)
Files:
task2_3.sqbpro: Also includes the commands for creating the index and managing access permissions.
How to Use
Load the Project Files: Use SQLite Browser to open the .sqbpro files to view the SQL scripts and results.
Load the Database: The clothesinc.db file can be opened in SQLite to explore the ClothesInc database created in Task 1.
License
This project is created for educational purposes as part of my coursework at [University Name]. Please do not use the content for any other purpose without permission.

