Task Summary: Basic Sales Summary from SQLite using Python
Objective:
Use Python to connect to a small SQLite database (sales_data.db), run a basic SQL query to summarize sales data, and display the results using print statements and a simple bar chart.

Tools Used:
Python (with built-in sqlite3)

SQLite (no external setup required)

Pandas (for handling query results)

Matplotlib (for bar chart visualization)

Key Steps:
Connect to SQLite database using sqlite3.

Create and populate a simple sales table (with columns: product, quantity, price).

Run SQL query to get:

Total quantity sold per product

Total revenue per product (quantity * price)

Load results into Pandas DataFrame for easy manipulation.

Print the sales summary using print(df).

Plot a bar chart using matplotlib to visualize revenue by product.

Deliverables:
Python script or Jupyter notebook that:

Connects to sales_data.db

Runs 1–2 SQL queries

Prints a sales summary

Displays a basic bar chart of revenue per product

