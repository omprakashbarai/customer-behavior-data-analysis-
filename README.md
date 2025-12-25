# customer-behavior-data-analysis-
End-to-end customer shopping behavior analysis using Python, SQL, and Power BI to derive actionable business insights.

📊 Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to uncover insights into spending patterns, customer segments, product performance, and subscription behavior to support data-driven business decisions.

📂 Dataset Summary

Rows: 3,900

Columns: 18

Key Features:

Customer demographics: Age, Gender, Location, Subscription Status

Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping behavior: Discount Applied, Promo Code Used, Purchase Frequency, Review Rating, Shipping Type

Missing Data: 37 values in review_rating.


🛠 Tools & Technologies

Python: pandas, numpy, matplotlib, seaborn

SQL: PostgreSQL

BI Tool: Power BI

Database: PostgreSQL

Version Control: Git & GitHub

🔍 Data Cleaning & Preparation (Python)

Loaded and explored data using pandas

Handled missing values in review_rating using median by product category

Standardized column names to snake_case

Feature engineering:

Created age_group by binning customer ages

Derived purchase_frequency_days

Removed redundant columns (promo_code_used)

Loaded cleaned data into PostgreSQL for SQL analysis


📈 Exploratory & SQL Analysis

Key business questions answered using SQL:

Revenue comparison by gender

High-spending customers who used discounts

Top 5 highest-rated products

Purchase amount comparison by shipping type

Subscriber vs non-subscriber spending behavior

Products most dependent on discounts

Customer segmentation (New, Returning, Loyal)

Top 3 products per category

Relationship between repeat purchases and subscriptions

Revenue contribution by age group


📊 Power BI Dashboard

An interactive dashboard was built to visualize:

Revenue trends

Customer segments

Product performance

Subscription insights

Shipping and discount behavior

for the dashboard see the file uploaded.


💡 Business Insights & Recommendations

Promote subscription plans with exclusive benefits

Implement loyalty programs for repeat customers

Optimize discount strategies to protect profit margins

Highlight top-rated and best-selling products

Target marketing toward high-revenue age groups and express shipping users
