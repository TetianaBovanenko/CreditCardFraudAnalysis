# Credit Card Fraud Analysis

![CC Fraud Logo](https://github.com/TetianaBovanenko/CreditCardFraudAnalysis/blob/main/frauddata_logo.png?raw=true)

## 📋 Project Overview
This project analyzes credit card transaction [data](https://www.kaggle.com/datasets/neharoychoudhury/credit-card-fraud-data) to identify patterns of fraudulent activity using Python for data preprocessing and Power BI for visualization. The dataset was sourced from Kaggle, and the aim was to uncover insights into fraud characteristics and patterns through data analysis and interactive visualizations.

🎥 View the Project
Visualizations: [Link to Power BI Dashboard](https://github.com/TetianaBovanenko/CreditCardFraudAnalysis/blob/main/credit%20card%20fraud%20analysis.pdf)
Presentation: [Watch the Video Presentation](https://drive.google.com/file/d/1ZSTKFIVkgS12oeajwO-Z9bR3Uywwc8bm/view?usp=drive_link)

---

## 🎯 Objectives
1. Understand patterns and characteristics of fraudulent transactions.
2. Preprocess raw data to ensure consistency and accuracy.
3. Visualize fraud patterns using interactive Power BI dashboards.
4. Calculate metrics related to fraud using DAX (Data Analysis Expressions).

---

## 🛠️ Tools and Technologies
- **Python**: Used for data loading, cleaning, and feature extraction with Pandas in Jupyter Notebook.
- **Power BI**: Used for creating interactive dashboards and reports to visualize fraud patterns.
- **DAX (Data Analysis Expressions)**: Utilized in Power BI to clean text data and compute metrics.

---

## 🔄 Data Preprocessing
The preprocessing workflow included:
- Handling inconsistent date formats in the transaction dataset.
- Cleaning the `is_fraud` column for accuracy.
- Extracting new features:
  - **Transaction Year, Month, Day, and Hour**
  - **Cardholder's Age**
- Dropping redundant columns to optimize the dataset.
- Exporting the cleaned dataset for visualization in Power BI.

---

## 📊 Data Visualization
In **Power BI**:
- Created calculated columns, such as:
  - **CleanedJob**: Categorized and cleaned job titles.
  - **CleanedMerch**: Processed merchant names for consistency.
  - **MonthName**: Translated month numbers into readable names.
- Used **DAX expressions** to compute:
  - Total amounts involved in fraudulent transactions.
  - Metrics and summaries for fraudulent patterns.

---

## 🚀 Installation and Setup
### Clone the Repository
```bash
git clone https://github.com/yourusername/credit-card-fraud-analysis.git
cd credit-card-fraud-analysis
