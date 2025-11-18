# 📊 Customer Behavior Analysis Dashboard

A complete end-to-end data analytics project covering **data cleaning**, **SQL business analysis**, and **Power BI dashboard development**. This README provides project details, installation steps, workflow, insights, and file structure.

---

## 📊 Dashboard Preview

<p align="center">
  <img src="images/dashboard_preview.png" alt="Dashboard Preview" width="750">
</p>

---

## 🚀 Project Overview

This project analyzes customer purchasing behavior using a full data pipeline — from raw data processing to BI dashboard creation. It helps businesses understand spending patterns, customer segments, seasonal revenue trends, and subscription performance.

### **Key Metrics**

* **Total Customers:** 3,900
* **Total Revenue:** $233,000
* **Average Purchase Amount:** $59.76
* **Average Review Rating:** 3.75 / 5

---

## 🛠️ Technologies Used

* **Python 3.8+** (Pandas, NumPy)
* **SQL** (PostgreSQL/MySQL)
* **Power BI**
* **Jupyter Notebook**
* **Git & GitHub**

---

## 🔄 Project Workflow

### **Phase 1: Data Preparation & Cleaning (Python)**

* Handling missing values (median imputation)
* Standardizing categorical fields
* Creating derived columns (e.g., `purchase_frequency_days`)
* Data validation and quality checks

### **Phase 2: Business Analysis (SQL)**

Conducted analysis on:

* Revenue segmentation
* Customer demographics
* Seasonal patterns
* Subscription impact
* Spending behaviors

*(Only the topics are mentioned. Actual queries are inside `sql_queries/business_questions.sql`)*

### **Phase 3: Dashboard Development (Power BI)**

* KPI cards and category-wise visuals
* Slicers for interactive filtering
* Custom theme for professional design

---

## 🧹 Data Cleaning Summary

Performed using Python:

* Missing value treatment
* Standardizing labels: Gender, Category, Seasons
* Frequency mapping:

  * Weekly → 7 days
  * Fortnightly → 14 days
  * Monthly → 30 days
  * Quarterly → 90 days
  * Annually → 365 days

---

## 📈 Dashboard Summary (Power BI)

### **Main Visuals**

* Revenue by Category
* Revenue by Season
* Customers & Revenue by Age Group
* Customers by Gender
* Subscription Status
* Purchase Frequency Distribution

### **Slicers**

* Gender
* Age Group
* Payment Method
* Subscription Status
* Category
* Frequency Type

### **Color Palette**

* Blue: `#1f77b4`
* Orange: `#ff7f0e`
* Green: `#2ca02c`
* Background: `#f8f9fa`

---

## 🔍 Key Insights

* **Female customers contribute 68% of revenue**
* **Winter season generates the highest revenue**
* **Clothing category accounts for 40% of revenue**
* **Subscribers spend 25% more on average**
* Weekly shoppers show **40% higher lifetime value**
* Middle-aged customers spend the most

---

## 💼 Business Impact

### **Supports Strategic Decisions in:**

* Marketing optimization
* Subscription program enhancement
* Inventory planning
* Pricing & discount strategies
* Customer retention programs

---

## 📁 Project Structure

```
Customer-Behavior-Analysis/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   └── 02_data_analysis.ipynb
│
├── sql_queries/
│   └── business_questions.sql
│
├── powerbi/
│   ├── customer_behavior_dashboard.pbix
│   └── dashboard_theme.json
│
├── docs/
│   └── project_report.pdf
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
```

---

## 🔗 Contact & Profiles

**Author:** *Sasikumar Anandan*
**Role:** Data Analyst | BI Professional

### Connect with me:

* **LinkedIn:** [Click Here](https://linkedin.com/in/sasikumar-anandan)
* **GitHub:** [Click Here](https://github.com/sasikumar69)
* **Portfolio:** [Click Here](https://sasikumar69.github.io/personal-portfolio)
* **Email:** [sasikumam77@gmail.com](mailto:sasikumam77@gmail.com)

---

## 🧠 Skills Demonstrated

### **Technical Skills**

* Python (Pandas, NumPy)
* SQL (PostgreSQL/MySQL)
* Power BI & Data Visualization
* Data Cleaning & Preprocessing
* Statistical & Business Analysis

### **Business Skills**

* Revenue & customer behavior analysis
* Strategic decision support
* BI dashboard reporting
* Data-driven insights

---

## ✅ Project Conclusion

This project showcases a complete analytical workflow from **raw data → insights → dashboard**. It demonstrates strong capabilities in:

* Data preprocessing
* SQL analysis
* BI visualization
* Insight storytelling
* Business recommendation generation

This dashboard assists businesses in optimizing marketing campaigns, improving customer retention, and increasing revenue through actionable data insights.

---

If you like this project, feel free to ⭐ star the repository on GitHub!
