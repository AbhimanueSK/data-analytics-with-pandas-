📊 Marketing Campaign Performance Insights

Data Analysis with Pandas & Visualizations

📌 Project Overview

In today’s competitive digital marketing landscape, understanding what drives campaign success is essential for maximizing ROI and improving strategic decision-making. Although organizations collect extensive campaign data, meaningful insights often remain hidden.

This project analyzes a comprehensive marketing dataset to evaluate campaign performance across companies, channels, customer segments, locations, and time periods.
Using pandas for data manipulation and matplotlib for visualizations, the project uncovers patterns in:

Conversion efficiency

Acquisition costs

Engagement behavior

ROI trends

Audience segmentation

Geographic influence

The goal is to derive actionable insights that can guide future marketing strategies and enhance campaign profitability.

📁 Dataset

Source:
https://raw.githubusercontent.com/ArchanaInsights/Datasets/main/marketing_campaign.csv

🧾 Data Dictionary
Column	Description
Campaign_ID	Unique identifier for each campaign
Company	The company running the campaign
Campaign_Type	Type of marketing effort (email, social media, influencer, etc.)
Target_Audience	Demographic group targeted (e.g., Women 25-34)
Duration	Duration of campaign in days
Channels_Used	Platforms used (Email, Google Ads, Instagram, etc.)
Conversion_Rate	% of leads/impressions converted
Acquisition_Cost	Cost to acquire one customer
ROI	Return on Investment
Location	Geographic campaign location
Language	Language used in the campaign
Clicks	Total number of clicks
Impressions	Total number of impressions
Engagement_Score	Score (1–10) for audience engagement
Customer_Segment	Segment of customers targeted
Date	Campaign date
🧪 Project Steps & Objectives
1️⃣ Load the Dataset

Import CSV into a pandas DataFrame

Inspect basic structure

2️⃣ Descriptive Analysis

Includes:

Viewing first few rows

Dataset shape (rows & columns)

Summary of data types, null values

Descriptive statistics

Count of unique Campaign_ID

Unique values for Location and Customer_Segment

Category counts for Campaign_Type and Channel_Used

3️⃣ Exploratory Data Analysis (EDA) & Visualizations
📈 Campaign Performance

Scatter plot: Acquisition_Cost vs ROI

Bar chart: Average Conversion_Rate by Channel_Used and Campaign_Type

Box plot: Engagement_Score across Campaign_Type

Bar chart: Average ROI by Company

Heatmap: Correlation — Engagement_Score vs Conversion_Rate

👨‍👩‍👧 Customer Segmentation

Count plot: Target_Audience distribution

Bar chart: Top Customer_Segment by Conversion_Rate for each Language

Box plot: Acquisition_Cost across Customer_Segment by Channel_Used

Bar chart: Average Conversion_Rate by Language

📡 Channel Effectiveness

Bar chart: Engagement_Score for different Channels_Used by Campaign_Type

Pie chart: Total ROI by Channel_Used

Scatter plot: Clicks vs Impressions for each Channel_Used

📅 Time-Based Analysis

Histogram: Distribution of Duration

Line chart: Conversion_Rate over time for each Company

Line chart: Engagement_Score trends over time

🌍 Geographical Analysis

Bar chart: Location with highest Acquisition_Cost

Bar chart: Conversion_Rate by Location grouped by Target_Audience

Pie chart: Proportion of ROI by Location

🛠️ Tools & Technologies Used

Python

Pandas (data manipulation)

NumPy (numerical computations)

Matplotlib (visualization)

Jupyter Notebook# data-analytics-with-pandas-
