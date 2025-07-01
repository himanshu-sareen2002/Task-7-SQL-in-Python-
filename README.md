# Task-7-SQL-in-Python-
Data Analysis Internship Task 7
# Task 7: Basic Sales Summary using SQLite and Python

## Description:
This task connects a SQLite database to Python using `sqlite3`, performs SQL queries, and visualizes sales data using `pandas` and `matplotlib`.

## Files:
- `sales_data.db` — Sample sales database
- `task7_script.py` — Script to extract and visualize sales data
- `sales_chart.png` — Bar chart showing revenue per product

## SQL Query Used:
```sql
SELECT product, SUM(quantity) AS total_quantity, SUM(quantity * price) AS revenue FROM sales GROUP BY product
