# mobile-sales-analysis
This project analyzes mobile phone sales data to identify trends, understand customer buying behavior, and determine which factors like price and brand influence sales performance

# Mobile Sales Data Analysis

## Objective
Analyze mobile phone sales data to uncover trends and insights.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn

Project Workflow
-Data Loading
-Data Cleaning
-Exploratory Data Analysis (EDA)
-Visualization
-Insights

## Key Insights
- Price affects units sold
- Some brands dominate revenue
- Sales trends vary over time

## Files
- eda.ipynb
- dataset.csv

## Known Problems
From the correlation matrix, one major issue is that revenue is highly dependent on price and units sold since it is a derived variable. Additionally, most variables show weak correlations, especially customer rating and time features, which do not significantly influence sales. This suggests the dataset lacks strong predictive features and may not fully represent real-world behavior. Also, variables like Sale_ID are not useful for analysis and can be considered irrelevant. These limitations highlight the need for more meaningful features and real-world data to improve the quality of analysis and insights

##Project Structure

├── data
├── notebooks
├── scripts
└── reports
    └── .gitignore
