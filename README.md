# Customer_Behaviour_Analysis
Customer Shopping Behavior Analysis
Project Overview
This project analyzes customer shopping behavior using a dataset of 3,900 transactional purchases to uncover key insights into spending patterns, product preferences, customer segmentation, and subscription behavior. The findings aim to support strategic business decisions.

* Key Findings & Insights
Revenue & Spending Patterns

Gender Revenue: Male customers generated significantly higher revenue ($157,890) compared to Female customers ($75,191).





Age Group Revenue: Young Adults contributed the highest total revenue ($62,143), followed by the Middle-aged group ($59,197).




Shipping Preference: The average purchase amount for Express shipping ($60.48) was slightly higher than for Standard shipping ($58.46).


Subscription: Non-subscribers generated a higher total revenue ($170,436) and had a slightly higher average spend ($59.87) than subscribers.

Product & Preference Analysis

Top 5 Products by Rating: Gloves had the highest average rating (3.86), followed by Sandals (3.84) and Boots (3.82).




Discount-Dependent Products: Hat had the highest percentage of discounted purchases (50.00%), indicating high discount sensitivity.

Top Category Products:


Accessories: Jewelry, Sunglasses, Belt.




Clothing: Blouse, Pants, Shirt.




Footwear: Sandals, Shoes, Sneakers.




Outerwear: Jacket, Coat.



Customer Segmentation & Loyalty

Customer Segments: The majority of customers are classified as Loyal (3,116 customers), with a smaller number of Returning (701) and New (83) customers.


Repeat Buyers & Subscription: A large number of repeat buyers (customers with >5 purchases) do not have a subscription (2,518).


* Methodology
The project utilized a structured two-phase approach:

1. Exploratory Data Analysis (EDA) in Python

Data Cleaning: Handled 37 missing values in the Review Rating column by imputing with the median rating per product category.



Feature Engineering: Created age_group and purchase_frequency_days columns.


Standardization: Renamed columns to snake case and dropped the redundant promo_code_used column.



Database Integration: Loaded the cleaned data into PostgreSQL for detailed SQL analysis.

2. Structured Data Analysis in SQL (SSMS)
Key Business Questions Answered:

Revenue by Gender and Age Group.


High-Spending Discount Users identification.

Product performance by Rating and Discount dependency.


Shipping Type and Subscription status comparison.


Customer Segmentation.

* Business Recommendations
Based on the analysis, the following strategic actions are recommended:


Boost Subscriptions: Promote exclusive benefits to convert the large base of non-subscribing repeat buyers.



Customer Loyalty Programs: Implement a program to reward repeat buyers and solidify their status in the "Loyal" segment.


Targeted Marketing: Focus marketing efforts on Young Adults and Male customers as they are the highest revenue-contributing segments.




Product Positioning: Highlight top-rated items like Gloves and best-selling category items in campaigns.



* Dashboard & Visualization
Insights are presented through an interactive dashboard built in Power BI .

Would you like me to elaborate on any of the business recommendations or provide the specific SQL queries used for the analysis?
