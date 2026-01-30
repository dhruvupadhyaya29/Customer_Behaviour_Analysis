# **🛒 Customer Shopping Behavior Analysis**

# **Project Overview**

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to uncover actionable insights related to customer demographics, spending patterns, product preferences, and subscription behavior to support data-driven business decisions.

# **Dataset Summary**

+ Total Records: 3,900
+ Total Features: 18
+ Key Features Include:
+ Customer demographics: Age, Gender, Location, Subscription Status
+ Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color
+ Behavioral metrics: Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type
+ Missing Data: 37 values in the Review Rating column 

# **Tools & Technologies**

+ Python (Pandas, NumPy) – Data cleaning and feature engineering
+ MySQL – SQL-based business analysis
+ Power BI – Interactive dashboard and visualization

# **Data Processing & Feature Engineering**

+ The dataset was cleaned and transformed using Python:
+ Handled missing values in Review Rating using median imputation by product category.
+ Standardized column names using snake_case.
+ Created new features:
+ age_group – customer segmentation by age
+ purchase_frequency_days – numerical conversion of purchase frequency
+ Removed redundant column promo_code_used.
+ Loaded the cleaned data into PostgreSQL for further SQL analysis.

# **Key Business Analyses (SQL)**

+ The following insights were generated using PostgreSQL:
+ Revenue comparison by gender
+ High-spending customers who used discounts
+ Top 5 products by average review rating
+ Average purchase amount by shipping type
+ Subscriber vs non-subscriber revenue analysis
+ Discount-dependent products
+ Customer segmentation (New, Returning, Loyal)
+ Top products per category
+ Repeat buyers and subscription relationships
+ Revenue contribution by age group

# **Power BI Dashboard**

+ An interactive dashboard was built to visualize:
+ Total customers and average purchase amount
+ Revenue by category and age group
+ Subscription distribution
+ Sales performance by product category

# **Business Recommendations**

+ Based on the analysis:
+ Promote subscription plans with exclusive benefits
+ Implement loyalty programs for repeat buyers
+ Optimize discount strategies to balance profit margins
+ Focus marketing on top-rated products and high-revenue age groups
+ Target users preferring express shipping for premium offers
