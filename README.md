# Credit Card Fraud Analysis
![CC Fraud Logo](https://github.com/TetianaBovanenko/CreditCardFraudAnalysis/blob/main/frauddata_logo.png?raw=true)

This project analyzes credit card transaction data to identify patterns of fraudulent activity. It utilizes Python for data preprocessing and Power BI for visualization. The [dataset] (https://www.kaggle.com/datasets/neharoychoudhury/credit-card-fraud-data) used is sourced from Kaggle.
## Project Overview
The main objective of this project is to understand the patterns and characteristics of fraudulent transactions through data analysis and visualization. The data was cleaned and preprocessed using Pandas in a Jupyter Notebook. The cleaned data was then visualized in Power BI, where DAX expressions were used to further clean text data and calculate metrics related to fraud.
## Tools and Technologies
- Python (Pandas, Jupyter Notebook): Used for data loading, cleaning, and feature extraction.- Power BI: Used for creating interactive dashboards and reports to visualize fraud patterns.
- DAX (Data Analysis Expressions): Used in Power BI to clean text data and compute various metrics.
## Data Preprocessing
The preprocessing involved:- Handling inconsistent date formats.
- Cleaning the is_fraud column.- Extracting new features like transaction year, month, day, and hour, as well as calculating the cardholder's age.
- Dropping redundant columns and exporting the cleaned data.
## Data Visualization
In Power BI:- Created calculated columns such as CleanedJob, CleanedMerch, and MonthName.
- Computed total amounts involved in fraudulent transactions using DAX.
## Installation
### Clone the Repository
```shgit clone https://github.com/yourusername/credit-card-fraud-analysis.git
cd credit-card-fraud-analysis
