# FabricStation-Tableau-Projec

**Project Overview:**

Utilize Tableau Desktop to connect to and analyze data from various sources, including a MySQL database and multiple CSV files. The goal is to create visualizations and summaries that provide insights into sales data by product categories and across different time periods.

**Detailed Steps:**

1. Database Connections:
Establish connections to a MySQL database named "FabricStation" and a CSV file named "Products.csv".
Join the Orderline table from the MySQL database with the product records from the CSV to enhance the product/item information for each record.
2. Calculations and Summary Table:
Introduce a calculated field named SalesAmount to compute the total sales for each order line.
Create a text table to summarize the total quantity sold and sales amount by product category, excluding taxes.
3. Visualization of Orders:
Connect to an additional CSV file, "Orders.csv".
Use a horizontal bar chart to visualize the number of orders placed and the total quantity of items sold, aggregated by year and month.
4. Pie Chart for Sales Composition:
Design a pie chart to display the sales composition across all stores, broken down by product category for each quarter over two years.
5. Mapping Stores and Sales:
Add a connection to "Stores.xlsx".
Display store locations on a map using zip codes and represent the total sales amount by the size of each map marker.
6. Customer Distribution by Zip Code:
Visualize distinct customer zip codes from "Orders.csv" on a map.
Color-code the markers to indicate which store serves each zip code area.
7. Area Chart for Store Sales:
Create a continuous area chart to display monthly sales amounts by store.
8. Finalize and Package:
After completing all visualizations, save the Tableau workbook as a packaged workbook (FabricStation.twbx).
