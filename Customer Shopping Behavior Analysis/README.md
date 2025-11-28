# Customer Shopping Behaviour: An Exploratory Data Analysis of 49,477 Retail Transactions

## 1. **Executive Summary**

This project analyses **49,477 real retail transactions** from multiple malls in Istanbul throughout 2022 and January 2023 to uncover patterns in customer behaviour, product performance, seasonal trends, mall performance, and payment preferences. The data gives a glimpse into the real shopping lifestyle and choices by customers in Istanbul. The insights support data-driven decisions in marketing, inventory management, and sales optimization.

## 2. **Business Problem**

Businesses are fraught with questions/challenges such as:

-	Identifying top-revenue and top-selling product categories to stock.
-	Performance of products across different shopping malls.
-	Tracking seasonal trends of customer demand of products.
-	Understanding how age and gender influence products sale-quantity.
-	Determining payment method preferences by customers across shopping malls.

Therefore, this project addresses these business problems using exploratory data analytics (EDA) and provides visualization.

## 3. **Methodology**

**Data Cleaning:** Checked for missing values & duplicates, formatted dates, renamed columns, handled categories, grouped customer ages

**Column Renaming:** invoice_no as _Invoice_no_, customer_id as _Customer_ID_, gender as _Gender_, age as _Age_, category as _Category_, quantity as _Quantity_Sold_, price as _Unit_Price_, payment_method as _Payment_Method_, invoice_date as _Invoice_Date_, shopping_mall as _Shopping_Mall_

**Feature Engineering:** Added *Total Revenue* column (Quantity × Unit Price), created *Year-Month* for seasonality analysis

**Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook, Microsoft Visual Studio Code, Microsoft Excel

**Skills:** Data Cleaning & Transformation, Exploratory Data Analysis (EDA), Feature Engineering, Data Aggregation & Grouping, Data Visualization & Chart Design, Business Insight Development, Python Programming, Use of Excel for preliminary data preparation

## 4. **Results**

- **High-revenue and highest-volume categories:** Clothing generates the highest revenue and is the largest in sale quantities. **It accrues 67.8% more revenue** than the second-highest product category (i.e. Shoes). Aside clothing category, not all the other high-selling products necessarily generate the highest-revenues, in-order.

  **Product Categories vs Total Revenue**

![Product Categories vs Total Revenue](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/92d053bb33ee240aa152af32161c55f7ca09c731/Customer%20Shopping%20Behavior%20Analysis/visuals/Product%20Categories%20vs%20Total%20Revenue.png)


  **Product Categories vs Quantity Sold**

![Product Categories vs Quantity Sold](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/92d053bb33ee240aa152af32161c55f7ca09c731/Customer%20Shopping%20Behavior%20Analysis/visuals/Product%20Categories%20vs%20Quantity%20Sold.png)



- **Mall activity:** The Mall of Istanbul leads with the **highest revenue generation (20.22%)** and followed by Kanyon (19.94%). Aside this close performance, the rest of the other malls have a disparity in revenue generation. The Emaar Square Mall is the least performing mall accounting for only 4.74% of the total revenue.

  **Shopping Mall vs Revenue Generation**

![Shopping Mall vs Revenue Generation](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/92d053bb33ee240aa152af32161c55f7ca09c731/Customer%20Shopping%20Behavior%20Analysis/visuals/Shopping%20Mall%20vs%20Revenue%20Generation.png)



- **Seasonal patterns in revenue and quantity sold:** Peak months show **4.39% higher sale-quantity and 7% higher revenue**, confirming mild but consistent seasonality. Specifically, October and March are the peak months for revenue and sale-quantities respectively.

  **Time Series of Sale Quantity and Total revenue per Month**

![Time Series of Sale Quantity and Total revenue per Month](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/2c3ea7576bb680d30f89482e4b15d81a9a37e830/Customer%20Shopping%20Behavior%20Analysis/visuals/Time%20Series%20of%20Sale%20Quantity%20and%20Total%20revenue%20per%20Month.png)



- **Strong customer activity in specific age-gender segments:** Young female customers aged 20-29 years are the **most active demographic** that drive the highest transaction activity in the data, contributing 11.64% of all transactions. Females, more than males, are the dominant customers. Customers in age group 30-39 years record the highest male transaction activity.

  **Customer Age Distribution by Gender**

![Customer Age Distribution by Gender](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/ed0ef05cdf3a34ce5018a4ee1006f0e1f20ae51f/Customer%20Shopping%20Behavior%20Analysis/visuals/Customer%20Age%20Distribution%20by%20Gender.png)



- **One payment method dominates customer transactions:** Cash is the **most preferred payment method** and accounts for 44.73% of all purchases, indicating a clear customer preference. Credit card and debit card are the less preferred payment methods, with debit card being the least preferred.

  **Distribution of Payment Method Usage**

![Distribution of Payment Method Usage](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/a727df9207ec8113957b1857fffa541e417304df/Customer%20Shopping%20Behavior%20Analysis/visuals/Distribution%20of%20Payment%20Method%20Usage.png)

## 5. **Business Implications & Recommendations**

- **Revenue & Sales Maximizing Strategy:** Clothing category’s 67.8% leading revenue advantage and large sale quantities suggests strong pricing power. This insight is crucial for retail business owners on what product to venture into and stock in their business. Furthermore, implementing **targeted promotions, premium placement, and prioritized inventory** will further boost revenues. Likewise, strategic pricing and advertising campaigns can be designed to drive sales and revenue in less performing product categories for businesses that seek to invest in them.
- **Mall Operations:** The Mall of Istanbul’s lead as the highest revenue-generating mall throughout 2022 and January 2023, followed by Kanyon shopping mall, shows that **resource allocation especially into high-revenue product category** sales like clothing will drive high profits, all things being equal. Again, based on the results, investment into low-revenue performing product categories like Souvenirs at low-revenue generating malls like Emaar Square mall in Istanbul will result in meagre revenues for retail business owners and retail shop investors, all things being equal.
- **Seasonal Planning:** The mild but consistent seasonality of revenue and sale-quantities with substantial peak amounts/quantities suggests a generally positive financial outlook and trend. Business owners and retail companies will benefit from this insight in terms of **preparing ahead of peak periods to meet customer demand**. To illustrate, a moderate preparation ahead of the peak revenue season like in October will secure and grow profit margins. Likewise, averting low patronage like in February 2022, possibly due to post-holidays product shortage, will accelerate month-on-month revenue generation.
- **Customer Targeting:** Young female customers aged 20-29 years contribute 11.64% of transactions which is the highest in the data. The highest male customers are aged 30-39 accounting 7.98% in transaction activity, followed by young customers aged 20-29 years. These **demographics can be targeted for higher-ROI marketing** by businesses. Also, aside customers below 10 years, businesses can design strategic campaigns to draw in the rest of the other demographics due to similar transaction activity records gender-wise, for even larger revenues.
- **Payment Optimization:** With 44.73% of transactions using cash, checkout systems should prioritize this payment flow. All things being equal, retail shops that trade or want to trade in similar product categories listed in this data, and have a **faster and smoother cash payment experience will accrue high revenue**. Also, incentivizing customers with swifter card payment experience and diverse digital payment options can accelerate such payment methods.

## 6. **Next Steps**

-	Applying customer segmentation techniques to identify distinct shopping behaviour patterns.
-	Developing sales forecasting models to predict future demand.
-	Perform market basket analysis for product bundling

## 7. **Conclusion**

This project analyses **49,477 real transactions** from Istanbul malls throughout 2022 and January 2023 to uncover insights on product performance, mall activity, seasonality, demographics, and payment behaviour. Through strong data cleaning, feature engineering, and visualization, the analysis reveals clear opportunities to optimize inventory, marketing, and operations. The result is crucial to business success for retail business owners, investors and shop managers operating in such large cities, trading similar products or run retail shops in shopping malls. Overall, the work demonstrates practical, job-ready data analytics skills applied to a real retail dataset.

## Acknowledgments
This project is based on an original dataset provided by Mehmet Tahir Aslan on Kaggle.com 
(Link: https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset?select=customer_shopping_data.csv).  


