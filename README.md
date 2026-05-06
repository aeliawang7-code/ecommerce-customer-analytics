# E-commerce Customer Analytics Dashboard (RFM Analysis)

## 📌 Overview
This project analyzes customer behavior and revenue trends using an e-commerce dataset (~500K transactions).

It applies RFM (Recency, Frequency, Monetary) segmentation to identify high-value customers, churn risks, and growth opportunities, and translates insights into actionable business strategies.


---

## 🚀 Key Highlights
- Processed and analyzed **500K+ transaction records** using SQL and Python  
- Built **RFM-based customer segmentation model** to classify users into 6 segments  
- Developed an **interactive Tableau dashboard** to visualize revenue trends and customer behavior  
- Identified **churn risk as the largest customer group**, highlighting major retention opportunities  


---

## 🛠 Tech Stack
- **SQL** – data extraction & transformation  
- **Python (Pandas, NumPy)** – data cleaning & feature engineering  
- **Tableau** – data visualization & dashboard design

---

## 📊 Key Analysis

### 1. Revenue Trend Analysis
- Analyzed monthly revenue patterns
- Identified strong seasonality with peak performance in **Q4**

### 2. Customer Segmentation (RFM)
Customers were segmented into:
- VIP
- Loyal
- At Risk
- Churn Risk
- Regular
- Potential Loyalist

---

## 📈 Dashboard

![Dashboard](Dashboard/tableau_dashboard.png)

📌 *Tableau Public Link Here:* 
1. Dashboard: https://public.tableau.com/app/profile/aelia.wang/viz/EcommerceCustomerAnalytics/Dashboard1?publish=yes
2. Monthly Revenue Trends: https://public.tableau.com/app/profile/aelia.wang/viz/MonthlyRevenueTrend_17781028333990/MonthlyRevenueTrend?publish=yes
3. Customer Segment Distribution: https://public.tableau.com/app/profile/aelia.wang/viz/CustomerSegmentDistribution_17781026288330/CustomerSegmentDistribution?publish=yes
4. Average Revenue by Customer Segment: https://public.tableau.com/app/profile/aelia.wang/viz/AverageRevenuebyCustomerSegment/AverageRevenuebyCustomerSegment?publish=yes
---


## 💡 Key Insights
- Revenue peaks in Q4, indicating seasonal demand
- Churn-risk customers represent the largest segment → major retention opportunity
- VIP customers generate significantly higher revenue per user

---

## 🚀 Strategic Recommendations

### 1. Retention Strategy (Churn Risk & At Risk)
- Launch targeted email campaigns and personalized discounts
- Re-engage inactive customers through limited-time offers

### 2. Growth Strategy (Loyal Customers)
- Prioritize Loyal customers as the main upgrade target
- Introduce loyalty programs and tiered rewards to convert them into VIP

### 3. Revenue Optimization (VIP Customers)
- Maintain VIP engagement through exclusive benefits
- Offer early access and premium services to maximize lifetime value

---

## 📂 Project Structure
```
ecommerce-customer-analytics
│
├── data                   # Raw dataset
├── Notebooks              # RFM analysis
├── Outputs                # Processed data
├── Dashboard              # Tableau files & screenshots
└── README.md
```

