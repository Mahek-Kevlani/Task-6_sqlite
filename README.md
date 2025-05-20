Sales Trend Analysis 

Objective
Analyze monthly revenue and order volume using SQL aggregation.
Tools Used
- SQLite (DB Browser for SQLite)
- SQL

Files Included
- sample_online_sales.sql – SQL script to create and populate the table
- analysis_queries.sql – SQL queries for analysis
- results.png – Screenshot of query results

Analysis Summary
- Grouped data by month and year using strftime
- Used SUM(amount) for revenue
- Used COUNT(DISTINCT order_id) for volume
- Extracted top 3 months with highest revenue

Output Preview
Query Result Screenshot
