# Macroeconomic Drivers of Stock Market Performance

## Project Overview
This project investigates the relationship between macroeconomic indicators and stock market performance using financial data collected between 2000–2025. The study combines statistical analysis, machine learning techniques, and interactive data visualizations to identify how economic variables influence stock market behavior.

The project analyzes approximately 3,000 observations across 24 financial and macroeconomic variables to understand long-term market patterns and economic impacts.

---

## Project Objectives

This project aims to:

- Analyze the relationship between GDP growth and stock market performance
- Study the impact of inflation on market returns
- Examine effects of interest rates on stock performance and trading volume
- Evaluate corporate profits and government debt influence on market confidence
- Build predictive models for stock price, stock returns, and trading volume
- Generate business insights for investors and policymakers

---

## Research Questions

### Q1:
How does GDP growth impact stock index closing prices and market performance?

### Q2:
What relationship exists between inflation rates and stock market returns?

### Q3:
How do interest rates affect stock performance and trading volume?

### Q4:
How do corporate profits and government debt influence investor confidence?

---

## Dataset Information

**Source:** Kaggle – Finance and Economics Dataset (2000–Present)

Dataset characteristics:

- Total observations: ~3,000
- Variables: 24
- Time period: 2000–2025

### Financial Variables

- Open Price
- Close Price
- High Price
- Low Price
- Trading Volume

### Macroeconomic Variables

- GDP Growth (%)
- Inflation Rate (%)
- Interest Rate (%)
- Unemployment Rate (%)
- Government Debt
- Corporate Profits
- Consumer Confidence

### Global Market Indicators

- Gold Prices
- Crude Oil Prices
- Forex Exchange Rates

---

## Methodology

### 1. Data Preparation

- Imported data using Pandas
- Verified data quality
- Standardized variable formats
- Time-series formatting
- Data validation

### 2. Exploratory Data Analysis (EDA)

Techniques used:

- Histograms
- Boxplots
- Correlation heatmaps
- Time-series visualization

Key findings:

- GDP growth positively correlates with stock performance
- Inflation and interest rates negatively correlate with market returns
- Gold prices show an inverse relationship with stock prices

---

## Feature Engineering

Created additional variables including:

### Stock Return (%)

Formula:

Stock Return (%) =
(Current Close Price − Previous Close Price)
/ Previous Close Price × 100

Purpose:

- Measure market volatility
- Evaluate relative market performance

---

## Predictive Models

### Model 1 — Stock Close Price Prediction

Methods:

- Multiple Linear Regression
- Random Forest Regression
- Gradient Boosting

Predictor variables:

- GDP Growth
- Inflation
- Interest Rate
- Unemployment
- Corporate Profits
- Government Debt
- Consumer Confidence

---

### Model 2 — Stock Return Prediction

Methods:

- Linear Regression
- Random Forest
- Gradient Boosting

---

### Model 3 — Trading Volume Prediction

Methods:

- Linear Regression
- Random Forest
- Gradient Boosting

---

## Model Evaluation Metrics

Evaluation measures:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)

Summary:

| Model | Best Performing Method |
|---------|------------------------|
| Close Price | Linear Regression |
| Stock Return | Linear Regression |
| Trading Volume | Linear Regression |

Findings:

- Macroeconomic indicators explain long-term market trends better than short-term market movements.
- Financial markets remain highly stochastic and sensitive to external factors.

---

## Dashboard Components

### Dashboard 1
Market performance analysis:

- GDP Growth trends
- Trading volume
- Interest rates
- Stock market performance

### Dashboard 2
Corporate and financial indicators:

- Corporate profitability
- Government debt
- Interest rates
- Forex analysis

### Dashboard 3
Economic crisis analysis:

- Unemployment trends
- Bankruptcy rates
- Venture capital funding
- Financial crisis impacts

---

## Key Findings

- GDP growth positively influences stock market performance.
- Inflation and higher interest rates generally reduce market returns.
- Corporate profitability significantly impacts investor confidence.
- Macroeconomic variables provide stronger insight into long-term trends than short-term price movement.

---

## Business Impact

### Investors
- Improve portfolio strategies using economic indicators
- Support risk management decisions

### Corporations
- Assist strategic planning and investment decisions

### Policymakers
- Better understand effects of economic policies on financial markets

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Tableau

---

## Future Improvements

- Include investor sentiment analysis
- Add financial news and social media data
- Implement advanced time-series forecasting models
- Apply deep learning techniques such as LSTM

---

## References

Fama, E. (1970). Efficient Market Hypothesis

Chen, Roll & Ross (1986). Economic Forces and Stock Market Returns

Finance and Economics Dataset (Kaggle)

---

## License

This project is created for academic purposes under the Master of Data Analytics program at University of Niagara Falls.
