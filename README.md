# 📈 Crypto Price Prediction using Neural Networks (BTC & ETH)

This project focuses on forecasting the hourly and daily prices of Bitcoin (BTC) and Ethereum (ETH) using time-series data and deep learning models. It uses Recurrent Neural Networks (RNNs) to capture temporal dependencies in crypto market data.

🧠 **Core Model:** Neural Networks (RNN)  
📄 **Project Type:** Time Series Forecasting  
💰 **Target:** BTC / ETH closing prices

---

## 📁 Notebooks

| File | Description |
|------|-------------|
| `BTC Prediction.ipynb` | Predicts BTC closing price using hourly data and lag features |
| `BTC prediction Hours model.ipynb` | Alternative model architecture for short-term BTC hourly forecast |
| `ETH model.ipynb` | Predicts ETH prices using similar neural network architecture |

---

## 🔍 Methodology

- **Data Preprocessing**
  - Created lag features and normalized values using MinMaxScaler
  - Converted time-series to supervised learning format with sliding window
- **Modeling**
  - Built RNN model using `Sequential()` in Keras
  - Trained with MSE loss and early stopping
  - Tuned architecture: layers, neurons, dropout
- **Evaluation**
  - RMSE, MAE
  - Line plots comparing actual vs predicted prices

---

## 📊 Tools & Libraries

- Python, Pandas, NumPy
- Keras (TensorFlow backend)
- Matplotlib, Scikit-learn

---

## 💡 Key Takeaways

- Short-term BTC/ETH prices show temporal autocorrelation patterns
- Neural networks can capture trend well but may overfit on volatile price points
- Feature engineering (lags, normalisation) significantly affects performance

---

## 📌 Future Improvements

- Integrate sentiment data from Twitter or Reddit
- Experiment with LSTM / GRU / 1D-CNN
- Hyperparameter tuning via GridSearchCV or Optuna
- Deploy as a Streamlit dashboard

---

## 👤 Author

**Surapot Nonpassopon**  
MSc Data Science and Analytics – University of Leeds  
📂 GitHub Portfolio: [github.com/surapotsrp](https://github.com/surapotsrp)
