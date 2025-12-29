# UPS KPI-METRICS ANALYSIS WITH POWER BI

## **1.0	Executive Summary**

This project presents an end-to-end KPI metrics analysis of logistics operations for UPS (United Parcel Service) using a ChatGPT-generated dataset representing fiscal and logistical transactions across Germany in 2024.

An interactive Power BI dashboard was developed to monitor performance indicators such as revenue, profit, cost, package quantities, and product categories. The analysis uncovers revenue patterns, regional performance differences, and dominant shipping product-categories, supporting data-driven decision-making in logistics operations.

## **2.0	Business Challenge/Problem**

Logistics businesses like UPS encounter a challenge of accessing a dashboard that helps monitors their fiscal and logistical KPIs like revenue, profit, cost, package quantities and regional performances.  Therefore, in this project I design a Power BI dashboard, equipped with slicers and data modelling features, to monitor the KPI metrics of UPS.

## **3.0	Methodology**

A synthetic dataset mimicking the financial and logistical operations of UPS in Germany is used in this project. The dataset, generated from ChatGPT, has two sheets – sales and cost. Each sheet has 2000 rows, with the sales sheet consisting of 9 columns and the cost sheet having 4 columns. The sales sheet has column features like transaction id, shipment date, shipping fee, and number of packages whiles the cost sheet has features like cost and handling fee. The transaction id column is the common column between the two sheets.

**Data Cleaning:** Checking for null values; Standardizing data column formats

**Tools:** Power BI (ETL, Power Query, Data Modelling [Table Joins], Dashboard Design, Slicer Development); Microsoft Excel; ChatGPT

**Skills:** Power BI Data Analysis & Dashboard Design, ETL, Chart Design & Data Visualization, Data Aggregation, Business Insight & Development, Business Reporting & Storytelling, ChatGPT Prompt Engineering & Data Generation

## **4.0	Key Findings**

-	UPS accrued a revenue of €40,590 in 2024, generated a profit of €18,450 and incurred a gross cost of €18,050. 
-	The highest revenue month was October (€4,086.03) and the least was February (€2,807.44). 
-	The state with the highest transaction frequency was North Rhine-Westphalia (216) and lowest was Hesse (175).
-	Books are identified as the highest shipping product-type (25.19%), followed by Electronics (24.99%). This result is also observed in revenue accruement per product type (Books - €10,220 ; Electronics - €10,140)


![Dashboard View](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/ba3736cc211094a19567b07ccd3aef2c4e71f0f1/KPI-Metrics%20Analysis%20with%20Power%20BI/visual/Dashboard%20View.png)

**Power BI Dashboard View**


Link to the Power BI project file to explore the dashboard -> (https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/ba3736cc211094a19567b07ccd3aef2c4e71f0f1/KPI-Metrics%20Analysis%20with%20Power%20BI/dashboard/UPS_financial_dashboard.pbix)

## **5.0	Recommendation**

To grow profits, UPS can leverage the insights of the dashboard to implement key actions. Central is to make an effort to expand variations in packages it usually ships beyond the traditional electronics, furniture, clothing and books. This can be achieved by strategic B2B/B2C advertisements and promotions to attract niched clients to deliver with them. Also, finding ways to reduce operational cost without compromising client results and satisfaction, will grow margins. Additionally, expanding operational activities to other economic states like Baden-Wurttemberg will also boost long-term business revenue.

## **6.0	Next Steps**

Future improvements to this project could include:

-	Automation of data refresh pipelines
-	Incorporation of delivery time, customer satisfaction, and SLA metrics
-	Customer and client segmentation analysis

## **7.0	Conclusion**

This project demonstrates how interactive dashboards and KPI-driven analytics can transform logistics data into actionable business insights.

By leveraging interactive Power BI dashboards, businesses like UPS can gain timely, data-driven insights into their operational and financial performance, enabling them to identify trends, optimize resource allocation, improve efficiency, and implement strategic decisions that support long-term business growth.

## **Acknowledgement**
Data generated using ChatGPT platform (Date Accessed: 21/12/2025)
