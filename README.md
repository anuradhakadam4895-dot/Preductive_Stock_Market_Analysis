# Predictive Analytics for Stock Market Movements

## 📈 Project Overview
This data science project implements a machine learning binary classification framework to predict whether a stock's closing price will move UP (1) or DOWN (0) on the following trading day. The project utilizes historical equities data and engineers technical momentum and trend indicators to guide algorithmic predictions.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Engineering:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Random Forest Classifier, Logistic Regression, StandardScaler)
* **Visualization:** Matplotlib

## ⚙️ Feature Engineering Details
To train the predictive models, three core technical analysis indicators were engineered from raw price matrices:
1. **SMA_7 & SMA_21:** Simple Moving Averages tracking short-term and medium-term price trends.
2. **RSI_14:** Relative Strength Index to quantify asset price velocity and identify overbought/oversold momentum conditions.

## 📊 Evaluation & Visualizations
Below is the sequential tracking performance graph showing predicted vs. actual directional movements over a 40-day testing window:

![Prediction Output Chart](major_stock_prediction.png)

## ⚠️ Key Structural Limitations
* **Exogenous Vulnerabilities:** The framework relies purely on historical price trends and does not account for real-time fundamental impacts like macroeconomic news catalysts or earnings disclosures.
* **Friction Metrics:** The simulation assumes zero brokerage fees, which would normally impact portfolio profitability during high-frequency signal shifts in real-world environments.
*
