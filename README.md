# customer-shopping-behavior-analysis
Data analytics project analyzing customer shopping behavior using Python, SQL, and Power BI
# 👨🏻‍💻 Customer Shopping Behavior Analysis — Data Analyst Portfolio Project

An end-to-end data analytics project analyzing customer shopping trends
from retail transaction data, using Python, SQL, and Power BI.

## 📌 Project Overview

This project simulates a real, end-to-end analyst workflow, from raw data
to a business-ready dashboard and report:

✅ **Data Preparation & EDA (Python)** — Clean and explore the raw dataset using Pandas and NumPy
✅ **Data Analysis (SQL)** — Answer 12 business questions covering revenue, customer segments, product performance, and discount behavior
✅ **Visualization (Power BI)** — Interactive dashboard highlighting key patterns for stakeholders
✅ **Report & Presentation** — Written findings and recommendations

## 📊 Dataset

Kaggle **"Customer Shopping Trends Dataset"** — ~3,900 records, 18 columns
(age, gender, item purchased, category, purchase amount, payment method,
subscription status, discount usage, review rating, and more).
Link: https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset

This is a publicly available dataset used for portfolio/educational
purposes, not real company data.

## 🛠️ How to Use This Project

1. **Clone the repository**
   ```
   git clone https://github.com/<your-username>/customer-shopping-behavior-analysis.git
   cd customer-shopping-behavior-analysis
   ```
2. **Open `Customer_Shopping_Behavior_Analysis.ipynb`**
   Contains data import, exploration, cleaning, and the connection to MySQL.
3. **Load the cleaned data into MySQL**
   - Create a database named `customer_shopping_db`
   - Run the notebook's `df.to_sql(...)` step to load the cleaned data
4. **Run the SQL business questions**
   - Open `customer_behavior_sql_queries.sql` in MySQL Workbench
   - Each query answers a specific business question, ordered simple to complex
5. **Open the Power BI dashboard**
   - Open `customer_behavior_dashboard.pbix` in Power BI Desktop
6. **Read the full findings**
   - `Business Problem Document.pdf` — the problem this project addresses

## 📈 Key Findings

*(Fill this in with your real results once you've run the queries — for
example:)*
- Total revenue analyzed: **[$X]** across **[X]** customers
- **[Category name]** generated the highest revenue at **[$X]**
- **[Subscribed / Non-subscribed]** customers had a **[X]%** higher average spend
- **[X]%** of customers fall into the "Loyal" segment, contributing **[$X]** in average spend
- **[Payment method]** customers had the highest average order value


## 🧰 Tools Used

Python (Pandas, NumPy) · MySQL · Power BI (DAX) · Jupyter Notebook

## 👨‍💻 About

Built by **G Abishek** as a data analytics portfolio project.
[LinkedIn](https://www.linkedin.com/in/gabishek) · [GitHub](https://github.com/abishek2701)
