# Customer Shopping Behaviour: An Exploratory Data Analysis of 49,477 Retail Transactions

## 1. **Executive Summary**

This project analyses **49,477 retail transactions** from multiple malls in Istanbul to uncover patterns in customer behaviour, product performance, seasonal trends, mall performance, and payment preferences. The insights support data-driven decisions in marketing, inventory management, and sales optimization.

## 2. **Business Problem**

Business owners are fraught with questions/challenges such as:

- Identifying their top-revenue and top-selling product categories.
- Understanding how products perform across different shopping malls.
- The seasonal fluctuations in customer demand.
- How age and gender influence sale quantities.
- Payment-method customer preference.

Therefore, this project answers these business questions using exploratory data analytics (EDA) and provides visualization.

## 3. **Methodology**

**Data Cleaning:** Checked for missing values & duplicates, formatted dates, renamed columns, handled categories, grouped customer ages

**Feature Engineering:** Added *Total Revenue* column (Quantity × Unit Price), created *Year-Month* for seasonality analysis

**Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook, Microsoft Visual Studio Code, Microsoft Excel

**Skills:** Data Cleaning & Transformation, Exploratory Data Analysis (EDA), Feature Engineering, Data Aggregation & Grouping, Data Visualization & Chart Design, Business Insight Development, Python Programming, Use of Excel for preliminary data preparation

## 4. **Results**

- **High-revenue categories differ from highest-volume categories:** There is a **high disparity in sale quantities** of the product categories, **likewise in their revenues**. Furthermore, the highest-volume sale (i.e. Clothing) product category does not translate as the highest-revenue product category (i.e. Technology). Technology generates 67.8% more revenue than the second-highest product category (i.e. Shoes).
- **Similar revenues accrued among shopping malls:** The highest revenue-accruing mall (i.e. Viaport Outlet) **earns just 3.67% more revenue** than the least revenue-accruing mall (i.e. Zorlu Center), indicating closely matched revenues at the ten observed shopping malls.
- **Seasonal patterns in revenue and quantity sold:** Peak months show **4.39% higher sale-quantity and 7% higher revenue**, confirming mild but consistent seasonality. Specifically, October and March are the peak months for revenue and sale-quantities respectively.
![Time Series of Sale Quantity and Total revenue per Month](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/77ffb37fad548f4983eb1a59218f82ee3099c734/Customer%20Shopping%20Behavior%20Analysis/visuals/Time%20Series%20of%20Sale%20Quantity%20and%20Total%20revenue%20per%20Month.png)
- **Strong customer activity in specific age-gender segments:** Young female customers aged 20-29 years are the **most active demography** that drive the highest transaction activity in the data, contributing 11.64% of all transactions. Females, more than males, are the dominant customers. Customers in age group 30-39 years record the highest male transaction activity.
![Customer Age Distribution by Gender](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/ed0ef05cdf3a34ce5018a4ee1006f0e1f20ae51f/Customer%20Shopping%20Behavior%20Analysis/visuals/Customer%20Age%20Distribution%20by%20Gender.png)

- **One payment method dominates customer transactions:** Cash is the **most preferred payment method** and accounts for 44.73% of all purchases, indicating a clear customer preference. Credit card and debit card are the less preferred payment methods, with debit card being the least preferred.
![Distribution of Payment Method Usage](https://github.com/EbenOA233/Data_Analysis_Portfolio_Projects/blob/a727df9207ec8113957b1857fffa541e417304df/Customer%20Shopping%20Behavior%20Analysis/visuals/Distribution%20of%20Payment%20Method%20Usage.png)

## 5. **Business Implications & Recommendations**

- **Revenue & Sales Maximizing Strategy:** Technology category's 67.8% leading revenue advantage suggests strong pricing power. Similarly, clothing category's 27,861 (121.3%) lead sale-quantity advantage infers robust customer preference. Targeted **promotion and strategic advertising campaigns** can further boost revenue and sales.
- **Mall Performance:** Revenue does not significantly change across shopping malls. With only 3.67% difference in peak and lowest mall performance among the ten observed malls, a general similarity of revenue per mall is observed. Maintaining **existing management structures** and sale/revenue mechanisms will help ensure consistent ROI. Moreover, **increase investment** in the top performing malls can drive further returns for business grow.
- **Seasonal Planning:** The mild but consistent seasonality of revenue and sale-quantities with substantial peak amounts/quantities suggests a generally positive financial outlook and trend for the business. Furthermore, a moderate preparation ahead of the peak revenue season in October is important to secure and grow profit margins. As the strongest dip in revenue and sales coincide in February, likely factors such as **post-holiday product shortages** must be averted to ensure continuous month-to-month revenue accruement.
- **Customer Targeting:** Young female customers aged 20-29 years contribute 11.64% of transactions which is the highest in the data. The highest male customers are aged 30-39 accounting 7.98% in transaction activity, followed by young customers aged 20-29 years. These demographies can be targeted for **higher-ROI marketing**. Moreover, strategic efforts must be made to **draw-in the other growing demographies** for an even robust growth.
- **Payment Optimization:** With 44.73% of transactions using cash, checkout systems should prioritize this payment flow. Introducing a further a **faster and smoother cash payment experiences** by customers will also strengthen as the preferred payment method. Also, introducing an innovative and seamless way to pay with digital mediums and cards will accelerate online purchases.

## 6. **Next Steps**

- Forecast monthly sales and mall performance
- Build customer segmentation clusters
- Perform market basket analysis for product bundling

## 7. **Conclusion**

This project analyses 49,477 real transactions from Istanbul malls to uncover insights on product performance, mall activity, seasonality, demographics, and payment behaviour. Through strong data cleaning, feature engineering, and visualization, the analysis reveals clear opportunities to optimize inventory, marketing, and operations. Overall, the work demonstrates practical, job-ready data analytics skills applied to a real retail dataset.

## Acknowledgments
This project is based on an original dataset provided by Mehmet Tahir Aslan on Kaggle 
(Link: https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset?select=customer_shopping_data.csv).  


