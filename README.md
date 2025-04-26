# 📈 Time Series Analysis for Bitcoin Price Prediction Using Prophet

## 🔍 Project Overview

This project presents a comprehensive study on Bitcoin price prediction using time series analysis techniques. It evaluates the performance of various forecasting models—**RNN**, **LSTM**, **ARIMA**, and **Facebook's Prophet**—on historical Bitcoin data. The objective is to identify the most effective model for forecasting Bitcoin prices amidst the high volatility of the cryptocurrency market.

The models are trained and tested on a dataset containing timestamps and closing prices, enabling us to explore patterns, evaluate accuracy, and propose data-driven solutions for real-world crypto trading strategies.

---

## 🧩 Problem Statement

Bitcoin and other cryptocurrencies are inherently volatile. Traditional prediction methods often fall short in this unpredictable market. This project investigates which time series forecasting method provides the most accurate predictions and supports smarter trading decisions.

---

## 🎯 Objectives

- Apply and compare **RNN**, **LSTM**, **ARIMA**, and **Prophet** models for Bitcoin price prediction.
- Analyze historical data to evaluate the predictive power of each technique.
- Provide insights for investors by identifying the most accurate forecasting model.

---

## 📌 Scope

- Time Series Analysis using ML and statistical models.
- Visualization and exploration of historical Bitcoin trends.
- Real-world application in volatile financial markets.
- Foundation for future hybrid and real-time forecasting systems.

---

## 🧪 Methodology

### Data Source
- 📊 Dataset: [Bitcoin Price Dataset on Kaggle](https://www.kaggle.com/datasets/jkraak/bitcoin-price-dataset)
- Features: Timestamp, Open, High, Low, Close, Volume, Number of Trades

### Preprocessing Steps
- Convert timestamps to datetime format.
- Handle null values.
- Train-Test split (80:20).
- Normalize data (as needed per model).

---

## 🧠 Models Used

### 🔁 RNN (Recurrent Neural Network)
- Suitable for sequential data and time dependencies.
- Learns historical trends to forecast future prices.

### 🧠 LSTM (Long Short-Term Memory)
- Variant of RNN with memory cells.
- Handles long-range dependencies and nonlinearities in price data.

### 📉 ARIMA
- Traditional statistical model.
- Effective for stationary data with trends and seasonality.

### 🔮 Facebook Prophet
- Additive model with trend, seasonality, and holiday components.
- Robust to missing data and outliers.
- User-friendly and interpretable.

---

## 📊 Output Screens (UI)
- **Home Page:** Welcome interface for users.
- **Registration & Login:** Secure access system.
- **Data View:** Visual inspection of historical Bitcoin prices.
- **Prediction:** User inputs time frame (e.g., weeks) to forecast Bitcoin value.

---

## ⚙️ System Architecture & Tools

### Hardware
- Intel i5, 8GB RAM (min), 128GB HDD

### Software
- OS: Windows 10
- Language: Python 3.10.8
- IDE: VS Code

### Libraries
- `Prophet`, `TensorFlow`, `Pandas`, `Scikit-learn`, `Seaborn`, `Streamlit`

---

## 📈 Evaluation and Results

Each model was tested and benchmarked for performance on unseen Bitcoin price data. Visualizations, accuracy metrics, and comparative analysis highlight which model performed best under various conditions.

---


## 🔍 Research Gap

- Lack of studies comparing ML and statistical models on Bitcoin data.
- Need for real-time systems and integration of market sentiment.
- Limited exploration of temporal patterns and model robustness under volatility.

---

## 🚀 Future Scope

- Incorporate macroeconomic and sentiment data.
- Build hybrid models combining strengths of RNN + ARIMA.
- Extend analysis to other cryptocurrencies.
- Develop real-time prediction dashboards.

---

## ✅ Conclusion

This project establishes the viability of ML and statistical models in forecasting Bitcoin prices. While ARIMA offers a baseline, models like **LSTM** and **Prophet** show promise in handling the complexities of crypto markets. The results guide investors toward smarter decision-making based on reliable predictions.

---

## 📚 References

1. Alqassem et al., IEEE Trans. Syst., 2020.
2. Nerurkar et al., J. Netw. Comput. Appl., 2021.
3. Ron & Shamir, Springer, 2013.
4. Tao et al., IEEE, 2021–2022.
5. Romiti et al., arXiv, 2019.
6. And more from top journals and conferences.

---

## 🙏 Thank You for Visiting!

Feel free to clone, fork, or contribute to this repository to enhance Bitcoin forecasting models and democratize crypto insights.
