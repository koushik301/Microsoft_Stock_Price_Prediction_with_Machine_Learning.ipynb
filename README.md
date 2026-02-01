# Microsoft Stock Price Prediction with Machine Learning

This project implements a comprehensive time-series analysis and forecasting pipeline to predict Microsoft (MSFT) stock prices using various machine learning and statistical models.

## 📌 Project Overview
The objective of this project is to analyze historical stock data and evaluate the performance of different modeling approaches for financial forecasting. The workflow includes:
- **Data Acquisition:** Loading historical MSFT stock data.
- **Exploratory Data Analysis (EDA):** Visualizing price trends and distributions over time.
- **Feature Engineering:** Preprocessing data for supervised learning and time-series models.
- **Modeling:** Implementing statistical, machine learning, and deep learning architectures.


## 📈 Key Insights & Business Impact
* **Volatality Handling:** While statistical models like **Auto-ARIMA** provided a solid baseline, the **LSTM (Long Short-Term Memory)** network demonstrated superior performance in capturing non-linear trends and sudden market shifts.
* **Feature Importance:** Exploratory analysis revealed that closing prices are heavily influenced by long-term momentum, validating the use of deep learning for sequential data.
* **Practical Application:** This pipeline serves as a foundational tool for quantitative analysis, helping to visualize potential risk and return scenarios for MSFT stock based on historical patterns.


## 🛠️ Tech Stack & Libraries
The project is built using Python and the following key libraries:
* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** `matplotlib`
* **Statistical Modeling:** `pmdarima` (Auto-ARIMA), `statsmodels`
* **Machine Learning:** `scikit-learn` (Linear Regression, KNN)
* **Time-Series Forecasting:** `prophet` (by Facebook)
* **Deep Learning:** `keras`, `tensorflow` (LSTM)

## 🤖 Models Implemented
The notebook explores several algorithms to determine the best fit for stock prediction:
1. **Linear Regression:** A baseline regression model.
2. **K-Nearest Neighbors (KNN):** Predicting prices based on historical similarity.
3. **Auto-ARIMA:** An automated statistical model for time-series forecasting.
4. **Facebook Prophet:** Designed for handling seasonality and trends in time-series data.
5. **Long Short-Term Memory (LSTM):** A recurrent neural network (RNN) capable of learning long-term dependencies.

## 📊 Dataset
The analysis uses a dataset named `MSFT.csv` containing historical price information, including:
- **Date**: The trading date.
- **Open/Close**: Opening and closing prices.
- **High/Low**: Highest and lowest prices during the day.
- **Volume**: Number of shares traded.

