# customer-shopping-behavior-analysis
Data analytics project analyzing customer shopping behavior using Python, SQL, and Power BI

# 👨🏻‍💻 Customer Shopping Behavior Analysis — Data Analyst Portfolio Project

An end-to-end data analytics project analyzing customer shopping trends
from retail transaction data, using Python, SQL, and Power BI.

## 📌 Project Overview

This project simulates a real, end-to-end analyst workflow, from raw data
to a business-ready dashboard and report:

✅ **Data Preparation & EDA (Python)** — Cleaned and explored the raw dataset using Pandas and NumPy
✅ **Data Analysis (SQL)** — Answered 10 business questions covering revenue, customer segments, product performance, and discount behavior
✅ **Visualization (Power BI)** — Built an interactive dashboard highlighting key patterns for stakeholders
✅ **Report** — Business Problem Document summarizing the objectives and scope

## 📊 Dataset

Kaggle **"Customer Shopping Trends Dataset"** — 3,900 records, 19 columns
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
5. **Open the Power BI dashboard**
   - Open `customer_behavior_dashboard.pbix` in Power BI Desktop
6. **Read the business problem document**
   - `Business_Problem_Document.pdf` — the problem this project addresses and its scope

## 📈 Key Findings

- Analyzed **3,900 customers**, totaling **$233,081** in revenue, with an average purchase of **$59.76** and an average review rating of **3.75/5**
- **Clothing** is the top revenue category at **$104,264**, more than the next three categories (Accessories, Footwear, Outerwear) combined
- Male and female customers spend almost identically on average (**$59.54** vs **$60.25**) — gender is not a meaningful driver of spend in this dataset
- **43%** of customers (1,677 of 3,900) used a discount on their purchase
- **839 customers** spent above the overall average purchase amount *despite* using a discount — showing discounting doesn't always mean lower-value transactions
- Customers were segmented into New (≤5 previous purchases), Returning (6–20), and Loyal (20+): **Loyal customers make up 60% of the customer base** (2,339 of 3,900), though average spend is nearly flat across all three segments (~$59–61), suggesting loyalty here reflects purchase frequency rather than higher basket size
- Payment method had minimal effect on spend — averages ranged narrowly from **$58.64 (Debit Card)** to **$61.24 (Venmo)**
- Shipping type also showed little variation in average spend (**$58.46–$60.73** across all 6 types), indicating shipping preference isn't linked to order value

## 🗂️ Files

| File | Description |
|---|---|
| `Customer_Shopping_Behavior_Analysis.ipynb` | Python data cleaning and EDA |
| `customer_shopping_behavior_cleaned.csv` | Cleaned dataset (3,900 rows) |
| `customer_behavior_sql_queries.sql` | 10 SQL business questions |
| `customer_behavior_dashboard.pbix` | Power BI interactive dashboard |
| `Business_Problem_Document.pdf` | Project's business problem, objectives, and scope |

## 🧰 Tools Used

Python (Pandas, NumPy) · MySQL · Power BI (DAX) · Jupyter Notebook

## 👨‍💻 About

Built by **G Abishek** as a data analytics portfolio project.
[LinkedIn](https://www.linkedin.com/in/gabishek) · [GitHub](https://github.com/abishek2701)

