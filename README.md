# Social-Media-Engagement-Analysis

PROJECT OVERVIEW
This project focuses on analyzing a social media engagement dataset to uncover patterns in user behavior and content performance.The dataset includes metrics such as likes, comments, shares, impressions, and watch time, which provide valuable insights into how audiences interact with digital content.  

TOOLS USED

- Python – Core programming language for analysis.
- NumPy – Efficient numerical computations, array operations, and mathematical transformations.
- Pandas – Data cleaning, aggregation, pivot tables, and feature engineering.
- Matplotlib – Basic plots (line charts, bar charts, scatter plots).
- Seaborn – Advanced statistical visualizations (heatmaps, boxplots, pairplots).
- Plotly – Interactive dashboards and dynamic charts for engagement metrics.

DATASET

Source :https://github.com/GeethaGunasekaran1/Dataset_rep/blob/main/social_media_engagement_5000.csv

Key Columns:'user_id', 'age', 'gender', 'country', 'post_id', 'post_type',
       'post_category', 'likes', 'comments', 'shares', 'watch_time_sec',
       'impression_count', 'posted_at', 'follower_count', 'is_verified',
       'device_type', 'sentiment', 'hashtags', 'engagement_rate'




STEPS FOLLOWED

Data Cleaning

Imputed missing values (mean for numeric columns, mode for categorical).
Removed outliers in WarehouseToHome (>100 km).
Standardized categorical values (e.g., “COD” → “Cash on Delivery”).
Data Transformation

Renamed inconsistent columns (PreferedOrderCat → PreferredOrderCat).
Created derived fields:
ComplaintReceived (Yes/No)
ChurnStatus (Active/Churned)
Dropped redundant columns (Churn, Complain).
Data Exploration & Analysis

Count of churned vs active customers.
Average tenure & cashback of churned customers.
Churn breakdown by complaints, city tier, and preferred order category.
Preferred payment mode among active customers.
Segmentation by marital status, warehouse distance, and satisfaction score.
Top 3 order categories by average cashback.
Categorization of customers by warehouse distance (Very Close, Close, Moderate, Far).
Relational Table Design

Created customer_returns table to track refund behavior.
Joined with customer data to analyze churned customers with complaints and returns.
KEY INSIGHTS

Customers with complaints showed a significantly higher churn rate.
City Tier‑1 had the highest churn in Laptop & Accessory category.
Credit Card was the most preferred payment mode among active customers.
Single customers preferring mobile phones showed higher order amount hikes.
Top cashback categories: Electronics, Fashion, and Groceries.
Warehouse distance strongly correlated with churn — farther customers churned more.
FILES INCLUDED

E-Commerce Customer churn db.sql – Table creation and sample data insertion.
ecomm.sql – Cleaned and transformed dataset.
README.md – Project description.
