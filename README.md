# Data Exploratory Analysis and Hypothesis Testing for Insurance Claims Data
## Objective
To analyze and derive insights from insurance claims data by performing exploratory data analysis (EDA) and hypothesis testing, enabling better understanding of claim trends, fraudulent activity, and customer segmentation.
## Overview
Insurance claims data can provide actionable insights into customer behavior, claim trends, and fraud detection. This project involves combining customer and claim datasets, performing data cleaning, EDA, and statistical hypothesis testing to answer specific business questions and draw meaningful conclusions.
## Dataset Used
- <a href="https://github.com/SourabhaSekharRout/Data-Exploratory-Analysis-and-Hypothesis-Testing-for-Insurance-Claims-Data/blob/main/cust_demographics.csv">Customer Demographics</a>:
  - Contains information about customers, including their personal details and demographic information.
- <a href="https://github.com/SourabhaSekharRout/Data-Exploratory-Analysis-and-Hypothesis-Testing-for-Insurance-Claims-Data/blob/main/claims.csv">Claims Data</a>:
  - Includes details of insurance claims made by customers.
## Process
The process involves the following steps:
#### Data Import: 
- Load datasets into the working environment.
#### Datatype Change: 
- Audit and adjust data types for consistency and business significance.
#### Missing Value Treatment: 
- Handle missing values by imputing continuous columns with the mean and categorical columns with the mode.
#### Outlier Treatment: 
- Identify and treat outliers to ensure robust analysis.
#### Data Merging: 
- Combine customer and claims datasets to create a unified view.
#### Exploratory Data Analysis: 
- Analyze and visualize trends, patterns, and anomalies in the data.
## Questions Addressed
- Convert claim_amount to numeric and remove the "$" sign.
- Create an alert flag for injury claims not reported to the police.
- Retain the most recent observation for each customer ID and remove duplicates.
- Categorize customers into age groups: Children (<18), Youth (18-30), Adult (30-60), Senior (>60).
- Calculate average claim amounts for different customer segments.
- Analyze total claim amounts for incidents occurring at least 20 days prior to October 1, 2018.
- Determine the number of adults from TX, DE, and AK claiming driver-related issues.
- Create pie charts for claim amounts by gender and segment.
- Compare male and female claims for driver-related issues using bar charts.
- Visualize the age group with the highest fraudulent policy claims.
- Show monthly trends of total claimed amounts in chronological order.
- Create facetted bar charts for average claim amounts by gender and age categories, separating fraudulent and non-fraudulent claims.
- Conduct hypothesis tests to determine relationships between variables and draw business implications.
## Features
- Comprehensive data cleaning and preprocessing.
- Statistical summaries and hypothesis testing.
- Data visualizations for claim trends and customer segmentation.
- Insights into relationships between key variables.
## Insights
- Key demographics and behavioral patterns in claim submissions.
- Fraud detection through claim analysis.
- Trends in monthly and segment-wise claim amounts.
- Relationships between customer age, gender, and claim activity.
- Statistical validation of key business assumptions.
