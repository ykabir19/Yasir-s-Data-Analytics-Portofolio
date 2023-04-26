# Yasir-s-Data-Analytics-Portfolio

# [Project 1: London Housing Supply Analysis Project](https://github.com/ykabir19/ykabir19/blob/main/London%20Housing%20Supply%20Analysis%20Project%20%20.ipynb)
![image](https://user-images.githubusercontent.com/116688829/233814178-e2e57d4f-8b80-464b-bd80-315317cc9a67.png)


Welcome to the London Housing Supply Analysis Project! This project aims to investigate the impact of economic and social factors on the supply of houses in London. By examining the relationship between population, number of jobs, interest rates, life satisfaction, and mean salary, we aim to provide valuable insights for policy makers, real estate professionals, and researchers interested in the London housing market.

## Project Overview
The London Housing Supply Analysis Project combines data from various sources to explore the influence of economic and social factors on the supply of houses in London. Our dataset spans a 20-year period from 2000 to 2019, allowing us to identify both short-term and long-term trends. With this comprehensive analysis, we seek to better understand the underlying forces shaping the housing market and provide valuable recommendations for addressing current challenges.

## Features
* Detailed descriptive statistics of the variables
* Correlation analysis to identify relationships between variables and avoid multicollinearity issues
* Stationary tests to ensure accurate regression results
* ARDL model to examine short-run and long-run relationships between variables
* Robust conclusions and actionable recommendations


# [Project 2: Real Canadian Superstore EDA](https://github.com/ykabir19/ykabir19/blob/2ccf8e25ce55183c4218b00a5280c19275b323d9/Exploratory%20Data%20Analysis%20Real%20Canadian%20Super%20store%20.R)
![image](https://user-images.githubusercontent.com/116688829/234446156-7d2afb2d-0f31-4133-8ef6-ab2bb8e62494.png)

The Real Canadian Superstore is a chain of supermarkets in Canada owned by the retailing giant Loblaw companies. This project aims to analyze the company's dataset to gain insights on the company's performance, customer behavior, and product information. The ultimate goal is to demonstrate how Data Analytics techniques can be used in the retail industry top  improve efficiency and industry performance.

## Dataset Information 
Dataset URL: https://www.kaggle.com/datasets/shrutigupta2495/the-real-canadian-superstore-dataset
Dataset Details:

Size: 13.22MB
Number of Columns: 27
Number of Rows: 35339
File Format: .csv

## Data Analysis and Results


Using RStudio, the dataset will be analyzed, focusing on:
* Exploratory Data Analysis and Visualizations: Visualizations information about the store's sales, profits, and customer behavior across different regions, segments, shipping modes, and product categories.
* Summary Statistics
* Regions with the highest orders
* Products with the highest sales and profit
* Relationship between Profit, Sales, Quantity, and Discount
* Regression Analysis

## Results and Recommendations

Based on the analysis, the following recommendations can be made to improve the Real Canadian Superstore's performance:
* Increase advertisement and offer more discounts in Central and Atlantic regions to improve sales.
* Consider adjusting discounts on products like tables, as they yielded a loss.
* Increase the stock of high-selling products and reduce the stock of low-selling products.
* Implement a time series regression (Auto-Regression) to predict sales and profits, which can help forecast and inform future business decisions.


# [Project 3: Impact ofData Analytics on Marketing Strategies: Customer Segmentation using RFM Analysis](https://github.com/ykabir19/ykabir19/blob/2ccf8e25ce55183c4218b00a5280c19275b323d9/Customer_Segmentation_Using_RFM_analysis_.ipynb)
![image](https://user-images.githubusercontent.com/116688829/234449236-7d6a58f5-4c7d-4c59-9747-9bbafb43a637.png)

## Overview 
This project aims to analyze the impact of Data analytics on marketing strategies, specifically customer segmentation. Using the Online Retail II dataset from the UCI Machine Learning Repository, an RFM (Recency, Frequency, Monetary) analysis is performed to segment customers based on their purchase behavior. The effectiveness of personalized marketing campaigns through these segments is evaluated, and insights are uncovered that can help businesses optimize their marketing efforts and drive revenue growth.

## Dataset 
The dataset used in this project is the Online Retail II dataset from the UCI Machine Learning Repository. It contains transactional data for an online retailer and includes variables such as Quantity, Price, and Customer ID. The dataset can be downloaded from https://archive.ics.uci.edu/ml/datasets/Online+Retail+II.

## Methodology
Data Analysis and Preprocessing: The dataset is first loaded, cleaned, and preprocessed, handling any missing values and outliers.
* Exploratory Data Analysis (EDA): Descriptive statistics and visualizations are used to explore the dataset, understand the distribution of numeric variables, and identify any trends or patterns.
* RFM Analysis: The RFM analysis is performed, calculating Recency, Frequency, and Monetary value for each customer. An optimal number of clusters is determined using the elbow method, and customers are segmented into these clusters using the K-means clustering algorithm.
* Further Segmentation and Marketing Strategies: Based on the RFM analysis, customers are further segmented into distinct groups, such as Champions, Loyal Customers, At-Risk Customers, New Customers, and Lost Customers. Targeted marketing strategies are proposed for each group to optimize marketing efforts and improve customer retention and acquisition.
* Conclusion: The results of the analysis are summarized, highlighting the importance of understanding customer behavior for targeted marketing strategies. Theoretical contributions, practical implications, research limitations, and future research recommendations are also discussed.

## Dependencies
* Python 3.11.2
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-learn


