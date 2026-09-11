# 📊 Quantium Retail Analytics Suite

A 2-page executive Power BI dashboard built on the QVI retail transaction dataset, 
designed to deliver customer insights and evaluate the impact of a retail trial 
strategy using statistical control-store matching. 🎯

## 🔍 Overview
This project analyzes retail transaction data to:
1️⃣ Provide executive-level business insights 
2️⃣ Measure the effectiveness of a store trial strategy against matched control stores

## 🗂️ Data & Modeling
- 📁 Source: QVI_data.csv (retail transaction dataset)
- 🧹 Cleaned and transformed using Power Query
- ⭐ Star schema design: Fact_Transactions, Dim_Customer, Dim_Date (DAX-generated)

## 📈 Page 1: Executive Overview & Customer Insights
- 💰 KPIs: Total Revenue ($1.93M) | Total Customers (73K) | Total Transactions (263K) 
  | Units Sold (505K) | Avg Transaction Value ($7.35)
- 📉 Total Revenue Trend over time
- 🏆 Top 7 Products by Revenue
- 👥 Customer Segmentation by Lifestage
- 💎 Revenue Contribution by Premium Customer Tier (Mainstream/Budget/Premium)

## 🧪 Page 2: Trial Store Analysis & Recommendations
- 🔗 Identified control stores using Pearson correlation on pre-trial monthly sales 
  patterns (Trial 77 → Control 71 | Trial 86 → Control 155 | Trial 88 → Control 159)
- 📊 KPIs: Revenue Uplift (+33.3%) | Customer Uplift (+80.0%) | Transaction Uplift (+21.2%)
- ⚖️ Pre-Trial vs Trial Revenue Comparison
- 🗃️ Store-Level Performance & Uplift Breakdown
- 📅 Weekly Revenue Uplift Trend (Trial vs Control)
- ✅ Executive Recommendations for trial rollout

## 🛠️ Tools & Skills
Power BI DAX Power Query Data Modeling Star Schema 
Statistical Analysis (Pearson Correlation) A/B Testing Methodology

## 💡 Key Insight
Trial stores showed strong, consistent uplift over matched control stores across 
revenue, customer visits, and transaction frequency — supporting a recommendation 
to extend the trial strategy to additional stores. 🚀

📷 Screenshots
🔗 
