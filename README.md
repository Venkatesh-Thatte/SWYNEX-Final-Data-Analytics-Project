SWYNEX Final Data Analytics Case Study

Project Overview

This case study combines the three project stages completed during the SWYNEX Data Analyst Internship: data cleaning and preparation, exploratory data analysis (EDA), and an interactive Excel dashboard. The goal is to turn raw sales transactions into a reliable dataset, identify performance patterns, and present findings in a decision-friendly format.


Business Problem

Sales teams need a clear view of revenue, order volume, product performance, city-level performance, payment methods, monthly trends, and sales representative results. The analysis explores the provided sales dataset to identify the strongest contributors and areas that may require follow-up.


Dataset Information
- Source: Sales dataset supplied for the SWYNEX internship tasks
- Records before cleaning: 45 transaction rows
- Records after cleaning: 44 transactions
- Time period represented in EDA summary: January–September
- Fields: Order ID, order date, customer name, city, product, category, quantity, unit price, payment mode, sales representative, and calculated sales/revenue fields where present
- Currency: Values are presented as AED in the project context

  
Data Cleaning and Preparation
The cleaning workflow documented in the workbook included:
- Removing a duplicate transaction (ORD1011)
- Replacing a missing customer name and city with Unknown
- Imputing missing or zero quantity values using the median valid quantity (3)
- Standardizing city, product, and payment-mode labels
- Trimming extra spaces from text fields
- Converting text-stored dates and numeric values to appropriate data types
- Correcting a negative unit price using the product's valid reference price

  
Validation
The validation sheet reports:
- 0 duplicate Order IDs
- 0 blank customer names
- 0 blank cities
- 0 quantities less than or equal to zero
- 0 unit prices less than or equal to zero
- 44 cleaned transaction rows'

  
Exploratory Data Analysis
The EDA workbook reports the following summary metrics:
- Total orders: 44
- Total units sold: 124
- Total revenue: AED 1,666,500
- Average order value: AED 37,875
- Median order value: AED 27,750

  
Key Findings
1. Laptop is the leading product by revenue, generating AED 780,000.
2. Hyderabad is the leading city by revenue, generating AED 632,000.
3. April is the strongest month in the EDA summary, with AED 477,500 in revenue.
4. Electronics is the largest category, generating AED 1,256,500 versus AED 410,000 from Furniture.
5. UPI is the leading payment mode by revenue, generating AED 670,500.
6. Vikram has the highest order count among the listed sales representatives, with 16 orders and AED 648,500 in revenue.
7. Pricing anomaly for review: Order ORD1019 lists a Laptop at 2,500, while other Laptop transactions are priced at 55,000. This should be validated against the source records before drawing conclusions from that transaction.


Dashboard
The interactive Excel dashboard consolidates KPI cards, charts, sales summaries, and filtering functionality to support exploration of sales performance. Use the dashboard workbook to review overall performance and compare products, cities, and sales representatives. Interactivity may depend on Excel desktop features such as PivotTables and slicers.


Business Recommendations
- Review the Laptop price recorded for ORD1019 against the original transaction or invoice.
- Investigate what drove April's revenue peak and whether the drivers can be repeated.
- Review city-level performance to understand the gap between Hyderabad and other cities.
- Assess the Electronics category's contribution and monitor Furniture performance separately.
- Compare sales representative results using both revenue and order count, not order count alone.
- Continue validating data quality at source to reduce missing, duplicate, and inconsistent entries.

  
Project Files
1. 01_Data_Cleaning_Preparation.xlsx — raw data, cleaned data, cleaning log, and validation checks.
2. 02_Exploratory_Data_Analysis.xlsx — EDA summary, charts, and key insights.
3. 03_Interactive_Dashboard.xlsx — dashboard and supporting analysis.

   
Tools and Skills
Microsoft Excel, data cleaning, data validation, exploratory data analysis, PivotTables, charts, KPI reporting, dashboard development, and business insight communication.


Conclusion
This case study demonstrates an end-to-end Excel analytics workflow: prepare and validate data, analyze business performance, and communicate findings through an interactive dashboard. The results provide a starting point for further investigation and more informed sales decisions.


Organization: SWYNEX
Project: Final Data Analytics Project — Task 4
Tool: Microsoft Excel
