# Stock Price Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting the next-day closing price of Apple (AAPL) stock using historical market data. The model is built using Machine Learning techniques and data fetched from Yahoo Finance.

---

## 🎯 Objective
To build a regression model that predicts the future closing price of a stock based on historical features such as Open, High, Low, and Volume.

---

## 📊 Dataset
- Source: Yahoo Finance
- Stock Used: Apple (AAPL)
- Library: `yfinance`

---

## ⚙️ Features Used
- Open Price
- High Price
- Low Price
- Volume

---

## 🎯 Target Variable
- Next_Close (Next day's closing price)

---

## 🤖 Machine Learning Model
- Algorithm: Linear Regression
- Problem Type: Supervised Learning (Regression)

---

## 🧪 Workflow
1. Data collection using yfinance
2. Data preprocessing and cleaning
3. Feature selection
4. Creating target variable using shift operation
5. Splitting data into training and testing sets
6. Training Linear Regression model
7. Making predictions
8. Evaluating model performance
9. Visualizing actual vs predicted prices

---

## 📈 Model Evaluation
- Mean Absolute Error (MAE): ~2.32  
- R² Score: ~0.98  

These results show that the model performs well in predicting short-term stock price movements.

---

## 📊 Visualization
A comparison graph between actual and predicted stock prices was plotted to analyze model performance.

---

## ⚠️ Important Note
This model is built for educational purposes only. Stock prices are influenced by many external factors, so real-world predictions require more advanced models and additional features.

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- yfinance

---

## 👨‍💻 Author
Saqib Latif  
AI/ML Engineering Intern

---

## 📌 Repository Structure
