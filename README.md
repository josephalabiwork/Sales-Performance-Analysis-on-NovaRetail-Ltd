# Sales-Performance-Analysis-on-NovaRetail-Ltd.
A Python-based data analysis project showcasing data cleaning with Pandas and insightful visualizations using Matplotlib.
## 📘 Introduction
This report presents the analysis of **NovaRetail Ltd.’s** sales data to understand overall sales performance across four major Nigerian cities.  
The analysis focuses on **total revenue, product categories, customer behavior, and sales trends** to support better data-driven decision-making and improve business performance.
 ## 🏢 Business Understanding
**Company Name:** Nova Retail Ltd.  
**Nature of Business:** Sales of electronics, appliances, and accessories.  
**Business Goal:** To identify sales trends, top-performing product categories, customer behavior patterns, and areas to improve profitability by analyzing historical sales data.
## 🧹 Data Preparation
Key data cleaning and preparation steps included:
- Checked and confirmed **no null values or duplicate records** were present.  
- Converted the **Date** column to a proper datetime format.  
- Verified that numerical fields — **Units Sold**, **Unit Price**, **Revenue**, and **Discount** — contained valid values.  
- Created a **Month** column derived from the Date field for monthly trend analysis.  
- Calculated **Total After Discount = Revenue - Discount** to determine net revenue.  
- Verified the **average revenue per transaction** was approximately **₦268,373**.
## 🔍 Exploratory Data Analysis (EDA)
During the EDA stage, several key aspects of the dataset were explored to understand its structure and underlying patterns.
**Basic Statistics:**  
- **Minimum Revenue:** ₦5,000  
- **Maximum Revenue:** ₦972,000  
- **Average Revenue:** ≈ ₦268,373  
- **Total Revenue:** ₦29,521,000  
- **Unique Customers:** 77  
## 📦 Sales Distribution
- **Lagos** recorded the highest transaction frequency and revenue, followed by **Kano**, **Port Harcourt**, and **Abuja**.  
- **Customer Behaviour:** Returning customers contributed a larger portion of total revenue compared to new customers.  
- **Monthly Trends:** Sales peaked in **September 2024**.  
- **Outliers:** A few high-revenue transactions in Lagos (₦250,000 and above) significantly influenced the total revenue.
## 📈 Analysis & Key Insights
- **Total Revenue:** ₦29,521,000 generated across all cities.  
- **Top City:** Lagos contributed the highest share of revenue.  
- **Peak Month:** September 2024 recorded the highest monthly sales.  
**Customer Insights:**  
- Total number of distinct customers: **77**  
- Returning customers generated more consistent sales  
- **23** customers made repeat purchases  
## 🛍️ Product Insights
- The most popular product category by sales volume was **Electronics**.  
- **Electronics** generated the highest total revenue.  
- **Average revenue per unit (Electronics):** ₦156,959.02  
## 👥 Sales Representative Insights
- **Top Performer:** Abdul Salim — highest total revenue among all sales reps.  
- **Average Units Sold per Sales Rep:**  
  - Abdul Salim — 3.35  
  - Chuka Obazi — 3.44  
  - Mary Felix — 2.97  
- **Total Discount Given Across All Sales:** ₦357,300
## SUMMARY OF FINDINGS
- **Total Revenue:** ₦29.52 million generated across 110 transactions.  
- **Customer Base:** 77 distinct customers, with 23 making repeat purchases.  
- **Top City:** Lagos led with ₦9.29 million in revenue — the strongest regional performer.  
- **Customer Type Split:**  
  - Returning customers: ₦17.49 million (≈59% of total)  
  - New customers: ₦12.03 million (≈41% of total)  
- **Top Product Category:** Electronics contributed ₦19.15 million (≈65% of total revenue).  
- **Peak Month:** September 2024 recorded the highest revenue at ₦4.74 million.  
- **Top Sales Representative:** Abdul Salim generated ₦10.59 million — the most successful salesperson.
## 💡 Recommendations
Actionable steps NovaRetail can take based on the findings:
- **Replicate the September playbook:** Conduct a retroactive campaign analysis for September (promotions, stock levels, and channel mix) and replicate the most successful tactics.
- **Invest in Lagos and Abuja market penetration:** Lagos contributes ~31.5% of total revenue — prioritize marketing and inventory there. Abuja shows strong accessories volume, so focus on targeted promotions for that category.
- **Focus on retention programs:** Returning customers generate ~59% of revenue. Implement loyalty programs, repeat-purchase incentives, and personalized offers to increase customer lifetime value.
- **Leverage top sales reps:** Analyze Abdul Salim’s performance strategies (accounts, leads, pricing, negotiation) and share best practices through mentorship or adjusted commission structures. Introduce incentives for mid-tier sales reps.
- **Optimize discount strategy:** The average discount per transaction (₦3,248) and total discount (₦357,300) are reasonable. Monitor margin impact during promotional months and favor targeted couponing over blanket discounts.
- **Prioritize high-margin inventory:** Since electronics drive the highest revenue per unit, ensure consistent stock availability, offer warranty bundles, and promote premium service add-ons.
- **Encourage repeat purchases among one-time buyers:** Convert one-time customers (~70% of total) using follow-up offers, cross-sell campaigns, and small loyalty rewards.
- **Investigate Port Harcourt performance:** Since excluding Port Harcourt significantly impacts total revenue, review operations, returns, and delivery times in that city to optimize logistics and marketing spend.
- ## ✅ Conclusion
The analysis reveals that **NovaRetail Ltd.** is performing well overall, generating a total revenue of **₦29.52 million** with strong customer engagement across major cities.  
**Lagos** stands out as the leading market, while **Electronics** remain the primary revenue driver, contributing the majority of total sales.  
**Returning customers** account for most of the income, reflecting strong loyalty and satisfaction, though there is still room to attract more **new customers** through targeted marketing strategies.  
Sales performance is led by **Abdul Salim**, whose approach and techniques could be replicated to enhance overall team results.


 







