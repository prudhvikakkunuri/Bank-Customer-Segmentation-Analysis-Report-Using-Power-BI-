# 🧮 Bank Customer Segment & Risk Analysis – Power BI

This project is an end-to-end **Power BI dashboard** for analyzing **bank customer behavior, segmentation, and risk**.  
It transforms raw customer and transaction data into actionable insights for **marketing, risk management, and strategic decision-making**.

---

## 📊 Project Overview

- **Total Customers:** 836K  
- **Total Transactions:** 981K  
- **Total Revenue:** ₹1.41 Billion  
- **Average Transaction Amount:** ₹1.44K  
- **Maximum Transaction Amount:** ₹1.56M  
- **Average Customer Age:** 40.47 years  

The dashboard helps stakeholders understand **who their customers are, how they transact, which segments are most valuable, and where the risks lie.**

---

## 🔍 Key Insights

### 👥 Customer Demographics
- Gender distribution:
  - **Male:** 75.48%
  - **Female:** 24.52%
- Strong presence in major cities:
  - **Top locations:** Mumbai, New Delhi, Bangalore, Gurgaon
- Age distribution:
  - Average age of customers is **40.47 years**
  - Visual breakdown across age groups with gender splits

### 💳 Transactions & Revenue
- **Total transactions:** 981K  
- **Total revenue:** ₹1.41 Billion  
- **Average transaction:** ₹1.44K  
- **Maximum transaction:** ₹1.56M  
- Trend analysis of:
  - Daily transaction activity
  - Peak transaction times
  - Customer spending behavior over time

### 🧩 RFM-Based Customer Segmentation
Used **RFM (Recency, Frequency, Monetary)** model to segment customers into:
- **Champions**
- **Loyal Customers**
- **At Risk**
- **Lost**
- **New Customers**
- **Others**

Key findings:
- **Champions** generated the highest revenue: **₹561.76M**
- Segment-wise comparison of:
  - Average revenue per customer  
  - Transaction frequency  
  - Age group distribution within each segment  

### ⚠️ Risk & Credit Behavior
- Customers classified into **High, Medium, and Low Risk** based on:
  - **Credit score**
  - **Account balance**
  - **Transaction history**
- Visualizations show:
  - Credit score distribution across segments  
  - Relationship between **risk level and account balance**  
  - Identification of **top high-revenue but high-risk customers** for closer monitoring

---

## 🛠️ Features

- **Interactive Power BI dashboard** with slicers for:
  - Age group, gender, location, customer segment, risk level, date range, and transaction range
- **Drilldown & drillthrough analysis**:
  - From overall KPIs → segment-level → individual customer details
- **RFM-based segmentation**:
  - Automatically classifies customers into meaningful behavioral groups
- **Risk analysis module**:
  - Combines credit score, balance, and transaction metrics for risk profiling
- Visualizations for:
  - Age group distribution
  - Gender distribution
  - Geographic distribution
  - Transaction trends & revenue patterns
  - Segment-wise and risk-wise comparisons

---

## 🧱 Tech Stack

- **Power BI Desktop**
- **DAX** (Data Analysis Expressions) for:
  - RFM scoring
  - KPI calculations (revenue, frequency, averages, etc.)
  - Risk scoring logic
- **Data Sources**:
  - Customer master data (demographics, credit score, balances)
  - Transaction data (amounts, dates, times)
  - Segmentation & risk mapping tables (if applicable)
