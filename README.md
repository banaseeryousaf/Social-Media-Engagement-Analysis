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

1. Load & Inspect Data  
- Import dataset, check data types, missing values, duplicates.  
- Convert posted_at to datetime.   
2. Clean & Prepare
- Handle missing values.  
- Standardize categorical fields (gender, country, device_type, post_type).  
- Remove duplicates by post_id.
3. Feature Engineering
- Compute engagement rate = (likes+comments+shares)/impression_count.
- Extract posting time features (day, hour).
4. Analysis & Visualization
- Engagement by demographics (age, gender, country).
- Compare verified vs. non-verified (is_verified).
- Trends by post_type, device_type, and posting time.
- Correlation between follower_count, impression_count, and engagement.
5. Insights & Reporting
- Identify top-performing content types.
- Highlight demographic and device trends.
- Recommend best posting strategies.
 
 
KEY INSIGHTS

1. Engagement Drivers  
- Posts with higher likes, comments, shares, and watch time correlate strongly with higher engagement rate.  
- Certain post types (e.g., videos) and categories consistently outperform others.  
2. Audience Demographics  
- Age and gender groups show different engagement patterns (e.g., younger users may engage more with short videos).  
- Country-level trends highlight regional preferences in content type and sentiment.  
3. Account & Content Factors  
- Verified accounts (is_verified) often achieve higher impressions and engagement.  
- Follower count positively impacts reach, but engagement rate depends more on content quality.  
- Posts with positive sentiment and relevant hashtags tend to drive stronger interaction.  
4. Timing & Devices  
- Engagement varies by posting time (day of week, hour of day).  
- Device type analysis shows whether mobile or desktop users interact more deeply.  
5 Performance Correlations  
- Strong link between impression_count and engagement, moderated by content type.  
- Watch time is a key predictor of meaningful engagement for video posts.  



FILES INCLUDED

social_media_engagement_5000.csv
Social-Media-Engagement-Analysis.ipynb
README.md – Project description.
