# AR Model for Stock Price Prediction

## 📌 Project Overview
This project explores **Auto-Regressive (AR) models** for stock price prediction using **Apple's (AAPL) stock data** from Yahoo Finance. The main objective was to understand how AR models work in time series forecasting and evaluate their effectiveness.

## 📊 Dataset
- **Source:** Yahoo Finance
- **Stock:** Apple Inc. (AAPL)
- **Date Range:** 2020-01-01 to 2024-01-01
- **Feature Used:** Closing Price

## 🛠️ Methods Used
1. **Downloading AAPL stock data** using `yfinance`.
2. **Building AR models:**
   - AR(1): Auto-Regressive model with lag 1.
   - AR(2): Selected based on Partial Autocorrelation Function (PACF).
3. **Model Evaluation:**
   - Compared AIC values to select the best AR model.
   - Forecasted future prices using the best model.
   - Evaluated predictions with RMSE (Root Mean Squared Error).

## 📈 Key Findings
- **AR(1) performed well**, but AR(2) showed slightly better results based on AIC.
- **AR models can capture trends**, but they are limited when dealing with sudden market fluctuations.
- **PACF helps in determining the best lag order** for AR models.

## 🚀 How to Run the Project
1. Install dependencies:
   ```bash
   pip install yfinance pandas numpy matplotlib statsmodels scikit-learn
   ```
2. Run the Python script:
   ```python
   python ar_model_stock_prediction.py
   ```

## 🔥 Lessons Learned
- How AR models work in time series forecasting.
- How to use PACF to determine the optimal AR order.
- Importance of AIC in model selection.

## 📌 Future Improvements
- Implement **ARIMA** (Auto-Regressive Integrated Moving Average) for better forecasting.
- Compare AR models with ML-based approaches like XGBoost.
- Use other financial indicators (Volume, Moving Averages) for richer predictions.

---
### 🌟 **Let’s Connect!**
If you're interested in time series forecasting and stock market predictions, feel free to contribute or discuss improvements!

🔗 **GitHub Repository:** [Add your GitHub repo link here]

