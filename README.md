# SQLite_python_project

This project demonstrates the use of SQLite with Python to perform various SQL operations on a dataset containing 8 different tables. The operations range from simple queries to more complex data analysis tasks.

## Project Overview

The project involves the following steps:

1. **Creating the Database:** A new SQLite database is created to store the 8 tables.
2. **Loading the Data:** The data for each table is loaded into the database.
3. **Executing SQL Queries:** A series of SQL queries are performed on the dataset to extract meaningful insights.

## Prerequisites

To run this project, you will need the following:

- **Python 3.x** installed on your machine.
- **SQLite** installed.
- **Jupyter Notebook** (optional, but recommended for interactive execution).

## Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/sqlite_python_project.git
   cd sqlite_python_project
Create the Database:

Ensure that your SQLite database is created and named according to your preference. By default, the code expects a database named veri_tabanları_sql.db. If you choose a different name, modify the connection string at the beginning of the notebook or script:

python
Copy code
%sql sqlite:///your_database_name.db
Load the Data:

Load the 8 tables into the SQLite database. Make sure that the data files are in the same directory as your Python script or Jupyter Notebook.

Run the Queries:

Execute the SQL queries provided in the project to interact with the database and perform the desired operations.

SQL Queries Overview
The project includes a set of SQL queries that perform the following tasks:

1-Count the number of customer entities in the Orders table./n
2-Find the number of unique customers in the Orders table./n
3-Group customers by country and count how many are in each./n
4-Filter customers based on whether they are from Brazil or the USA./n
5-Group customers by country and city, then count them./n
6-Find addresses containing the word "da"./n
7-Identify customers living in Germany-Berlin./n
8-Filter customers in Canada whose names contain "in"./n
9-List products with prices between $40 and $90./n
10-Find product names, prices, and squares of the prices for items over $30./n
11-List the CategoryIDs in the Products table./n
12-Calculate the average price of products in the "Beverages" category./n
13-Find total earnings from customers living in the USA./n
14-Calculate the average product price per category./n
15-List employees by their total sales./n
16-Find the average prices of orders from Germany by category./n
17-Calculate average prices of orders from Germany and the USA by category./n
18-Find the average price of orders placed in June, July, and August./n
19-List the maximum quantities of customer orders for 1997./n
20-List employees with orders from 1997, sorted by the number of orders./n
Usage
Interactive Execution:

If using a Jupyter Notebook, you can run the provided SQL queries interactively. The queries are written with %sql magic commands, which allow direct interaction with the SQLite database.

Script Execution:

If running as a Python script, ensure that the necessary libraries (sqlite3, pandas, etc.) are imported, and the database connection is correctly established.

Contributing
If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are welcome.
