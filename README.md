# 📊 Retail Profit Churn Analysis using RFM Framework

## 📌 Project Overview

This project focuses on analyzing retail transaction data to identify high-value customers, measure profitability concentration, and quantify customer churn risk using an RFM (Recency, Frequency, Monetary) based analytical framework.

The project combines customer segmentation, Pareto analysis, profitability analysis, and churn risk assessment to support data-driven business decision-making and customer retention strategy development.

---
https://public.tableau.com/app/profile/shilpi.kumari7067/viz/Retail_profit/Dashboard1?publish=yes

# 🎯 Business Problem

Retail businesses often prioritize revenue growth without fully understanding:

- Which customers contribute most of the profit
- How profit is concentrated across customer segments
- How vulnerable the business is to customer churn
- Which customer groups require strategic retention focus

As a result, organizations may:
- Spend retention budgets inefficiently
- Ignore high-profit inactive customers
- Make weak revenue-centric decisions

This project addresses these challenges through structured business analytics and financial risk modeling.

---

# 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Tableau
- Jupyter Notebook

---

# 📂 Project Workflow

1. Data Collection  
2. Data Cleaning & Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. RFM Feature Engineering  
5. Revenue & Profit Concentration Analysis  
6. Churn Risk Quantification  
7. Tableau Dashboard Development  
8. Strategic Recommendation Generation  

---

# 📊 Key Analysis & Results

## 1️⃣ Revenue Concentration Analysis

Using Pareto Analysis, customers were ranked based on total revenue contribution.

### Key Finding:
Top 20% of customers contribute approximately **48% of total revenue**, indicating moderate revenue concentration.

<img src="images/Total Revenue.png" width="700">

---

## 2️⃣ Profit Concentration Analysis

Profit concentration was evaluated separately to understand profitability dependency.

### Key Finding:
Top 20% of customers contribute approximately **81% of total profit**, revealing strong dependency on a relatively small customer segment.

<img src="images/Total Profit.png" width="700">

---

## 3️⃣ RFM Customer Segmentation

Customers were segmented using:

- **Recency** → Days since last purchase
- **Frequency** → Number of unique purchases
- **Monetary** → Total customer spending

<img src="images/RFM Table.png" width="700">

---

## 4️⃣ Recency Distribution Analysis

Recency analysis was performed to identify inactive customers and evaluate churn behavior patterns.



## 5️⃣ Churn Risk Assessment

A statistically calibrated churn threshold was defined using the 75th percentile of Recency (>183 days).

### Key Finding:
Approximately **17–18% of total profit** is exposed to churn risk from high-value inactive customers.

# 📈 Tableau Dashboard

An interactive Tableau dashboard was developed to visualize:

- Sales Trends
- Profit Distribution
- KPI Metrics
- Regional Performance
- Customer Segmentation
- Category-wise Sales

# 🧠 Strategic Insights

- Profit concentration is significantly higher than revenue concentration.
- A small customer segment drives most company profitability.
- Revenue alone is not a reliable indicator of business value.
- Customer inactivity should be analyzed using data-driven thresholds.
- Blanket discount strategies may reduce profit margins.

# 💡 Strategic Recommendations

- Prioritize retention of high-value inactive customers
- Implement personalized engagement campaigns
- Focus on profitability-based segmentation
- Evaluate retention ROI before campaign execution
- Monitor customer behavior continuously using dashboards

# 📌 Business Impact

This project demonstrates how business analytics and customer segmentation can help organizations:

- Reduce churn exposure
- Improve customer retention strategy
- Protect high-profit customer relationships
- Support executive-level business decisions
- Improve long-term profitability

# 🚀 Future Enhancements

- Machine Learning based churn prediction
- Customer Lifetime Value (CLV) modeling
- Real-time dashboard integration
- Automated retention recommendation system

---

# 👤 Author

**Shilpi Kumari**  
B.Tech Computer Science Engineering  
Aspiring Data & Business Analytics Professional  

Focused on:
- Data Analytics
- Business Intelligence
- Customer Analytics
- Data Visualization

---

# ⭐ If You Like This Project

Feel free to:
- Star this repository
- Fork the project
- Connect for collaboration
