# 📈 HDFC Bank Stock Risk Classification using Machine Learning

## 🧠 Capstone Project

This project focuses on analyzing HDFC Bank stock market behavior using Machine Learning and financial analytics techniques.

The system uses Yahoo Finance historical stock data to:
- calculate stock returns
- measure volatility
- generate Z-score based risk classifications
- compare multiple machine learning models
- predict the next trading day’s stock risk category

The project demonstrates a complete end-to-end financial analytics workflow using Python.

---

# 🎯 Project Objective

The objective of this project is to:

- Analyze HDFC Bank stock data from Yahoo Finance
- Calculate stock market volatility using statistical techniques
- Create risk categories using Z-score analysis
- Build predictive machine learning classification models
- Compare model performance
- Predict the next day’s stock risk class

---

# 🏦 Why HDFC Bank?

HDFC Bank was selected because:
- it is one of India’s leading banking stocks
- it has strong market relevance
- it provides stable and meaningful financial data
- it is suitable for stock market analytics and volatility analysis

---

# 📂 Data Source

Data Source:
- Yahoo Finance API (`yfinance`)

Stock Used:
- `HDFCBANK.NS`

Data Period:
- 01-Jan-2025 to 14-May-2026

Prediction Target:
- Predict stock risk class for 15-May-2026

---

# 📊 Dataset Features

The project uses stock market variables including:

- Open Price
- High Price
- Low Price
- Close Price
- Volume

Additional engineered features:
- Daily Returns
- 5-Day Moving Average
- 10-Day Moving Average
- Volatility
- Z-Score

---

# 🧠 Key Financial Concepts Used

## 📈 Daily Return

Daily return measures percentage stock movement compared to the previous trading day.

Formula:

Return = (Current Close - Previous Close) / Previous Close

---

## 📊 Volatility

Volatility measures how much stock prices fluctuate over time.

Higher volatility indicates:
- higher uncertainty
- higher market risk

---

## 📉 Moving Average

Moving averages smooth short-term price fluctuations and help identify market trends.

The project used:
- 5-Day Moving Average
- 10-Day Moving Average

---

## 🚨 Z-Score Analysis

Z-score standardizes stock returns and identifies unusual market behavior.

Formula:

Z = (Value - Mean) / Standard Deviation

Risk Classification:
- Low Risk → Z-score < -1
- Medium Risk → -1 ≤ Z-score ≤ 1
- High Risk → Z-score > 1

---

# ⚙️ Machine Learning Models Used

The following classification algorithms were implemented and compared:

| Model | Purpose |
|---|---|
| KNN | Similarity-based classification |
| Decision Tree | Rule-based classification |
| SVM | Boundary-based classification |
| Random Forest | Ensemble learning |

---

# 🧪 Machine Learning Workflow

1. Data Collection from Yahoo Finance
2. Data Cleaning
3. Feature Engineering
4. Z-score Calculation
5. Risk Classification
6. Train-Test Split
7. Feature Scaling
8. Model Training
9. Model Evaluation
10. Model Comparison
11. Model Saving
12. Next-Day Risk Prediction

---

# 📈 Exploratory Data Analysis (EDA)

The project includes:
- Stock Price Trend Analysis
- Return Distribution Analysis
- Risk Class Distribution
- Moving Average Visualization
- Feature Importance Analysis
- Model Accuracy Comparison

---

# 🏆 Best Performing Model

Random Forest achieved the best overall performance because:
- it handles non-linear market behavior effectively
- it reduces overfitting
- it combines predictions from multiple decision trees
- it performs well on noisy financial data

---

# 💾 Model Persistence

The final trained model and scaler were saved using:
- `joblib`
- `.pkl` files

Saved Files:
- `hdfc_risk_model.pkl`
- `scaler.pkl`

This enables future predictions without retraining the model.

---

# 🔮 Final Prediction

The final system predicts:
- the expected stock risk category
- for the next trading day
- using the latest available market indicators

---

# 💡 Business Insights

The project identified several important financial insights:

- Stock volatility varies across trading periods
- Moving averages and volatility strongly influence risk behavior
- Financial markets contain non-linear patterns
- Ensemble models perform effectively on stock market data

---

# 🚀 Business Impact

This project demonstrates practical applications of Machine Learning in:
- Financial Analytics
- Risk Monitoring
- Stock Volatility Analysis
- Predictive Financial Modeling
- Market Behavior Analysis

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Yahoo Finance API (`yfinance`)
- Joblib
- Jupyter Notebook

---

# 📂 Project Structure

HDFC_Bank_Risk_Classification/

├── hdfc_stock_capstone.ipynb
├── hdfc_stock_capstone.html
├── hdfc_risk_model.pkl
├── scaler.pkl
├── README.md

---

# 📌 Final Conclusion

A complete stock risk classification system was successfully developed using HDFC Bank stock market data.

The project combined:
- financial analytics
- statistical analysis
- feature engineering
- machine learning classification
- predictive modeling

The system successfully demonstrated how Machine Learning can support:
- financial risk analysis
- volatility monitoring
- predictive stock analytics
- data-driven market insights

This capstone project represents a practical real-world implementation of predictive analytics in finance.

---

# 🔗 Author

## Goutham Kumar
