# InternIntelligence_Advanced_time_forecating_with_prophet
This project focuses on identifying anomalies in sales data and forecasting future trends using two time-series models: **Prophet** and **ARIMA**. It combines statistical analysis, visualizations, and model performance tracking for better insight into sales patterns.

## 📁 Project Overview

- **Anomaly Detection:** Z-score, IQR, and rolling bounds methods.
- **Temporal Pattern Analysis:** Breakdown of anomalies by weekday and month.
- **Geographic Breakdown:** Store-level performance insights.
- **Forecasting Models:**
  - **Prophet**: With seasonality, holidays, and external regressors (oil prices).
  - **ARIMA**: Auto-optimized using `auto_arima`.
- **Evaluation:**
  - Rolling RMSE and MAPE metrics.
  - Residual analysis (distribution, ACF, QQ plots).
  - Time-based cross-validation.
- **Model Persistence:** Saved using `.pkl` for deployment/reuse.

## 🔎key visual outputs
- Anomaly comparison across Z-score, IQR, and rolling stats
- Weekly/Monthly anomaly trends
- Prophet forecast (trend + components)
- Prophet with oil price as external regressor
- ARIMA forecast plot
- Rolling RMSE / MAPE plots
- Residual distributions and ACF

## model files
- prophet_model.pkl – Advanced Prophet model
- arima_model.pkl – Trained ARIMA model

### to load a model
click this kaggle link, you will find it in the output section ready if you wanna load it.

##📌 Dependencies
- Python 3.8+
- Prophet
- pmdarima
- scikit-learn
- numpy / pandas / matplotlib / plotly / statsmodels
