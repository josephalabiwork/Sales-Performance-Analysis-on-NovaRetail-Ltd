# Sales-Performance-Analysis-on-NovaRetail-Ltd.
A Python-based data analysis project showcasing data cleaning with Pandas and insightful visualizations using Matplotlib.
## INTRODUCTION
This report presents the analysis of NovaRetail Ltd.’s sales data to understand sales performance across four Nigerian cities.
 The analysis focuses on total revenue, product categories, customer behavior, and sales trends to support better business decisions.
 Company Name: Nova Retail Ltd.
Nature of Business: Sales of electronics, appliances, and accessories.
Business Goal:
To identify sales trends, top-performing categories, customer patterns, and areas to improve profitability by analysing historical sales data.
This data contains 110 transactions across 11 columns
Each record represents a single transaction with the following fields: 

Column                                                                Description
TransactionID                  Unique identifier for each sale
Date                                             Date of transaction
City                                               City where the sale occurred
CustomerID                Unique identifier for each customer
Customer Type        Indicates customer New or Returning
Category                     Product category (Electronics, etc)
Units Sold                               Number of units sold
Unit Price                                   Price per unit
Revenue                  Total revenue from the transaction
Discount                 Discount amount applied
SalesRep                    Name of the sales representative 
Key data cleaning and preparation steps included:
	•	Checked and confirmed no null values or duplicates.
	•	Converted Date column to proper datetime format.
	•	Verified that numerical fields (Units Sold, Unit Price, Revenue, Discount) contained valid values.
	•	Created Month column derived from Date for monthly trend analysis.
	•	Calculated Total After Discount = Revenue - Discount for net revenue.
 During the EDA stage, several aspects of the data were explored:
		Basic Statistics:
	•	Minimum revenue: ₦5,000
	•	Maximum revenue: ₦972,000
	•	Average revenue: approximately ₦268,373
           •        Total revenue:  ₦29,521,000
            •        Unique customers:  77

## SALES DISTRIBUTION:
Lagos recorded the highest transaction frequency and revenue, followed by Abuja, Kano, and Port Harcourt.
	•	Customer Behaviour:
Returning customers contributed a larger portion of total revenue compared to new customers.
	•	Monthly Trends:
         Sales peaked in September 2024
	•	Outliers:
A few high-revenue transactions in Lagos (₦250,000 and above) significantly influenced the total revenue.
 •  Bar chart showing total revenue by city with  Lagos as the state with the most revenue.
• Pie chart showing new vs returning customers with returning customers contributing more to the total revenue.
• Bar chart showing top product categories by revenue with electronics as the best product category in this dataset.
 • Bar chart showing sales rep performance with Abdul Salim as the best sales rep
•  Bar chart showing average revenue per customer by city with Lagos topping the chart as the best state by average revenue per customers which also shows that customers spent highest in Lagos
•   The business generated nearly ₦30 million in total revenue with strong customer diversity (77 customers), but discounts remained moderate, suggesting controlled pricing.
•   Lagos is the top-performing city, contributing significantly to total revenue. Abuja shows solid accessory sales, while Port Harcourt contributes less to total income — excluding it reduces revenue by roughly ₦6.96M.
•  Returning customers generate ~59% of total revenue, showing strong retention. However, there’s still growth potential in acquiring and converting new customers.
•  Electronics dominate sales, driving 65% of total revenue. This category likely represents the core business value, emphasizing its profitability.
•  Sales peaked in September 2024, indicating a seasonal demand increase in Q3. February and mid-year months show stable but moderate performance.
•  Abdul Salim leads significantly in revenue generation, suggesting strong client relationships or coverage of key cities.
•  The company’s main strength lies in high-value Electronics sales and repeat customer retention.
 • Total Revenue: ₦29.52 million generated across 110 transactions.
•  Customer Base: 77 distinct customers, with 23 making repeat purchases.
• Top City: Lagos led with ₦9.29 million in revenue — the strongest regional performer.
•  Customer Type Split:
•	Returning customers: ₦17.49 million (≈59% of total)
•	New customers: ₦12.03 million (≈41% of total)
•  Top Product Category: Electronics, contributing ₦19.15 million (≈65% of total revenue).
•  Peak Month: September 2024 recorded the highest revenue (₦4.74 million).
•  Top Sales Rep: Abdul Salim, generating ₦10.59 million — the most successful salesperson.
Strengthen Customer Retention
•	Since returning customers generate ~59% of total revenue, continue to build loyalty through:
o	Reward programs or referral bonuses.
o	Personalized offers based on past purchases.
o	Follow-up communication to encourage repeat buying.
________________________________________
 Expand New Customer Acquisition
•	New customers contribute only 41% of revenue — a sign that marketing and outreach can grow.
o	Increase digital and in-store promotions in underperforming cities.
o	Target campaigns for new buyers in Abuja and Port Harcourt.
o	Offer first-time purchase discounts or bundle deals to attract fresh customers.
________________________________________
 Focus on High-Value Products
•	Electronics dominate (₦19.15M revenue) — indicating strong demand and profitability.
o	Continue prioritizing Electronics marketing and stock availability.
o	Introduce related upsell items (e.g., warranties, accessories, installation services).
o	Monitor for overreliance; diversify into high-performing subcategories within Electronics.
________________________________________
 Leverage Lagos’ Market Strength
•	Lagos leads in sales (₦9.29M total, ₦2.56M from new customers).
o	Deepen engagement in Lagos with local partnerships or exclusive promotions.
o	Study Lagos buying trends to replicate success in other cities like Kano or Abuja.
________________________________________
 Support Underperforming Regions
•	Port Harcourt’s revenue impact is small — excluding it barely changes overall revenue.
o	Reassess marketing efforts and product mix in that region.
o	Consider optimizing logistics or relocating resources to stronger zones if profitability is low.
________________________________________
 Incentivize Top Sales Reps
•	Abdul Salim is the leading sales performer (₦10.59M).
o	Use his strategy as a benchmark for training others.
o	Implement performance-based incentives and recognition programs.
o	Pair high and mid-performing reps to share best practices.
________________________________________
Monitor Seasonal Sales Patterns
•	Peak revenue in September 2024 suggests possible seasonal demand.
o	Plan promotions and stock levels around that period.
o	Analyze low-performing months to identify reasons (e.g., stock issues, reduced marketing).

10. ## CONCLUSION

The analysis reveals that the business is performing well overall, with ₦29.52 million in total revenue and strong customer engagement across major cities. Lagos stands out as the leading market, while Electronics remain the key revenue driver, contributing the majority of total sales.
Returning customers account for most of the income, highlighting good customer loyalty and satisfaction, though there is room to attract more new customers through targeted marketing. Sales performance is led by Abdul Salim, whose strategies could be replicated to improve team-wide results.




