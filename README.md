# 📊 Superstore Sales Analysis Dashboard (Python + Power BI)

---

## 1. **Project Title & Headline**

### Title:

**Superstore Sales & Profit Analysis Dashboard (Python + Power BI)**

### Headline:

An end-to-end data analysis project using Python for data cleaning and exploratory analysis, and Power BI for interactive dashboard visualization to uncover insights about sales performance, profitability, and business trends.

---

## 2. **Short Description / Purpose**

This project focuses on analyzing the Superstore sales dataset to gain insights into business performance.

The project is divided into two main phases:

* **Python (EDA & Data Cleaning)** – Used to explore, clean, and analyze raw data.
* **Power BI (Dashboard)** – Used to build an interactive dashboard for visualization.

The goal is to identify sales trends, evaluate profitability, detect loss-making areas, and provide data-driven insights to support business decision-making.

---

## 3. **Tech Stack**

The following tools and technologies were used:

* **Python** (Pandas, NumPy, Matplotlib, Seaborn) – Data cleaning & analysis
* **Power BI** – Dashboard creation & visualization
* **Power Query** – Data transformation
* **DAX (Data Analysis Expressions)** – KPI calculations
* **Excel / CSV** – Data source
* **GitHub** – Version control & documentation

---

## 4. **Data Source**

The dataset used is the **Superstore dataset**, widely used for business analytics practice.

It contains:

* Order Date
* Customer Segment
* Region
* Category & Sub-Category
* Sales
* Profit
* Quantity
* Discount

---

## 5. **Business Problem**

Retail companies generate large volumes of sales data, but without analysis it becomes difficult to understand:

* Which products generate the highest revenue
* Which categories are profitable or loss-making
* Which regions perform best
* How sales change over time
* What factors cause losses

---

## 6. **Project Goal**

The goal of this project is to:

* Monitor overall sales and profit
* Identify top-performing categories
* Detect loss-making products
* Analyze regional performance
* Understand sales trends
* Identify root causes of losses

---

# 7. **Python Analysis (EDA & Data Cleaning)**

---

##  Data Cleaning

* Checked dataset structure using `.info()` and `.shape()`
* Verified missing values using `.isnull()`
* Removed duplicates using `.drop_duplicates()`
* Converted `Order Date` to datetime format
* Cleaned column names

---

##  Exploratory Data Analysis (EDA)

### 1. KPI Analysis

* Total Sales
* Total Profit
* Total Orders
* Profit Margin

👉 Purpose: Understand overall business performance

---

###  2. Category & Sub-Category Analysis

* Identified top-performing categories
* Found loss-making sub-categories (e.g., Tables, Bookcases)

 Purpose: Evaluate product profitability

---

###  3. Region Analysis

* Compared sales & profit across regions
* Identified underperforming regions

👉 Purpose: Analyze geographic performance

---

###  4. Segment Analysis

* Compared Consumer, Corporate, Home Office
* Calculated profit efficiency

👉 Purpose: Identify high-value customers

---

###  5. Time Series Analysis

* Monthly sales trend using resampling

👉 Purpose: Identify trends & seasonality

---

###  6. Discount vs Profit Analysis (Key Insight)

* Scatter plot analysis
* Found negative relationship between discount and profit

👉 Purpose: Identify root cause of losses

---

##  Key Findings (Python)

* High discounts significantly reduce profit
* Certain sub-categories consistently generate losses
* Consumer segment drives highest sales
* Corporate segment shows better efficiency
* Sales fluctuate over time

---

#  8. **Power BI Dashboard**

---

##  Features

* Interactive filters (Region, Category, Segment)
* Dynamic KPI cards
* Drill-down capabilities

---

##  KPI Cards

* Total Sales
* Total Profit
* Profit Margin
* Total Quantity

---

##  Key Visualizations

* **Sales & Profit by Region** → Regional performance
* **Sales Trend (Line Chart)** → Time-based trends
* **Profit by Sub-Category** → Identify losses
* **Discount vs Profit (Scatter Plot)** → Root cause analysis

---

##  Insights from Dashboard

* Technology category generates highest profit
* Tables and Bookcases are loss-making
* West region performs best
* Sales show seasonal patterns
* High discounts lead to losses

---

# 🖼️ 9. **Dashboard Preview**

![Dashboard](https://github.com/ashish141008-tech/superstore-sales-analysis-PowerBI/blob/main/Superstore_Sales_Analysis.png)

---

#  10. **Final Conclusion**

This project demonstrates an end-to-end data analysis workflow:

* Python was used to clean and explore the data
* Power BI was used to visualize insights

### Key Business Insight:

> High discount strategies negatively impact profitability and are a major cause of losses.

---

#  11. **Future Improvements**

* Add predictive analysis (forecasting)
* Build SQL-based data pipeline
* Enhance dashboard UI/UX
* Add more business KPIs

---

#  12. **Author**

**Ashish Kumar Gupta**
📧 [ashish141008@gmail.com](mailto:ashish141008@gmail.com)

---

⭐ If you found this project helpful, feel free to star the repo!
