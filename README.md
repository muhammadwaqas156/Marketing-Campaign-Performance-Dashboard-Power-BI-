# 📊 Marketing Campaign Performance Dashboard (Power BI)

## 📌 Project Overview
This project analyzes marketing campaign performance using Power BI. The goal is to identify high-performing campaigns, evaluate customer segments, and understand the impact of discounts and marketing strategies on profitability.

The dashboard provides insights into key metrics such as revenue, ROI, conversions, and customer behavior to support data-driven decision-making.

---

## 🎯 Objectives
- Analyze campaign performance using ROI, Revenue, Profit, and Conversion Rate
- Identify top-performing and underperforming campaigns
- Evaluate the effectiveness of discount strategies
- Understand customer segmentation (Basic, Standard, Premium)
- Discover which marketing keywords drive better results

---

## 🧹 Data Preparation
Data cleaning and transformation were performed using Power Query:

- Removed duplicates and handled missing values
- Corrected data types (numeric and categorical)
- Standardized categorical values (Subscription Tier, Keywords)
- Validated business rules (Conversions ≤ Clicks)
- Created meaningful campaign names for better readability

---

## ⚙️ Feature Engineering
The following calculated columns and measures were created:

- **Conversion Rate** = Conversions / Clicks  
- **Cost Per Click (CPC)** = Budget / Clicks  
- **Revenue per Conversion** = Revenue / Conversions  
- **Profit** = Revenue - Budget  
- **Performance Category** = High / Medium / Low (based on ROI)  

---

## 📊 Dashboard Structure

### 📄 Page 1: Overview
- KPI Cards: Total Revenue, Profit, ROI, Conversions, Conversion Rate  
- ROI by Campaign  
- Revenue vs Budget (Scatter Plot)  
- Profit by Discount Level  
- Revenue by Keywords  
- Conversion Rate by Subscription Tier  

---

### 📄 Page 2: Campaign Analysis
- Top 5 and Bottom 5 Campaigns (based on ROI)  
- Conversions vs Clicks (Efficiency Analysis)  
- ROI Distribution  
- Detailed Campaign Table with conditional formatting  

---

### 📄 Page 3: Customer Insights
- Revenue, Profit, and Conversion Rate by Subscription Tier  
- Revenue by Keywords  
- Discount vs Profit Analysis  
- Units Sold vs Revenue (Scatter Plot)  

---

## 🔍 Key Insights
- High ROI campaigns are not always those with the highest conversions  
- Moderate discounts tend to generate better profitability  
- Customer segments behave differently in terms of revenue and ROI  
- Keywords like "Stylish" and "Innovative" perform better than generic terms  

---

## 🛠 Tools & Technologies
- Power BI (Dashboard & Visualization)  
- Power Query (Data Cleaning & Transformation)  
- DAX (Data Analysis Expressions)  

---

## 💼 Business Value
This dashboard helps:
- Identify profitable campaigns  
- Optimize marketing spend  
- Improve targeting strategies  
- Support data-driven decisions  

---

## 🚀 Future Improvements
- Add time-based analysis (monthly/quarterly trends)  
- Integrate real-time data sources  
- Apply forecasting models  

---

## 👤 Author
**Muhammad Waqas**  
MSc Advanced Computer Science | Data Analyst
