# Sales-Performance-Analysis-on-NovaRetail-Ltd.
A Python-based data analysis project showcasing data cleaning with Pandas and insightful visualizations using Matplotlib.
## INTRODUCTION
This report presents the analysis of NovaRetail Ltd.’s sales data to understand sales performance across four Nigerian cities.
 The analysis focuses on total revenue, product categories, customer behavior, and sales trends to support better 
 ## BUSINESS UNDERSTANDING
Company Name: Nova Retail Ltd.
Nature of Business: Sales of electronics, appliances, and accessories.
Business Goal:
To identify sales trends, top-performing categories, customer patterns, and areas to improve profitability by analysing historical sales data.
## DATA UNDERSTANDING
This data contains 110 transactions across 11 columns
Each reCord represents a single transaction with the following fields: 

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
## DATA PREPARATION
Key data cleaning and preparation steps included:
	•	Checked and confirmed no null values or duplicates.
	•	Converted Date column to proper datetime format.
	•	Verified that numerical fields (Units Sold, Unit Price, Revenue, Discount) contained valid values.
	•	Created Month column derived from Date for monthly trend analysis.
	•	Calculated Total After Discount = Revenue - Discount for net revenue.
## EXPLORATORY DATA ANALYSIS
During the EDA stage, several aspects of the data were explored:
		Basic Statistics:
	•	Minimum revenue: ₦5,000
	•	Maximum revenue: ₦972,000
	•	Average revenue: approximately ₦268,373
           •        Total revenue:  ₦29,521,000
            •        Unique customers:  77
## SALES DISTRIBUTION:
Lagos recorded the highest transaction frequency and revenue, followed by Kano, Port Harcourt and abuja
	•	Customer Behaviour:
Returning customers contributed a larger portion of total revenue compared to new customers.
	•	Monthly Trends:
         Sales peaked in September 2024
	•	Outliers:
A few high-revenue transactions in Lagos (₦250,000 and above) significantly influenced the total revenue.
 







