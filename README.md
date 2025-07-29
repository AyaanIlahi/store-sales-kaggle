# Store Sales – Kaggle Competition  
**Time Series Forecasting with Feature Engineering and Gradient Boosting** 📈

Solution for the [Store Sales – Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting) competition.  
The challenge: predict daily sales across multiple stores using historical data, promotions, and external factors.

## 📓 Notebook
- [`store_sales_notebook.ipynb`](store-sales.ipynb) – EDA, feature engineering, LightGBM training, and evaluation.  

## ⚙️ Approach
- **LGBMRegressor** with time‑based lags, rolling means, and holiday indicators.  
- Tuned parameters: `n_estimators=1000`, `max_depth=10`, `num_leaves=128`; optimized using **RMSLE**.
- 
## 🧠 Learnings
Enhanced skills in **time series forecasting**, **feature engineering**, and **RMSLE evaluation**;  
next steps: explore deep learning models and advanced feature tuning.
