# 📦 Amazon Grocery Demand Forecasting | Time Series ML (ARIMA + Prophet + XGBoost)

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

Forecasting grocery product demand using classical and machine learning time series models on a real-world retail dataset.  
Built entirely inside Kaggle using a subset-first approach to ensure performance.

---

## 🎯 Business Objective

Amazon Fresh faces inventory management issues due to erratic demand.  
This project aims to build an accurate **demand forecasting system** to minimize:

- 🛒 Overstocks and understocks
- 💰 Inventory-related losses
- 🚚 Supply chain inefficiencies

---

## 🧠 Models & Tech Stack

| Category          | Tools & Techniques                                           |
|-------------------|-------------------------------------------------------------|
| Classical Model   | ARIMA                                                       |
| Seasonal Model    | Prophet                                                     |
| ML Model          | XGBoost (with lag features)                                 |
| Language          | Python                                                      |
| Libraries         | pandas, matplotlib, seaborn, statsmodels, prophet, xgboost |
| Evaluation        | RMSE, MAE, MAPE                                             |

---

## 📊 Dataset Used

**[Store Sales - Time Series Forecasting (Kaggle Competition)](https://www.kaggle.com/competitions/store-sales-time-series-forecasting)**

Subset includes:
- Daily sales for one store and one product family  
- Date, holiday flags, promotional indicators  

---

## 🚀 Project Pipeline

1. **Data Loading & Cleaning**  
2. **Exploratory Data Analysis (EDA)** – trends, seasonality, decomposition  
3. **Time Series Preparation** – log transform, stationarity checks  
4. **Model Training**  
   - ARIMA  
   - Prophet  
   - XGBoost  
5. **Evaluation & Comparison**  
   - Metrics: RMSE, MAE, MAPE  
   - Forecast vs Actual visualizations  
6. **Conclusion & Business Insights**

---

## 📈 Model Performance

| Model    | RMSE ↓ | MAE ↓ | MAPE ↓ |
|----------|--------|--------|--------|
| ARIMA    | ✅ Moderate | ✅ Moderate | ⚠️ High    |
| Prophet  | ✅ Good     | ✅ Good     | ✅ Good     |
| XGBoost  | ⭐ Best     | ⭐ Best     | ⭐ Best     |

📌 XGBoost gave the most accurate forecast using lag + time features.

---

## 💡 Business Takeaways

- ML-based models (like XGBoost) outperform traditional ones in retail settings.
- Better forecasts help optimize inventory, reduce waste, and improve profit margins.
- Seasonal + promotional components are critical in demand patterns.

---

## 🔁 Future Improvements

- Expand from single store/family to full dataset
- Add external regressors (weather, events)
- Automate retraining + build deployment pipeline (Streamlit/Flask)
