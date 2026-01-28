# Pizza Sales Analysis

## Overview
This project analyzes transactional data for a pizza store to optimize inventory and sales performance.By processing over **48,620 rows** of data, the analysis identifies peak order times, best-selling pizza categories, and key revenue drivers to inform operational improvements.

## Dataset
The project utilizes a comprehensive sales dataset:
* **Total Records:** 48,620 rows.
* **Features:** 12 key columns including Order ID, Quantity, Price, and Pizza Category.
* **Key Metrics:** Tracks unit price, total price, pizza size, and ingredients.

## Tools & Technologies
* **SQL (PostgreSQL/SQL Server):** Data cleaning and complex querying for business KPIs.
* **Power BI:** Interactive dashboard development for sales tracking.
* **Python:** Initial data exploration and statistical summaries.
* **Excel:** Raw data management and preliminary filtering.

## Project Steps
1.  **Requirement Gathering:** Defined business questions regarding daily/monthly trends and product performance.
2.  **Data Cleaning:** Standardized date formats and handled null values to ensure reporting accuracy.
3.  **SQL Analysis:** Wrote queries to calculate critical metrics like **Average Order Value** and **Total Pizzas Sold**.
4.  **Data Visualization:** Designed a dual-page Power BI dashboard focusing on "Home" metrics and "Best/Worst Sellers."
5.  **Insights Generation:** Analyzed sales distribution across categories and sizes to identify consumer preferences.

## Dashboard
The Power BI dashboard provides a visual breakdown of:
* **KPIs:** Total Revenue ($817.86K), Average Order Value ($38.31), and Total Pizzas Sold (68K).
* **Trends:** Daily and monthly order distributions to identify peak periods.
* **Category Analysis:** Sales performance across Classic, Supreme, Veggie, and Chicken categories.
* **Top/Bottom Performers:** Rankings for the top 5 and bottom 5 pizzas based on revenue, quantity, and total orders.

## Key Results & Insights
* **Total Revenue:** The store generated a total of **$817,860.05**.
* **Average Order Value:** The average spend per order was **$38.31**.
* **Peak Activity:** Friday and Saturday evenings were identified as the highest-volume periods.
* **Top Seller by Revenue:** The **Thai Chicken Pizza** contributed the most to total sales revenue.
* **Volume Leader:** The **Classic Deluxe Pizza** had the highest total quantity sold.

## How to Run
1.  **Database:** Execute the provided SQL script in your SQL environment to generate the KPI tables.
2.  **Visuals:** Open the `.pbix` file in Power BI Desktop to interact with the sales filters and charts.
3.  **Reporting:** Review the included presentation for a summary of findings and business recommendations.
