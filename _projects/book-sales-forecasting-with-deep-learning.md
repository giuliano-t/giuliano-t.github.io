---
layout: default
title: "Book Sales Forecasting with Deep Learning"
stack: "Python, Time Series, Forecasting, Deep Learning"
priority: "minor"
date: 2025-05-15
github: https://github.com/giuliano-t/Book-Sales-Forecasting-with-Deep-Learning
---

## Forecasting Book Sales to Guide Investment Decisions

Publishers face the challenge of anticipating future sales to optimize inventory, procurement, and marketing investments. This project developed and compared multiple forecasting models on historical book sales data to support those decisions.

The workflow began with basic **time-series analysis** such as seasonal decomposition and autocorrelation analysis. I then implemented a range of models — from **Auto-ARIMA** to **XGBoost** and **Long Short-Term Memory (LSTM)** neural networks — to fit the data and generate future predictions.

![Sales Forecast Comparison Chart](/assets/images/book_forecast_chart.png)

Results showed that **advanced models outperformed classical methods**, with **XGBoost reducing forecast error significantly compared to Auto-ARIMA**, especially in capturing complex patterns.

![Model Performance Comparison Chart](/assets/images/book_performance_chart.png)

---

## Tech Stack

- **Models**: Auto-ARIMA, XGBoost, LSTM  
- **Libraries**: Python, Pandas, Statsmodels, Scikit-learn, TensorFlow/Keras  
- **Hyperparameter Tuning**: Keras Tuner, Grid Search  

---

[🔗 View on GitHub](https://github.com/giuliano-t/Book-Sales-Forecasting-with-Deep-Learning)

