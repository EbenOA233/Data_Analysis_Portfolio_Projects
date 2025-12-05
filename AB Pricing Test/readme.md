# Profit Optimization Experiment: An A/B Pricing Test of Zara’s Faux Leather Jacket 

## 1.	**Executive Summary**

This project explores a 1000 Zara-ChatGPT augmented retail transaction dataset to uncover patterns in purchasing behaviour of Zara’s Faux Leather Jacket. An a/b test is performed to determine the difference in mean profit per customer between two prices ($24.99 or $35.99) of the product. The result of the Welch two sample t-test’s p-value (4.98 × 10⁻¹⁰⁷), which is essentially 0, shows a strong statistically significant difference in mean profit between the two prices. Therefore, maintaining the price of $35.99 per product is statistically superior for profit generation. Like Zara, this result is crucial for fashion retail business owners, product inventory managers and sales executives to encourage data-driven pricing strategy to ensure enabled business profit margins.

## 2.	**Business Problem/Challenges**

Retail businesses constantly face the challenge of determining the optimal product price that maximizes profit. A key strategic dilemma is whether to increase prices to improve profit margins or reduce prices to stimulate higher sales volume. Therefore, this project:
•	Explores a retail transaction data to understand customer purchasing behaviour of Zara’s faux leather jacket.
•	Performs an A/B test to determine difference in mean profit per customer between the two prices of the product.
•	Recommends a statistically superior price for the product based on the test.

## **3.	Methodology**
A dataset comprising a total of 1000 customer entries and capturing 12 columns were analysed. Key features of the data include product price, sales volume and transaction date. Below are additional key descriptions and actions.

Data creation: Zara retail transaction data, obtained from Kaggle.com, was modified and augment with ChatGPT generated data to form the 1000 customer entries.
Data Cleaning:  Checked for na & null values; formatted dates.
Feature Engineering: Created Profit column [(Quantity) * (Price – Cost)], where assumed product cost is $15; Created Year-Month for seasonality analysis; pivoted aggregated profit data by time and pricing group for time-series analysis
Data Grouping: Prices are analysed in terms of two groups. Price Group A is for $24.99, and Price Group B is for $35.99. The product variants A and B are binary flags for price groups A and B respectively. Also, profit is categorized in terms of the two price groups.
Hypotheses: Null Hypothesis (H0) – There is no difference in average profit per customer between the $30 price and $40 price; Alternative hypothesis (H1) – There is a difference in average profit per customer between the $30 price and $40 price. 
Statistical Testing: The Welch’s test was selected to compare the mean profit of the two price groups as it does not assume equal variance of the observed groups and is robust for real-world business data.
Tools Used: Python, Pandas, Scipy, Matplotlib, Seaborn, Jupyter Notebook, Microsoft Visual Studio Code, Git & Github
Skills: Statistical Testing & Business Decision Making, Exploratory Data Analysis, Business Insight Development, Business Reporting & Storytelling, Data Cleaning, Feature Engineering, Data Aggregation & Grouping, Data Visualization & Chart Design, Git & Github File Management

## **4.	Results & Business Recommendation**
•	Variation in Sales Volumes: An exploration of the data shows that sale volume differs between the two prices of the jacket. The Sale volume is 1.84% higher when price of the jacket is $35.99 than when just $24.99. Similarly, total profit accumulation is far higher when the product price is $35.99. Zara and other fashion retail businesses are prudent in their decision to test different prices for products like the faux leather jacket, as clearly a higher profit is seen in one price group than the other.
•	Strong Statistical Significance in Mean Profit Per Customer: The result of the Welsch two sample t-test indicates a strong statistically significant difference in mean profit per customer between the two prices. A p-value of 4.98 × 10⁻¹⁰⁷, which is essentially 0, is recorded showing that profit difference due to price change is real. Further, the difference in mean profit between the two prices is statistically decisive, with an extremely small probability of occurring by random chance. The null hypothesis is rejected, and alternative hypothesis is accepted.  
•	Best Price for the product: Based on the result, the best price for the product is $35.99. This price is statistically superior between the two prices, and is robust across time. For a fashion retail business like Zara, this outcome is critical to maximize profit whiles considering customer sensitivity to price change. Further, sticking to a largely accepted price of a product will build more customer patronage and encourage referrals.

## **5.	Next Steps**
To strengthen future pricing decisions, the following steps are recommended:
•	Conduct customer segmentation analysis (age, region, loyalty)
•	Perform a price sensitivity analysis with additional price groups
•	Run promotional impact testing (discount vs no discount)

## **6.	Conclusion**
This project demonstrates how A/B testing, profit engineering, and statistical validation can be applied to real retail pricing decisions. The results clearly show that the higher price group ($35.99) delivers superior profitability for Zara’s faux leather jacket with overwhelming statistical confidence. By following a structured, data-driven methodology, Zara can confidently implement the recommended pricing strategy and improve long-term revenue performance.

