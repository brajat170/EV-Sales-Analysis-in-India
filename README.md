# EV-Sales-Analysis-in-India

SQL | Power BI | Data Analytics Project

📌 Project Overview

This project analyzes Electric Vehicle (EV) sales across India using SQL for data analysis and Power BI for interactive visualization.
The objective is to understand state-wise EV adoption, monthly and quarterly trends, and vehicle-category performance, helping identify growth patterns in India’s EV market.

This project demonstrates end-to-end data analyst skills — from raw data handling to dashboard insights.

🛠 Tools & Technologies

SQL (PostgreSQL) – Data cleaning, aggregation, CTEs, window functions

Power BI – Interactive dashboards, DAX measures

Excel / CSV – Source datasets

GitHub – Version control & documentation

📂 Project Files

This repository contains:

EV SALES.sql → SQL queries for data analysis

evsales.pbix → Power BI dashboard file

🗄️ Dataset Description

The dataset includes EV sales data across Indian states with the following columns:

State

Sale Date

Vehicle Category (2-Wheeler, 3-Wheeler, 4-Wheeler)

EVs Sold

Total Vehicles Sold

🔍 SQL Analysis Performed

Using SQL, the following analyses were carried out:

State-wise total EV sales

Monthly EV sales trends

Quarterly EV sales analysis

Ranking top-performing states using window functions

Vehicle category-wise EV sales distribution

Example SQL Query
SELECT 
    state,
    SUM(ev_sold) AS total_ev_sales
FROM sales_by_state
GROUP BY state
ORDER BY total_ev_sales DESC;

📊 Power BI Dashboard Features

The Power BI dashboard includes:

🔹 KPI Cards

Total EVs Sold

Monthly EV Sales

Total 2-Wheeler EVs Sold

🔹 Visualizations

State-wise EV Sales Map (India)

Monthly EV Sales Trend

Quarterly EV Sales Trend

Vehicle Category-wise EV Sales

Top States by EV Sales

🔹 Interactivity

Filters for Year, State, and Vehicle Category

Drill-down analysis for better insights

📈 Key Insights

EV adoption is increasing steadily across India

Two-wheelers account for the majority of EV sales

Certain states consistently outperform others in EV adoption

Clear month-on-month and quarter-on-quarter growth trends observed

🎯 Skills Demonstrated

SQL querying (GROUP BY, CTEs, Window Functions)

Data aggregation & trend analysis

Power BI dashboard design

KPI creation & business storytelling

Analytical thinking & insight generation

🚀 How to Use This Project

Import the dataset into PostgreSQL

Run queries from EV SALES.sql

Open evsales.pbix in Power BI

Refresh data and explore the dashboard

📬 Contact

Rajat Bhatia

📧 Email: brajat909@gmail.com

🔗 LinkedIn: (linkedin.com/in/rajat-bhatia-2094341a2)
📧 Email: brajat909@gmail.com

🔗 LinkedIn: (add your LinkedIn profile link)
