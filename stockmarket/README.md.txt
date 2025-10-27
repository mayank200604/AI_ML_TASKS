# 📊 Stock Market Prediction using Machine Learning & Deep Learning

This project predicts whether a **stock should be bought or sold for the next trading day** using real historical data and technical indicators. It applies multiple machine learning algorithms including Decision Tree, Logistic Regression, Random Forest, XGBoost, and LightGBM to find the best-performing model.


## 📌 Project Overview

The goal of this project is to analyze historical stock data and predict next-day price movements (BUY or SELL signal) using machine learning.

This project involves:

1. **Fetching live stock data**
   - Using `yfinance` to download historical data for multiple companies  
   - Handling missing data and cleaning  

2. **Adding Technical Indicators**
   - RSI (Relative Strength Index)  
   - MACD (Moving Average Convergence Divergence)  
   - OBV (On-Balance Volume)  
   - 50-Day and 200-Day Moving Averages  
   - MA Crossover Signal  

3. **Preparing Data for Machine Learning**
   - Feature selection and target creation (based on next-day close price)
   - Splitting into training and testing datasets  

4. **Applying ML Models**
   - Decision Tree Classifier  
   - Logistic Regression  
   - Random Forest  
   - XGBoost  
   - LightGBM  
   - Hyperparameter tuning using `GridSearchCV`  

5. **Model Evaluation**
   - Comparing models using accuracy score  
   - Selecting the best model for final prediction  

6. **Making Predictions**
   - Predicting whether the stock should be **BUY** or **SELL** for the next trading day  


## ⚙️ Requirements

Install the following Python libraries before running the notebook:

```bash
pip install yfinance pandas ta scikit-learn xgboost lightgbm
