# TCS Share Price Prediction using Regression Analysis

## 📌 Project Overview
This project focuses on predicting the share price of Tata Consultancy Services (TCS) using regression analysis. The dataset consists of historical stock prices from 2002 to 2004, and the analysis involves understanding correlations and applying regression techniques to predict future stock values.

## 📊 Dataset Description
The dataset contains six key attributes:
- **Date**: The date of the stock price record
- **Open**: The opening price of TCS stock on a particular day
- **High**: The highest stock price of TCS on that day
- **Low**: The lowest stock price of TCS on that day
- **Close**: The stock price of TCS at market closing
- **Volume**: The total number of TCS shares traded on that day
- **Adj Close**: Adjusted closing price considering splits and dividends

## 🔍 Correlation Analysis
- Strong positive correlation between **Open and High (0.999)** and **Open and Close (0.999)** indicates a trend where stock prices generally increase by market close.
- Moderate positive correlation **(0.221)** between **Volume and Open** suggests trading volume tends to increase with higher opening prices.

## 📈 Regression Analysis
The regression model was applied to analyze and predict stock prices. Key results:
- **Multiple R**: 0.8516 (Indicates strong correlation between predicted and actual values)
- **R-Squared**: 0.7039 (70.39% of the variation in stock price is explained by the model)
- **Adjusted R-Squared**: 0.7030 (Refined measure accounting for the number of predictors)
- **Standard Error**: 2823.804 (Measures variability of residuals, lower values indicate better accuracy)

## 🛠️ Methodology
1. Data Preprocessing: Handling missing values, data cleaning
2. Exploratory Data Analysis: Understanding patterns and correlations
3. Regression Model: Applying linear regression to predict stock prices
4. Evaluation: Assessing model accuracy with R-Squared and error metrics

## 🚀 How to Run the Project

1. Clone this repository:
   ```sh
   git clone https://github.com/Arch1123/Share-Price-Prediction-TCS-Regression.git
   ```
2. Open the `TCS-Price_Prediction.xlsx` file, which contains the complete dataset and analysis results.
3. Load the data from `TCS-Price_Prediction.xlsx` using a data analysis tool (e.g., Python, Excel, or Jupyter Notebook).
4. Perform Exploratory Data Analysis (EDA) to examine stock price trends and distributions.
5. Conduct correlation analysis using the `Corelation` sheet to understand relationships between stock attributes.
6. Apply regression modeling using the data from the `TCS1` sheet to predict stock prices.
7. Evaluate the model's performance using the results in the `Multiple Regression` sheet.

Finally, review the generated statistical results and visualizations to interpret stock price predictions effectively.

## 📌 Conclusion
This project successfully applies regression analysis to predict TCS stock prices with a strong correlation and high explanatory power. Future improvements could involve using advanced machine learning techniques like LSTMs or Random Forest Regression.

## 📝 Author
Archit Garg

