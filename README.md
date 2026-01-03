##E-Commerce Retail Analytics Dashboard 

( TABLEAU LINK:- https://public.tableau.com/views/Product_Demand_Analysis_/Dashboard3?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

A comprehensive analysis of retail transaction data to identify revenue patterns, customer behavior, and market expansion opportunities using Python and Tableau.
Project Overview
This project analyzes over 400,000 retail transactions from 2011 to provide actionable insights for business decision-making. I cleaned the raw data, performed exploratory analysis, and created interactive Tableau dashboards to answer key business questions from executive stakeholders.
Dataset

##Records: 406,830 transactions
##Time Period: 2011
##Geography: 37 countries (excluding United Kingdom)
##Source: Online retail store transactions

##Business Questions Answered
Question 1: Revenue Time Series Analysis
The CEO wanted to view monthly revenue trends for 2011 to understand seasonal patterns and forecast for the next year. I created a time series visualization showing revenue fluctuations throughout the year.

Question 2: Top Revenue-Generating Countries
The CMO requested insights on the top 10 countries by revenue (excluding the UK) along with quantity sold. This helps identify key markets for the business.
Key Finding: After USA, Netherlands showed the highest product demand with 284,662 units sold.

Question 3: Top 10 Customers by Revenue
The CMO wanted to identify high-value customers to implement targeted retention strategies.
Key Finding: The top customer generated $279,489 in revenue.

Question 4: Geographic Demand Analysis
The CEO needed a single-view visualization of product demand across all countries to identify expansion opportunities.
Tools & Technologies

##Python: Data cleaning and preprocessing (Pandas, NumPy)
##Tableau: Interactive dashboard creation and data visualization
##Jupyter Notebook: Analysis and documentation

##Key Insights

Identified top customer contributing nearly $280K in revenue
Netherlands emerged as the market with highest demand (284,662 units)
Analyzed revenue patterns across 37 countries to support expansion strategy
Created executive-ready dashboards for CMO and CEO decision-making

├── data/
│   └── retail_data.csv
├── notebooks/
│   └── data_cleaning_analysis.ipynb
├── dashboards/
│   └── Product_Demand_Analysis.twbx
└── README.md

