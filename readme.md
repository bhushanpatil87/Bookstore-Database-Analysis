📊 Bookstore Database Analysis

SQL Database Design, ETL & Business Insights

📌 Project Overview

This project involves designing and analyzing a bookstore relational database using SQL (PostgreSQL).

The objective was to build a structured database system and extract meaningful insights related to sales, customer behavior, and inventory management.

This project demonstrates:

✔ Database Design using SQL
✔ Table Relationships (PK–FK)
✔ ETL using CSV Data
✔ Data Cleaning & Validation
✔ Business-Oriented SQL Analysis
✔ Inventory & Sales Insights

🛠 Tools & Environment
Database: PostgreSQL
Query Tool: pgAdmin / SQL Editor
Editor: VS Code
Version Control: Git & GitHub
🗂 Project Structure
bookstore-sql-database/
│
├── schema.sql        → Table creation & relationships  
├── data_import.sql   → CSV data loading (ETL)  
├── queries.sql       → Analysis queries  
└── README.md         → Documentation  
🗄 Dataset Description

The dataset simulates a real-world bookstore system with:

Books (title, author, price, stock)
Customers (name, location, contact details)
Orders (purchase transactions, quantity, revenue)

👉 These tables are connected using primary and foreign keys, forming a relational database structure

Initial Data Considerations:

❌ Missing values
❌ Inconsistent formats
❌ Data duplication risk
❌ Stock vs order mismatch

🔍 Database Design & Methodology
1️⃣ Schema Design
Created Books, Customers, Orders tables
Established relationships using:
Primary Keys
Foreign Keys

👉 Ensures structured and relational data storage (core DB concept)

2️⃣ Data Loading (ETL)
Imported CSV data using SQL
Validated data types and structure
Ensured consistency across tables
3️⃣ Data Analysis Using SQL

Performed business-focused queries:

✔ Total revenue calculation
✔ Top-selling books identification
✔ Customer purchase behavior analysis
✔ Genre-wise sales trends
✔ Inventory stock tracking

👉 SQL helps analyze trends like best-selling products and inventory health

4️⃣ Advanced SQL Techniques
Joins (INNER, LEFT JOIN)
Aggregations (SUM, AVG, COUNT)
Filtering & Sorting
CTEs (Common Table Expressions)
Window Functions (ROW_NUMBER)
📊 Key Insights Generated

✔ Identified top-performing books and genres
✔ Analyzed customer purchase patterns
✔ Calculated total revenue and order trends
✔ Detected low-stock inventory items
✔ Evaluated overall sales performance

🚀 SQL Skills Demonstrated
Database Design & Schema Creation
Relational Modeling (PK–FK)
ETL (CSV Import & Validation)
Query Optimization (basic)
Data Analysis using SQL
Aggregations & Joins
Business Insight Generation
📈 Why This Project Matters

This project reflects real-world database use cases where businesses rely on structured data to:

✔ Track sales and revenue
✔ Manage inventory efficiently
✔ Understand customer behavior
✔ Support data-driven decision-making

👉 Bookstore systems are common examples used to learn database design and analytics in real-world scenarios