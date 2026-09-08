# 📚 Online Bookstore SQL Analysis

## 📌 Project Overview

This project focuses on analyzing an **Online Bookstore dataset** using **SQL**. The project includes data related to **Books, Customers, and Orders**.

The goal of this project is to perform data analysis using SQL queries and extract meaningful insights from the bookstore data.

---

## 🛠️ Tools Used

- PostgreSQL
- SQL
- CSV Dataset

---

## 📂 Dataset

The project contains three datasets:

### 📚 Books
Contains information about books, including:

- Book ID
- Title
- Author
- Genre
- Published Year
- Price
- Stock

### 👤 Customers
Contains customer information, including:

- Customer ID
- Name
- Email
- Phone
- City
- Country

### 🛒 Orders
Contains order-related information, including:

- Order ID
- Customer ID
- Book ID
- Order Date
- Quantity
- Total Amount

---

## 🗄️ Database Structure

The database consists of three tables:

- `Books`
- `Customers`
- `Orders`

### Relationships

- Each customer can place multiple orders.
- Each book can appear in multiple orders.
- The `Orders` table connects the `Customers` and `Books` tables.

---

## 📊 SQL Analysis

The project includes both **Basic** and **Advanced SQL queries**.

### Basic Analysis

Some of the analysis performed:

1. Retrieve books from a specific genre.
2. Find books published after a specific year.
3. Retrieve customers from a specific country.
4. Find orders placed during a specific period.
5. Calculate the total stock of books.
6. Find the most expensive book.
7. Identify customers who ordered more than one book.
8. Retrieve orders with a total amount above a specified value.
9. List all available book genres.
10. Find the book with the lowest stock.
11. Calculate total revenue generated from orders.

---

### Advanced Analysis

The advanced analysis includes:

1. Total number of books sold for each genre.
2. Average price of books in a specific genre.
3. Customers who placed multiple orders.
4. Most frequently ordered book.
5. Top expensive books from a specific genre.
6. Total quantity of books sold by each author.
7. Cities where customers spent above a specified amount.
8. Customer who spent the most on orders.
9. Remaining stock after fulfilling orders.

---

## 🔍 SQL Concepts Used

This project demonstrates the following SQL concepts:

- `SELECT`
- `WHERE`
- `ORDER BY`
- `GROUP BY`
- `HAVING`
- `JOIN`
- `LEFT JOIN`
- Aggregate Functions
  - `SUM()`
  - `AVG()`
  - `COUNT()`
- `DISTINCT`
- `LIMIT`
- `COALESCE()`

---

## 📁 Project Structure

```text
Online-Bookstore-SQL-Analysis/
│
├── Source-Data/
│   ├── Books.csv
│   ├── Customers.csv
│   └── Orders.csv
│
├── Project on SQL Only Questions/
│   └── questions.sql
│
├── Project on SQL - Solved_questions/
│   └── project.sql
│
└── README.md



👨‍💻 Author

Piyush Mishra

Aspiring Data Analyst

🔗 LinkedIn: piyush-mishra113

🔗 GitHub: piyush-mishra9
