# Stock Movement Prediction using News Sentiment Analysis 📈

## Project Overview
Predicting Apple (AAPL) stock movement (UP/DOWN) using ML + NLP

## Tech Stack
- Python
- yfinance, pandas, numpy
- matplotlib, seaborn
- vaderSentiment
- scikit-learn, xgboost
- ta (Technical Analysis)

## Dataset
- Stock Data: Downloaded via yfinance (automatic)
- News Data: [Kaggle - Apple Stock AAPL Historical Financial News](https://www.kaggle.com/datasets/frankossai/apple-stock-aapl-historical-financial-news-data)

## ML Workflow
1. Stock Data Collection
2. Feature Engineering — MA, RSI, MACD, Volatility
3. EDA
4. News Sentiment Analysis — VADER
5. Data Merging
6. Model Training
7. Model Evaluation

## Results
| Model | Accuracy |
|---|---|
| Logistic Regression | 57% |
| Decision Tree | 59% |
| Random Forest | 57% |
| SVC | 56% |
| **XGBoost** | **65%** |

## Key Findings
- Negative sentiment = most important feature!
- RSI + MACD boosted accuracy from 51% to 65%
- NLP + ML combined = better than either alone!
