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

The workflow began with **time-series diagnostics** such as seasonal decomposition and autocorrelation analysis. I then implemented a range of models — from **Auto-ARIMA** to **XGBoost** and an **LSTM neural network** — to capture seasonality and long-term trends.  

Results showed that **advanced models outperformed classical methods**, with **XGBoost reducing forecast error significantly compared to Auto-ARIMA**, especially in capturing complex seasonal fluctuations.

![Sales Forecast Comparison Chart](/assets/images/book_forecast_chart.png)

![Sales Forecast Comparison Chart](/assets/images/book_performance_chart.png)

---

## Tech Stack

- **Models**: Auto-ARIMA, XGBoost, LSTM  
- **Libraries**: Python, Pandas, Statsmodels, Scikit-learn, TensorFlow/Keras  
- **Tuning**: Keras Tuner, Grid Search  

---

<p>
  <a href="https://github.com/giuliano-t/Book-Sales-Forecasting-with-Deep-Learning" class="btn">
    View on GitHub
  </a>
</p>

