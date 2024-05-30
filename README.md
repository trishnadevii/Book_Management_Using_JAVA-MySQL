# Book Management System using MySQL and Java

This project is a book management system developed using Java and MySQL. It allows users to search, view books from a MySQL database.

## Requirements

To run this project, I use the following:

- NetBeans
- MySQL Server
- MySQL Connector/J JDBC driver

## Installation

1. Clone this repository or download the zip file.
2. Install MySQL Server and create a new database.
3. Execute the SQL script `create_database.sql` to create the necessary tables.
4. Update the `DB_URL`, `DB_USER`, and `DB_PASSWORD` constants in the `DBConnection.java` file with your MySQL database information.
5. Add the MySQL Connector/J JAR file to your project's classpath.
6. Compile and run the `Main.java` file.

## Usage

When the program starts, you will see login page. 

When the program starts after login, you will see a menu with the following options:
1. View all books
2. Add a new book
3. Search any books by different options
5. Exit



## Database Schema

The database schema for this project consists of a single table named `books`. The table has the following columns:

'Book_id' int not null
'Book_title'  varchar(100) not null
'Edition' varchar(10)  
'Author'  varchar(100) not null     
'Published_by'  varchar(40)  not null     
'Genre'  varchar(20)  not null  
'Price_in_Rs'  int   not null  
'Total_Pages'  int   not null  
