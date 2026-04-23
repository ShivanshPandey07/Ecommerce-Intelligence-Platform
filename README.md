# 🛒 E-Commerce Intelligence Platform

![Python](https://img.shields.io/badge/Python-3.11-blue)
![SQL](https://img.shields.io/badge/SQL-SQLite-orange)
![Tableau](https://img.shields.io/badge/Tableau-Public-lightblue)
![Status](https://img.shields.io/badge/Status-Complete-green)

## 📌 Project Overview

A full end-to-end data analytics project analyzing **100,000+ real e-commerce orders** from Olist, Brazil's largest e-commerce platform. This project simulates the work of a data analyst at Amazon, Google, or Microsoft — from raw data to executive dashboard.

**Business Problem:** An e-commerce company is losing revenue and doesn't know why. Using data, we identify the root causes and provide actionable recommendations.

---

## 🔗 Live Dashboard

👉 [View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/shivansh.pandey1813/viz/EcommerceIntelligenceDashboard_17769399911110/EcommerceIntelligenceDashboard)

---

## 📊 Key Findings

| Metric | Value |
|---|---|
| Total Orders Analyzed | 96,470+ |
| Total Revenue | R$ 19.7 Million |
| Overall Churn Rate | ~68% |
| Average Review Score | 4.09 / 5 |
| Late Delivery Rate | ~10-24% by state |
| Top Category | Bed Bath Table |

---

## 🧩 Project Structure
ecommerce-intelligence-platform/
│
├── data/
│   ├── raw/              ← Original Olist dataset (9 CSV files)
│   ├── processed/        ← Cleaned & engineered datasets
│   └── final/            ← Final Tableau-ready dataset
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_sql_analysis.ipynb
│   ├── 04_rfm_segmentation.ipynb
│   ├── 05_churn_analysis.ipynb
│   └── 06_tableau_prep.ipynb
│
├── dashboard/            ← Tableau workbook
├── reports/              ← Charts & findings
└── README.md

---

## 🔍 Project Phases

### Phase 1 — Data Exploration
- Loaded and explored all 9 datasets
- Analyzed 100K+ orders across customers, products, sellers
- Identified key patterns in order volume and status distribution

### Phase 2 — Data Cleaning
- Fixed missing values, data types, duplicates
- Engineered new features: delivery days, is_late, days_diff
- Built master dataset merging all 9 tables

### Phase 3 — SQL Analysis
- Answered 7 key business questions using SQLite
- Monthly revenue trend, top categories, late delivery by state
- Customer repeat rate, review score impact, seller performance

### Phase 4 — RFM Customer Segmentation
- Built RFM model (Recency, Frequency, Monetary)
- Segmented 93,000+ customers into 9 behavioral groups
- Identified Champions, At Risk, Lost and more

### Phase 5 — Churn & Root Cause Analysis
- Defined churn as no purchase in 180 days
- Identified 3 root causes: late deliveries, low reviews, low spend
- Used statistical hypothesis testing (t-test) to validate findings

### Phase 6 — Tableau Dashboard
- Built 6-sheet interactive executive dashboard
- Revenue trends, category performance, delivery heatmap
- Customer segmentation and churn overview

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3.11 | Data cleaning, analysis, modeling |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | RFM scoring |
| SQLite + SQL | Business queries |
| Tableau Public | Executive dashboard |
| Git & GitHub | Version control |

---

## 💡 Business Recommendations

1. **Improve last-mile delivery** in AL, MA, SE states which have 20%+ late rates
2. **Immediately follow up** with customers who give 1-2 star reviews
3. **Create loyalty programs** targeting low-spend first-time customers
4. **Reactivation campaigns** for the 15,000+ At Risk customers
5. **Double down** on Bed Bath Table and Health Beauty categories

---

## 📁 Dataset

**Source:** [Brazilian E-Commerce (Olist) — Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)  
**Size:** 100,000+ orders | 9 tables | 2016–2018

---

## 👤 Author

**Shivansh Pandey**  
Aspiring Data Analyst | Python • SQL • Tableau  
[GitHub](https://github.com/ShivanshPandey07) | [Tableau Public](https://public.tableau.com/app/profile/shivansh.pandey1813/viz/EcommerceIntelligenceDashboard_17769399911110/EcommerceIntelligenceDashboard?publish=yes)