
### 🚀 Key Features & Workflow

1.  **Data Cleaning & Visualization:** Handled missing values, plotted time series to identify patterns.
2.  **Stationarity Testing:** Used Augmented Dickey-Fuller (ADF) test and differencing to make data stationary.
3.  **Model Building:**
        -   Found optimal parameters (p,d,q) using ACF & PACF plots
        -   Implemented ARIMA for non-seasonal forecasting
        -   Implemented SARIMA for data with strong seasonality
4.  **Model Evaluation:** Evaluated using RMSE and visualized Predicted vs. Actual values.

### 📊 Results

- Successfully captured seasonality and trend from Airline dataset using SARIMA.
- Built a working forecasting model for Microsoft stock data with low error rate.
- Visual comparison shows models can predict future values with high accuracy for short-term forecasting.

### 💡 Key Learnings

- Difference between ARIMA and SARIMA and when to use which.
- Importance of making time series data stationary before modeling.
- How to interpret ACF/PACF plots for parameter tuning.

### 🔮 Future Improvements

- [ ] Add Deep Learning models: LSTM / Prophet
- [ ] Deploy as a Streamlit web app for interactive forecasting
- [ ] Add hyperparameter tuning with Auto-ARIMA

### 👨‍💻 Author

**Muhammed Munawir M T**
Aspiring Data Scientist | Machine Learning Enthusiast

- GitHub: [@munawirmt](https://github.com/munawirmt)
- LinkedIn: [Connect with me](https://www.linkedin.com/in/muhammed-munawir-m-t-45b31a286/)

---
⭐ If you found this project useful, please give it a star!
