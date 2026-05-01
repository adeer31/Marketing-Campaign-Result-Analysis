# 📊 Marketing Data Analysis: Data Cleaning, EDA & Dashboard

## 📌 Project Overview
This project focuses on cleaning and analyzing a marketing dataset to uncover insights related to customer demographics, purchasing behavior, and campaign effectiveness. The analysis is performed using Python for data processing and Tableau for interactive data visualization, enabling a comprehensive, end-to-end data analysis workflow.

## 🎯 Objectives
1. Clean and preprocess raw marketing data
2. Explore customer demographics and behavior
3. Evaluate marketing campaign performance
4. Identify patterns in income and spending
5. Build an interactive dashboard for business insights

## 📂 Dataset
The dataset is sourced from the Maven Analytics Data Playground (https://mavenanalytics.io/data-playground/marketing-campaign-results) and contains customer-level marketing data, including:
1. Demographics (age, education, marital status, country)
2. Income information
3. Product spending behavior
4. Purchase channels (web, catalog, store, deals)
5. Campaign response data

## 🛠️ Tools & Technologies
1. Python (Pandas, NumPy) for data cleaning and analysis
2. Matplotlib & Seaborn for exploratory visualization
3. Tableau for interactive dashboard development
4. Jupyter Notebook for analysis workflow

## 🧹 Data Cleaning & Preprocessing
1. Removed duplicate records
2. Handled missing values in income using median imputation
3. Standardized column names
4. Created new features such as Age, Total Spending, and Total Purchases
5. Cleaned inconsistent categorical values
6. Identified and handled outliers

## 🔍 Exploratory Data Analysis
1. Customer segmentation based on demographics
2. Analysis of income vs spending behavior
3. Purchase patterns across different channels
4. Campaign response analysis
5. Correlation analysis between key variables

## 📊 Tableau Dashboard
The Tableau dashboard translates the analysis into interactive visuals, including:
1. Total product spending by customers
2. Income vs spending analysis
3. Purchase behavior by channel
4. Campaign performance overview
5. Filters for exploring customer segments

## 📈 Key Insights
1. Income is the strongest driver of customer spending, showing a high positive correlation (r = 0.82), making it the most important factor for customer segmentation.
2. Wine products dominate total revenue, contributing over 50% of overall spending, significantly outperforming all other product categories.
3. Customers with children at home tend to spend less, as indicated by a strong negative correlation between the number of kids and total spending (r = -0.56).
4. Physical stores are the primary purchase channel, accounting for the highest number of transactions compared to web, catalog, and deal channels.
5. Campaign performance varies significantly, with Campaign 6 achieving the highest acceptance, while Campaign 2 underperforms by a wide margin.
6. The customer base is heavily skewed toward older age groups, with the majority of customers aged between 36 and 60, and very low representation from younger customers.
7. Total purchases and income both show strong positive relationships with total spending, indicating that frequent buyers and higher-income customers contribute the most to revenue.

## 📌 Conclusion
This project demonstrates how combining data cleaning, exploratory analysis, and interactive visualization can transform raw marketing data into actionable business insights. By leveraging Python and Tableau, the analysis provides a clear understanding of customer behavior and supports more effective, data-driven marketing strategies.
