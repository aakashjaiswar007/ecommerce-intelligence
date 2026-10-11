# 🛒 AI-Powered E-commerce Intelligence System
> End-to-end data analytics project on 1M+ real UK retail transactions — combining Python, machine learning, AI APIs, and Power BI to surface actionable business insights from raw transactional data.

---

## 📌 Project Overview

This project analyses over **1 million UK e-commerce transactions** from a real gift shop dataset (2009–2011). The goal was to go beyond basic reporting — using multiple AI and machine learning techniques to clean, segment, detect anomalies, forecast revenue, and automatically generate executive-level business insights.

The entire pipeline runs from raw messy data all the way to an interactive Power BI executive dashboard, simulating a real-world end-to-end analytics workflow.

---

## 🔍 What This Project Does

**Data Cleaning & Sentiment Analysis**
Cleaned 779,000+ transactions from 1.06M raw rows — removing cancellations, guest orders, and zero-price entries. Applied VADER AI sentiment analysis to 5,086 unique product descriptions, finding that positively-framed product names generate measurably higher average revenue than negatively-described ones across 41 countries.

**Customer Segmentation**
Used K-Means clustering (K=4) to segment 5,878 customers into four behavioural tiers — Champions, Loyalists, At-Risk, and Lost — based on Recency, Frequency, and Monetary (RFM) values. Discovered that just 17.4% of customers (Champions) drive 73.2% of total revenue, a classic Pareto pattern with direct implications for retention strategy.

**Anomaly Detection**
Deployed Isolation Forest to automatically scan all 779K transactions and flag 15,541 suspicious orders worth £4.9M — categorised as bulk orders, high-price anomalies, and near-zero price entries. This step replaces what would take a human analyst days of manual review.

**Revenue Forecasting**
Trained Meta's Prophet AI model on 23 months of cleaned transaction data to forecast Q1 2012 revenue at £1.97M (95% confidence interval: £1.4M–£2.5M). The model also identified November as the peak season (+42% above baseline) and January–February as the slowest months — directly informing inventory and marketing planning.

**AI Insight Generation**
Integrated the Gemini AI API to automatically generate professional executive-level business insights from the analysis output — simulating an AI-augmented analytics workflow where the analyst handles the numbers and AI writes the business narrative.

**Executive Dashboard**
Built a 2-page interactive Power BI dashboard with DAX measures, KPI cards, segment visuals, anomaly flags, and a revenue trend + forecast chart — designed for a Monday morning executive review.

---

## 📊 Key Findings

| Finding | Number |
|---------|--------|
| Total revenue analysed | £17.37M |
| Transactions cleaned | 779,425 (from 1.06M raw) |
| Unique customers | 5,878 across 41 countries |
| Champion customers → revenue share | 17.4% of customers = 73.2% of revenue |
| Anomalous orders flagged by AI | 15,541 orders worth £4.9M |
| Q1 2012 revenue forecast | £1.97M (Prophet AI) |
| Positive sentiment uplift | Positive products outperform negative in avg revenue |

---

## 🔧 Tech Stack

| Area | Tools |
|------|-------|
| Data cleaning & EDA | Python, Pandas, NumPy, Matplotlib, Seaborn |
| NLP & Sentiment | VADER (vaderSentiment) |
| Machine Learning | Scikit-learn (K-Means, Isolation Forest) |
| Forecasting | Meta Prophet |
| AI API | Google Gemini API |
| Dashboard | Power BI, DAX |
| Environment | Jupyter Notebook, Anaconda |

---

## 📥 Dataset

The raw dataset is not included in this repo due to file size.

**Download here:** [UCI Online Retail II Dataset](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

---

## 👤 Author

**Aakash Jaiswar**
📧 aakashjaiswar007@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/aakash-jaiswar)
🐙 [GitHub](https://github.com/aakashjaiswar007)
