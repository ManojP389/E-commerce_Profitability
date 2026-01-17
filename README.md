# E-commerce_Profitability
## 📌 Project Overview
This project analyzes **E-commerce sales and expenses data** to evaluate overall **business profitability**.  
Using **SQL, Power BI, and real-world Amazon sales data**, the project provides actionable insights into revenue, orders, expenses, and net profit across categories, cities, and fulfillment types.

The dashboard is designed to help business stakeholders understand:
- Where revenue is coming from
- Which categories and cities perform best
- How expenses impact net profit
---
## 🎯 Objectives
- Analyze total revenue, orders, expenses, and net profit
- Identify top-performing product categories and cities
- Compare revenue by fulfillment type (Amazon vs Merchant)
- Build an interactive and professional Power BI dashboard
- Demonstrate an end-to-end data analytics workflow
---
## 🗂️ Dataset
- **Amazon Sales Dataset** (Kaggle – real-world data)
- Expense data (manually cleaned and structured)
**Key data files:**
- Amazon Sale Report.csv
- Expense IIGF.csv
- clean_expenses.csv
---
## 🛠️ Tools & Technologies
- **SQL (SQLite)** – Data storage and querying
- **Power BI** – Data transformation, modeling, DAX & visualization
- **Power Query** – Data cleaning and preparation
- **GitHub** – Version control and project hosting
---
## 🔄 Project Workflow
1. Collected raw E-commerce sales and expense data (CSV)
2. Cleaned and structured data using Power Query
3. Imported cleaned data into a SQLite database
4. Loaded database into Power BI
5. Created DAX measures for KPIs
6. Designed an interactive dashboard with slicers and visuals
---
## 📐 Key Metrics (KPIs)
- **Total Revenue**
- **Total Orders**
- **Total Expenses**
- **Net Profit**
---
## 📊 Dashboard Insights
- Revenue by product category
- Revenue by city
- Orders and revenue trends over time
- Fulfillment-wise revenue comparison
- Expense impact on profitability
---
## 🧮 DAX Measures Used
Total Revenue = SUM('Amazon Sale Report'[Revenue])
Total Orders = DISTINCTCOUNT('Amazon Sale Report'[OrderID])
Total Expense = SUM('Expense IIGF'[Amount])

Net Profit = [Total Revenue] - [Total Expense]
