# 📊 Product Analytics Dashboard – Power BI Project

This is a self-built Power BI project that analyzes product performance using real business metrics and consulting principles. I created this project independently to deepen my skills in DAX, business thinking, and dashboard storytelling. It explores how customer behavior, revenue trends, and product dynamics influence strategic decisions.

 PPT: https://github.com/06-10-2004/product-analytics-Powerbi-dashboard/raw/refs/heads/main/compressed_From-Data-to-Decisions-A-Product-Analytics-Journey%20(1).pptx
 LINKEDIN: https://www.linkedin.com/in/haritha-s-15599a31a/
---

## 🧠 1. Background and Overview

As a data analyst, I realized that simply showing charts isn’t enough — what matters is how data connects to real business outcomes. In this project, I wanted to move beyond basic dashboards and focus on **business questions** like:

- Which products drive the most value?
- Where should we invest next?
- How are our users behaving over time?

To do this, I used **Power BI and DAX** to track core product metrics such as **engagement**, **churn**, **retention**, **funnel conversion**, and **ROI**. I also applied a **consulting mindset** learned through the PwC Virtual Internship to structure the analysis into actionable insights.

---

## 🗂️ 2. Data Structure Overview

The dataset represents **e-commerce transactional data** and includes:

| Field | Description |
|-------|-------------|
| `User_Name` | Unique customer identifier |
| `Purchase_Amount` | Transaction amount |
| `Country`, `Age`, `Product_Category` | Customer attributes |
| `Transaction_Date` | Date of purchase |
| Derived columns using DAX | First Purchase Date, Repeat Flag, Churn, Retention, ROI metrics |

Metrics are computed using DAX to analyze **behavior over time**, **repeat purchase patterns**, and **conversion flows**.

---

## 📌 3. Executive Summary

This Power BI dashboard answers key business questions like:

- 🔄 How are customer retention and churn trending?
- 📈 What’s the average revenue per customer?
- 📊 Which products perform best/worst across segments?
- 🌍 Which regions offer growth opportunities?

**Outcome**: The dashboard helps stakeholders make **data-backed decisions** on product investment, marketing focus, and customer targeting.

---

## 🔍 4. Insights Deep Dive

### 1. 🛍️ Best and Worst Product Performance
- **Metric**: Total Sales, Customer Count, Repeat Rate
- **Insight**: Product A led in revenue (₹4.2M), but Product D had the highest churn (35%).
- **Story**: Product A retained repeat users, while Product D had high drop-off post first purchase.

### 2. 📆 Monthly & Category Trends
- **Metric**: Monthly Sales Trend by Category
- **Insight**: Category X peaked in Q2, showing a 22% MoM growth, while Category Z declined consistently.
- **Story**: Seasonal demand drove spikes; some categories may need repositioning.

### 3. 🌍 Regional Revenue Contribution
- **Metric**: Sales and Churn by Country
- **Insight**: Region B generated ₹1.9M with only 8% churn; Region C had 22% churn.
- **Story**: Region B is a strong candidate for product push and customer loyalty campaigns.

### 4. 🔁 Retention & Churn
- **Metric**: Retention Rate, Churn %
- **Insight**: Overall retention = 47%, churn highest in 18–25 age group.
- **Story**: Younger users are harder to retain — consider onboarding or personalized campaigns.

### 5. 💸 ROI & Revenue Per Customer
- **Metric**: Avg Revenue Per Customer = ₹251.58k
- **Insight**: High revenue from repeat buyers; one-time users generate low lifetime value.
- **Story**: Focused retention programs could boost profitability.

---

## 💡 5. Business Recommendations

- 📦 **Optimize Category Z**: Revisit product mix or marketing for underperforming category.
- 🌍 **Double Down on Region B**: Strong performance and loyalty — expand targeting there.
- 🔁 **Retention Campaigns**: Personalized campaigns for 18–25 age group to reduce churn.
- 📈 **Focus on Repeat Buyers**: Maximize ROI by nurturing repeat customers.

---

## ⚠️ Caveats and Assumptions

- ROI is based only on revenue; no cost data was available.
- Churn is defined as no purchase within 30+ days —
