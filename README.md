
# EDA - Time Series Models in Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![ML](https://img.shields.io/badge/ML-Time%20Series-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

A complete hands-on project on **Exploratory Data Analysis (EDA) and Time Series Forecasting** using real-world datasets. This repository demonstrates the journey from raw time-dependent data to accurate future predictions using ARIMA & SARIMA models.

### 🔗 Live Project: [Google Colab Notebooks](https://github.com/munawirmt/EDA-Timeseries-models)

---

### 📌 Overview

Time Series data is everywhere - from stock prices to flight passengers. This project focuses on:
- Understanding patterns, trends, and seasonality
- Handling non-stationary data
- Building and evaluating classical forecasting models

### 📂 Datasets Used

1.  **Microsoft Stock Data (MSFT)** - For financial time series analysis
2.  **Airline Passengers Dataset** - Classic dataset for seasonality & trend analysis
3.  `AirPassengers.csv` - Monthly airline passenger numbers

### 🛠️ Tech Stack & Models

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Statsmodels
- **Concepts:**
    - Exploratory Data Analysis (EDA)
    - Time Series Decomposition (Trend, Seasonality, Residual)
    - Stationarity Check (ADF Test)
    - **ARIMA** (AutoRegressive Integrated Moving Average)
    - **SARIMA** (Seasonal ARIMA)
- **Environment:** Google Colab

### 📁 Repository Structure
EDA-Timeseries-models/
├── ARIMA_&_SARIMA_Model.ipynb      # Main ARIMA & SARIMA implementation
├── EDA_Timeseries.ipynb            # Exploratory Data Analysis
├── Time_series_with_microsoft_data.ipynb # Forecasting on MSFT data
├── http://AirPassengers.csv               # Dataset
├── http://microsoft.csv                   # Dataset
└── http://README.md

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
