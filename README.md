# 📚 Online Bookstore Data Analysis Using SQL

## 📌 Project Overview
The Online Bookstore Data Analysis project uses PostgreSQL to manage and analyze bookstore data. It focuses on books, customers, and orders to extract meaningful insights about sales, customer purchasing behavior, book popularity, and inventory.

The project demonstrates how SQL can be used to organize relational data and answer business-related questions through data analysis.

## 🎯 Project Objectives
- Manage book, customer, and order information using a relational database.
- Analyze total sales revenue and customer spending.
- Identify popular books, genres, and authors.
- Examine book prices and inventory levels.
- Retrieve meaningful insights using SQL queries.

## 🛠️ Tools and Technologies
- **Database:** PostgreSQL
- **Language:** SQL
- **Data Sources:** CSV files
- **Tables:** Books, Customers, Orders

## 🗂️ Database Structure

### 1. Books
Stores information about books.

| Column | Description |
|---|---|
| Book_ID | Unique identifier for each book |
| Title | Book title |
| Author | Book author |
| Genre | Book category |
| Published_Year | Year of publication |
| Price | Price of the book |
| Stock | Available stock |

### 2. Customers
Stores customer information.

| Column | Description |
|---|---|
| Customer_ID | Unique identifier for each customer |
| Name | Customer name |
| Email | Customer email |
| Phone | Customer phone number |
| City | Customer city |
| Country | Customer country |

### 3. Orders
Stores book order information.

| Column | Description |
|---|---|
| Order_ID | Unique identifier for each order |
| Customer_ID | References the Customers table |
| Book_ID | References the Books table |
| Order_Date | Date of the order |
| Quantity | Quantity ordered |
| Total_Amount | Total amount of the order |

## 📥 Data Import
The project uses three CSV files as data sources:

- `Books.csv` — Book details
- `Customers.csv` — Customer information
- `Orders.csv` — Order records

The CSV files were imported separately into their corresponding PostgreSQL tables.

Users can download the CSV files from this repository and import them into the respective tables using pgAdmin's Import/Export Data feature.

## 🔍 Key Analysis and SQL Queries

### Basic Analysis
- Retrieve books belonging to a specific genre.
- Find books published after a particular year.
- Filter customers by country.
- Retrieve orders placed during a specified period.
- Calculate total available book stock.
- Identify the most expensive and lowest-stock books.
- Calculate total revenue from orders.

### Advanced Analysis
- Calculate total books sold by genre.
- Find the average price of books in a specific genre.
- Identify customers who placed multiple orders.
- Find the most frequently ordered book.
- Identify the top three most expensive books in a genre.
- Calculate total books sold by each author.
- Identify customer locations associated with high-value orders.
- Find the customer who spent the most.
- Estimate remaining stock based on recorded orders.

## 💡 SQL Concepts Used
- Database and table creation
- Primary keys and foreign keys
- Data import from CSV files
- SELECT and WHERE clauses
- ORDER BY and LIMIT
- DISTINCT
- Aggregate functions such as SUM(), AVG(), and COUNT()
- GROUP BY and HAVING
- INNER JOIN and LEFT JOIN
- SQL data analysis techniques

## 📈 Key Learnings
- Designed a relational database with connected tables.
- Imported CSV datasets into PostgreSQL.
- Practiced writing SQL queries to retrieve and analyze data.
- Explored sales, customer purchasing patterns, and book popularity.
- Applied aggregate functions and joins to summarize information.
- Used SQL to answer practical business questions.

## 🚀 How to Run the Project

1. Install PostgreSQL and open pgAdmin.
2. Execute the SQL script to create the database and tables.
3. Download the three CSV files from this repository.
4. Import `Books.csv`, `Customers.csv`, and `Orders.csv` into their corresponding tables using pgAdmin's Import/Export Data feature.
5. Execute the SQL queries to analyze the bookstore data.

## 📁 Project Files
- `README.md` — Project documentation
- `OnlineBookstore.sql` — SQL script for database creation, table creation, data import, and analysis
- `Books.csv` — Book information
- `Customers.csv` — Customer information
- `Orders.csv` — Order information

## 👨‍💻 Author
**M Ganesh Kumar**

Electronics and Communication Engineering Student

GitHub:https: //github.com/mganesh1013-tech