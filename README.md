# Customer Shopping Behavior Analysis

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to extract insights related to spending patterns, customer segments, product preferences, and subscription behavior to support data-driven business decisions.

---

## 1. Dataset Summary

* **Total Rows:** 3,900
* **Total Columns:** 18

**Key attributes include:**

* **Customer demographics:** Age, Gender, Location, Subscription Status
* **Purchase details:** Item Purchased, Category, Purchase Amount, Season, Size, Color
* **Shopping behavior:** Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type
* **Missing values:** 37 missing entries in the *Review Rating* column

The dataset is used consistently across Python EDA, SQL analysis, and the Power BI dashboard.

---

## 2. Project Components

The repository contains three primary analytical components:

### 2.1 Python Exploratory Data Analysis

**File:** `Customer_Sales_Analysis.ipynb`

* Performs exploratory data analysis (EDA) on the dataset
* Includes data loading, basic cleaning, and examination of customer behavior variables

---

### 2.2 SQL Analysis

**File:** `Customer_analysis_sql_queries.sql`

* Contains SQL queries for analyzing customer shopping patterns
* Queries aggregate and filter data to provide structured insights into behavior and sales performance

---

### 2.3 Power BI Dashboard

**File:** `Customer_Behavior_powerbi.pbix`

* An interactive dashboard built using Power BI
* Visualizes customer shopping behavior trends, category performance, and other dataset-driven insights

---

## 3. How to Use This Project

### 3.1 Python Notebook (`Customer_Sales_Analysis.ipynb`)

1. Open in Jupyter Notebook, JupyterLab, or VS Code
2. Ensure the dataset (CSV) is available in the appropriate path
3. Execute the notebook cells sequentially to reproduce the EDA

---

### 3.2 SQL Queries (`Customer_analysis_sql_queries.sql`)

1. Import the dataset into a relational database
2. Open the SQL file in your preferred editor
3. Run the queries to replicate the analysis

---

### 3.3 Power BI Dashboard (`Customer_Behavior_powerbi.pbix`)

1. Open the file in Power BI Desktop
2. Confirm correct data source paths
3. Interact with the dashboard to explore insights

---

## 4. Project Structure

```
Customer Shopping Behavior Analysis
│
├── Customer_Sales_Analysis.ipynb        # Python notebook for EDA
├── Customer_analysis_sql_queries.sql    # SQL analysis scripts
├── Customer_Behavior_powerbi.pbix       # Power BI dashboard
└── README.md                            # Project documentation
```

---



