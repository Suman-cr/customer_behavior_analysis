# customer_behavior_analysis
📊 Customer Shopping Behavior Analysis | End-to-end data project analyzing 3.9K purchases. Features Python (pandas) for data cleaning and imputation , PostgreSQL for structured business queries (revenue, segmentation, subscriptions) , and an interactive Power BI dashboard to visualize key consumer trends.




# 📊 Customer Shopping Behavior Analysis

## 📝 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories. The primary goal is to uncover actionable insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions.

## 📂 Dataset Summary

* **Size:** 3,900 rows and 18 columns.


* **Demographics:** Includes Customer Age, Gender, Location, and Subscription Status.


* **Purchase Details:** Features Item Purchased, Category, Purchase Amount, Season, Size, and Color.


* **Shopping Behavior:** Tracks Discount Applied, Previous Purchases, Frequency of Purchases, Review Rating, and Shipping Type.



## 🛠️ Tech Stack & Methodology

This end-to-end data analysis pipeline leverages three primary tools:

* **Python (pandas):** Used for initial Exploratory Data Analysis (EDA) and data cleaning. Missing values in the `Review Rating` column were imputed using the median rating of each product category. Feature engineering was applied to create an `age_group` column and a `purchase_frequency_days` column.


* **PostgreSQL:** The cleaned dataset was loaded into a PostgreSQL database to execute structured queries. This facilitated complex business analysis, such as identifying high-spending discount users and comparing revenue across demographics.


* **Power BI:** An interactive dashboard was developed to visually present key metrics, including revenue by age group, sales by category, and the percentage of customers by subscription status.



## 💡 Key Insights

* **Gender Revenue Trends:** Female customers generate slightly higher total revenue than male customers.


* **Shipping Impact:** Customers utilizing Express shipping spend approximately 12% more per transaction ($60.48) compared to those using Standard shipping ($58.46).


* **Subscription Value:** Subscribers account for a massive 78% of the revenue share and exhibit a 68% higher average spend compared to non-subscribers.


* **Customer Segmentation:** The customer base breaks down into New shoppers (50%), Returning shoppers (35%), and Loyal shoppers (15%).


* **Top-Rated Products:** The products with the highest average customer satisfaction ratings are Gloves, Sandals, Boots, Hats, and Skirts.



## 🚀 Business Recommendations

* **Boost Subscriptions:** Promote exclusive benefits for subscribers to capitalize on their higher spending habits.


* **Loyalty Programs:** Implement and enhance reward systems for repeat buyers to successfully transition them into the high-value "Loyal" segment.


* **Targeted Marketing:** Focus promotional efforts on high-revenue age groups and customers who prefer express shipping.


* **Product Positioning:** Actively highlight top-rated and best-selling products in marketing campaigns to maximize sales and customer satisfaction.



---

## 👨‍💻 About the Author

Developed by Suman Kumar Gouda. This repository serves as a practical application of data cleaning, SQL querying, and business intelligence visualization methodologies gathered during B.Tech Computer Science and Engineering studies.
