# 📈 AI Portfolio Risk & Return Analyzer using Machine Learning

## Overview

The **AI Portfolio Risk & Return Analyzer** is an end-to-end financial analytics and machine learning project that analyzes an equity portfolio, evaluates its historical performance, measures investment risk, predicts future portfolio returns and volatility, and provides an interactive business intelligence dashboard using **Power BI**.

The project combines **financial analytics**, **portfolio management**, **machine learning**, **Monte Carlo simulation**, and **interactive visualization** to build a decision-support system for portfolio evaluation.

---

## Project Objectives

* Analyze historical portfolio performance
* Measure portfolio risk using financial risk metrics
* Forecast future portfolio returns using Machine Learning
* Predict future portfolio volatility
* Estimate probability of portfolio losses
* Compare portfolio performance against the NIFTY 50 benchmark
* Visualize insights through an interactive Power BI dashboard

---

## Technologies Used

| Category         | Tools                        |
| ---------------- | ---------------------------- |
| Programming      | Python                       |
| Data Analysis    | Pandas, NumPy                |
| Visualization    | Matplotlib, Plotly, Power BI |
| Machine Learning | Scikit-learn, XGBoost        |
| Financial Data   | yfinance                     |
| Optimization     | SciPy                        |
| Development      | Jupyter Notebook             |

---

## Project Workflow

```text
Historical Stock Data
          │
          ▼
 Data Collection (Yahoo Finance)
          │
          ▼
 Data Cleaning & Feature Engineering
          │
          ▼
 Portfolio Analytics
          │
          ▼
 Machine Learning Models
          │
          ▼
 Performance Evaluation
          │
          ▼
 Power BI Dashboard
```

---

# Portfolio

The project analyzes a diversified Indian equity portfolio consisting of stocks from multiple sectors.

Example Portfolio:

* Reliance Industries
* HDFC Bank
* TCS
* Infosys
* ICICI Bank
* Bharti Airtel
* ITC
* Tata Motors

Benchmark:

* NIFTY 50 Index

---

# Features

### Portfolio Analytics

* Portfolio Value Tracking
* Daily Returns
* Portfolio Growth
* CAGR
* Annual Return
* Annual Volatility
* Sharpe Ratio
* Sortino Ratio
* Maximum Drawdown
* Portfolio Beta
* Portfolio Alpha
* Historical VaR (95%)
* Historical CVaR (95%)

---

### Machine Learning

The project predicts:

* Future Portfolio Returns
* Future Portfolio Volatility
* Probability of Portfolio Loss

Models implemented:

### Return Prediction

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

### Volatility Prediction

* Linear Regression
* Random Forest
* XGBoost

### Loss Prediction

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

---

### Model Evaluation

Regression Metrics

* MAE
* RMSE
* R² Score
* Directional Accuracy

Classification Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

---

## Feature Engineering

The following financial indicators were created for model training:

* Daily Return
* Lag Returns
* Rolling Mean
* Moving Average
* Exponential Moving Average
* Rolling Volatility
* Drawdown
* Momentum
* RSI
* MACD
* Bollinger Bands
* Calendar Features
* Forward Return
* Forward Volatility

---

# Portfolio Optimization

Implemented:

* Mean-Variance Optimization
* Maximum Sharpe Portfolio
* Minimum Variance Portfolio
* Efficient Frontier

---

# Monte Carlo Simulation

The project performs Monte Carlo simulation to estimate future portfolio performance.

Simulation Features

* 10,000 simulated portfolio paths
* 252 trading-day investment horizon
* Portfolio value distribution
* Probability of Profit
* Best Case Scenario
* Worst Case Scenario
* Median Expected Value

---

# Power BI Dashboard

The project includes an interactive dashboard consisting of multiple pages.

### Executive Dashboard

* Portfolio Value
* CAGR
* Annual Return
* Sharpe Ratio
* Risk Score
* Portfolio Growth
* Benchmark Comparison

### Portfolio Analytics

* Portfolio Allocation
* Sector Allocation
* Stock Performance
* Risk vs Return Scatter Plot

### Risk Analytics

* Drawdown Analysis
* Daily Returns
* VaR
* CVaR
* Beta
* Alpha
* VIX Analysis

### Machine Learning

* Actual vs Predicted Returns
* Actual vs Predicted Volatility
* Loss Probability
* Model Comparison
* Feature Importance

### Correlation Analysis

* Correlation Heatmap
* Diversification Analysis

---

# Repository Structure

```text
AI-Portfolio-Risk-Return-Analyzer
│
├── data/
│
├── notebooks/
│   ├── 01_Data_Collection.ipynb
│   ├── 02_Portfolio_Analytics.ipynb
│   ├── 03_Feature_Engineering.ipynb
│   ├── 04_WalkForward_Backtesting.ipynb
│   ├── 05_Optimization.ipynb
│   └── 06_PowerBI_Export.ipynb
│
├── dashboard/
│   ├── AI_Portfolio.pbix
│   └── Dashboard_Screenshots/
│
├── output/
│
├── report/
│
├── requirements.txt
│
└── README.md
```

---

# Future Improvements

* SHAP Explainability
* LSTM-based Return Forecasting
* Black-Litterman Portfolio Optimization
* Live Market Data Integration
* Real-Time Portfolio Monitoring
* News Sentiment Analysis
* Automated Portfolio Rebalancing

---

# Skills Demonstrated

* Financial Analytics
* Quantitative Finance
* Portfolio Management
* Machine Learning
* Predictive Analytics
* Time Series Analysis
* Feature Engineering
* Model Evaluation
* Data Visualization
* Power BI Dashboard Development
* Python Programming
* Risk Management

---

# Author

**Anushree Lal**

B.Tech Biotechnology
Thapar Institute of Engineering & Technology

**Skills**

Python • Machine Learning • Financial Analytics • SQL • Power BI • Excel

---

## License

This project is intended for educational and portfolio purposes only and should not be considered financial or investment advice.





