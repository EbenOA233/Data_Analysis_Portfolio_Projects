# Rewe Sales Insights Automation with SQL & Python

## **1.	Executive Summary**

Rewe is one of Germany’s leading supermarket chains, offering everyday grocery products ranging from beverages to fresh produce. This project analyzes synthetic sales data from June 1–8, 2025, across three hypothetic Rewe store branches (101, 102, and 103) to uncover insights into revenue performance, product category sales, store-level differences, payment method preferences and discount impacts on sale volumes.

Using SQL Server Management Studio for data storage, SQL for querying and Python for visualization, the project demonstrates how supermarket managers and retail analysts can track key business KPIs to support informed decision-making and accelerate growth.

## **2.	Business Questions/Problems**

The project aims to answer the following business questions:
-	How do gross revenues differ across Rewe store branches? 
-	Which stores accrued revenue above the average gross revenue?
-	Which product categories generate the highest gross revenue? 
-	What payment methods do customers prefer?
-	Which stores record the highest net revenue?
-	How does discount affect sale volumes at Store 101?

## **3.	Methodology**
This project uses synthetic retail data of Rewe, generated using ChatGPT, covering June 1 – 8, 2025. The data is divided into three tables “DailyStoreSales”, “ProductSalesSummary” and “PaymentSummary”. Three hypothetic Rewe store branches are captured throughout this project, namely: 101, 102 and 103. The “DailyStoreSales” table highlights the daily transactional data, the “ProductSalesSummary” shows the product sales records, and “PaymentSummary” table covers the payment-related transactional data. 

**Data Cleaning:** Checked for null and na values.

**Tools:** Microsoft SQL Server Management Studio (SQL Server Database Creation); Microsoft Visual Studio (SQL & Python scripting); ChatGPT

**Skills:** ETL, Python, Matplotlib, Pandas, Sqlalchemy, SQL, CTE, Window Function, Order by, Group by, Having, Aggregate Functions, SQL Syntax Writing, MySQL, Microsoft SQL Server Database-Python connection, Data Cleaning, Chart Design & Visualization, Business Reporting & Storytelling, Github File Management, ChatGPT Prompt Engineering & Data Generation

## **4.	Key Findings**

-	The three Rewe stores recorded different gross-revenues over the period. [Store 101 - €15,640 ; Store 102 - €13,470 ; Store 103 - €9,340]

![Gross Revenue by Store](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/36a924c91ef9483539ab91a2c954107065aabd31/Rewe%20Sales%20Insights%20Automation%20with%20SQL%20%26%20Python/visuals/Gross%20Revenue%20by%20Store.png)

-	Only stores 101 and 102 accrued revenue above the average gross-revenue (€12,816.67).

![Above Average Gross Revenue](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/36a924c91ef9483539ab91a2c954107065aabd31/Rewe%20Sales%20Insights%20Automation%20with%20SQL%20%26%20Python/visuals/Above%20Average%20Gross%20Revenue.png)

-	Beverage is the highest gross-revenue accruing product category across the three stores. [Bakery - €3,615 ; Beverage - €10,775 ; Dairy - €6,000 ; Meat - €9,870 ; Produce - €8,190]

![Gross Revenue by Product Category](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/36a924c91ef9483539ab91a2c954107065aabd31/Rewe%20Sales%20Insights%20Automation%20with%20SQL%20%26%20Python/visuals/Gross%20Revenue%20by%20Product%20Category.png)

-	EC Card is the most preffered payment method, ahead of cash and credit card payments, across the three stores. [Transaction Frequency: EC Card - 2855; Cash - 710; Credit Card - 160]

![Transaction Frequency by Payment Method](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/36a924c91ef9483539ab91a2c954107065aabd31/Rewe%20Sales%20Insights%20Automation%20with%20SQL%20%26%20Python/visuals/Transaction%20Frequency%20by%20Payment%20Method.png)

-	Stores 101 and 102 record the highest net revenue across the three Rewe stores. [Store 101 - €13,180 ; Store 102 - €11,355 ; Store 103 - €7,870]

![Net Revenue by Store](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/36a924c91ef9483539ab91a2c954107065aabd31/Rewe%20Sales%20Insights%20Automation%20with%20SQL%20%26%20Python/visuals/Net%20Revenue%20by%20Store.png)

-	Sale volumes increases with increasing discount across the product categories, in general, at Store 101.

![Discount impact on Sale Volume at Store 101](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/36a924c91ef9483539ab91a2c954107065aabd31/Rewe%20Sales%20Insights%20Automation%20with%20SQL%20%26%20Python/visuals/Discount%20impact%20on%20Sale%20Volume%20at%20Store%20101.png)

## **5.	Recommendation**

To grow further profits, Rewe should ensure a balanced but prioritized resource allocation into beverage products, relative to the other product categories. Stocking high-revenue generating products like beverage and meat products in Stores 101 and 102, and investigating low-revenue generation in Store 103, will grow overall margins. Also, leveraging discount-sale volume insights to design profit and sale volume-increasing schemes, will boost revenue. Additionally, implementing an even easier and smoother EC Card checkout experience will promote customer patronage, as its the most preferred payment method.

## **6.	Next Steps**
Rewe’s sales KPI tracking can further be bolstered by:
-	Expanding the analysis to include longer time periods and seasonal trends
-	Adding customer segmentation (time of day, basket size, repeat customers)
-	Applying sales forecast for demand planning

## **Acknowledgement**
Data generated using ChatGPT platform (Date Accessed: 21/12/2025)
