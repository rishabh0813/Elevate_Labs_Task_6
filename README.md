# Elevate_Labs_Task_6
Sales Trend Analysis Using Aggregations (Task 6 - Data Analyst Internship)
📌 Objective
Analyze monthly revenue and order volume from the given orders.csv dataset using SQL aggregations.
This task demonstrates how to group data by time periods, apply aggregate functions, and extract meaningful insights.

a.Use EXTRACT(MONTH FROM order_date) for month.
b.GROUP BY year/month.
c.Use SUM() for revenue.
d.COUNT(DISTINCT order_id) for volume.
e.Use ORDER BY for sorting.
f.Limit results for specific time periods.

🛠️ Tools
SQL (MySQL)
Dataset: orders.csv
Jupyter Notebook: Sql-Dataset Connection Using Python

✅ Key Learnings

EXTRACT() is used to pull month/year from a date.

SUM(total_price) gives total monthly revenue.

COUNT(DISTINCT order_id) gives unique order volume.

GROUP BY is used for monthly aggregation.

ORDER BY sorts the results by time or revenue.

LIMIT restricts results (e.g., top 3 months or specific years).


📌 Interview Prep Questions

How do you group data by month and year?

What’s the difference between COUNT(*) and COUNT(DISTINCT col)?

How do you calculate monthly revenue?

What are aggregate functions in SQL?

How do you handle NULLs in aggregates?

What’s the role of ORDER BY and GROUP BY?

How do you get the top 3 months by sales?
