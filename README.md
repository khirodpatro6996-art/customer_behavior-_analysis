# customer_behavior-_analysis


 # 📊 Customer Behavior Analysis & Dashboard

 ## 📌 Project Overview
 
This project analyzes customer purchasing behavior to uncover insights related to spending patterns, discounts, loyalty, subscriptions, and demographics. The goal is to demonstrate an end-to-end data analytics workflow — from data cleaning and exploration to SQL analysis and interactive dashboarding.


## 🛠️ Tools & Technologies Used

* **Python** (Pandas, SQLAlchemy)
* **SQL (MySQL)** for analytical querying
* **Power BI** for interactive dashboarding
* **Jupyter Notebook** for EDA and data preparation
* **GitHub** for version control and project documentation

---

## 🔄 Data Workflow 

1. **Raw dataset** loaded in Python
2. **Data cleaning & feature engineering** performed in `eda.ipynb`
3. Cleaned dataset exported as `customer_cleaned.csv`
4. Same cleaned dataset used for:

   * SQL analysis (via SQLAlchemy)
   * Power BI dashboard


## 🧹 Data Cleaning & Feature Engineering

Key steps performed:

* Handled missing values (e.g., median imputation for review ratings)
* Standardized column names using snake_case
* Removed irrelevant columns
* Created new features:
  * `age_group`
  * `purchase_frequency_days`
* Validated data quality after cleaning

## 🔍 Exploratory Data Analysis (EDA)

EDA focused on understanding:

* Customer demographics
* Spending behavior
* Category-level revenue
* Discount usage patterns
* Customer loyalty distribution
* 
Each EDA output is accompanied by **clear, business-focused insights** written in Markdown.

---

## 🗄️ SQL Analysis

SQL analysis was performed using **SQLAlchemy** to connect Python with the database.
Key analytical questions answered include:

* Revenue comparison by gender
* High-value discount usage
* Top-rated products
* Shipping method impact on spending
* Subscription vs non-subscription performance
* Customer segmentation (New, Returning, Loyal)
* Repeat buyer behavior
* Revenue contribution by age group
* Core business KPIs

Each SQL query is followed by a **concise insight**, and a final **SQL Insights Summary** consolidates findings.

---

## 📈 Key Business KPIs

* **Total Revenue**
* **Average Order Value**
* **Repeat Customer Rate**
* **Subscriber Revenue Contribution**

These KPIs are used consistently across SQL outputs and Power BI visuals.

---

## 📊 Power BI Dashboard

The Power BI dashboard visualizes:

* Customer count, average purchase amount, and ratings (KPI cards)
* Revenue and sales by category
* Revenue and sales by age group
* Subscription and discount behavior
* Interactive slicers for dynamic exploration

The dashboard is fully aligned with the SQL analysis and uses the **cleaned dataset only**.

---

## 💡 Key Insights Summary

* The customer base shows strong retention, with a high proportion of loyal customers.
* Revenue is higher among male customers, though spending patterns are broadly consistent.
* Discounts are widely used, but only a small percentage of customers combine discounts with high-value spending.
* Subscription status currently impacts customer volume more than per-order spending.
* Revenue is fairly evenly distributed across age groups, indicating broad market appeal.

---

## 🎯 Business Recommendations

* Improve subscription adoption among repeat and loyal customers.
* Apply discounts more selectively to avoid margin loss on high-value customers.
* Prioritize high-rated and high-demand products for inventory and promotions.
* Maintain balanced marketing across age groups due to evenly distributed revenue.

---

## ✅ Conclusion

This project demonstrates an **end-to-end data analytics pipeline**, integrating Python-based data preparation, SQL analysis, and Power BI visualization. It reflects real-world analytical thinking, clean data practices, and business-focused insights suitable for stakeholder decision-making.
et points**

