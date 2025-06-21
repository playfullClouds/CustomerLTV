# CustomerLTV

# 📊 Analyzing the Impact of Returns on Customer Lifetime Value (LTV)

Welcome to the official repository for the **Customer LTV Analytics Project**, a comprehensive SQL and Power BI-based analysis that explores how product returns impact Customer Lifetime Value (LTV). This project dives into six core business objectives using advanced SQL queries, structured business logic, and visual storytelling via Power BI.

---

## 🚀 Project Overview

This analysis investigates the nuanced relationship between product returns and customer value. Instead of assuming returns are always detrimental, the project breaks down patterns across segments, product categories, demographics, and payment methods. The findings inform smarter customer retention and product strategy decisions.

---

## 🎯 Project Objectives

1. **How do returns affect total Customer Lifetime Value (LTV)?**
2. **Which product categories have the highest return rates and how do they impact revenue and LTV?**
3. **Are specific customer demographics (age, gender) associated with higher return rates and lower LTV?**
4. **Is there a correlation between return frequency and customer churn?**
5. **Do payment methods affect the likelihood of returns and their influence on LTV?**
6. **How can we use return data to develop customer retention strategies?**



## 🧰 Tools & Technologies

- **SQL**: Core language used for data cleaning, transformation, cohort creation, and deriving metrics.
- **Power BI**: Used to design professional, dynamic dashboards and visualizations aligned with each objective.
- **Python**: Used only for downloading the dataset from Kaggle using the Kaggle API.

---

## 🗃️ Dataset

The project uses a Kaggle dataset simulating retail customer behavior [here](https://www.kaggle.com/datasets/shriyashjagtap/e-commerce-customer-for-behavior-analysis). Key tables include:
- `Customer_ID`, `Purchase_Date`, `Product_Category`, `Payment_Method`, `Purchase_Amount`, `Returns`, `Gender`, `Age`

Derived fields include:
- `Adjusted_LTV`, `Return_Rate`, `Churned`, `Customer_Segment`, `ReturnCohort`, and more.

---

## 📊 Visualizations

Each objective features multiple Power BI visuals for data storytelling, including:
- **Scatter plots**: Return Rate vs Adjusted LTV
- **Bar charts**: Category-wise Return Rates
- **Line charts**: Monthly Revenue vs Adjusted Revenue
- **Histograms**: Return Distribution across Demographics
- **Donut + KPI cards**: Global Revenue vs Return Impact
- **Heatmaps and stacked visuals** for retention strategy breakdowns

All visuals are interactive and were created in Power BI Desktop.

---

