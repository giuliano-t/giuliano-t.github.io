---
layout: default
title: "JP Morgan Credit Default Predictor"
stack: "Python, XGBoost, FastAPI, Docker"
priority: "major"
date: 2025-01-03
github: https://github.com/giuliano-t/jpmorgan-credit-default-app
live: https://jpmorgan-credit-default-predictor.onrender.com
---

# JP Morgan Credit Default Predictor

This project was developed as a spin-off of the [**JP Morgan Chase & Co. Quantitative Research Virtual Internship**](https://www.theforage.com/simulations/jpmorgan/quantitative-research-11oc).  
The goal was to build a reliable model that predicts the probability of a customer defaulting on a credit payment — a key task in minimizing financial risk and improving lending decisions.  

The work combines two parts:
- **Analysis & Model Selection:** a full Jupyter Notebook workflow, including EDA, feature engineering, handling class imbalance, and hyperparameter tuning. I compared a classic **XGBoost** model with a **Deep Learning** approach (TensorFlow/Keras) to identify the best performer.  
- **Deployment as a Web App:** the chosen model was integrated into a production-style **FastAPI** application, containerized with **Docker**, and deployed to **Render** for real-time credit risk prediction.

[🔗 View on GitHub](https://github.com/giuliano-t/jpmorgan-credit-default-app)

[🌐 Live](https://jpmorgan-credit-default-predictor.onrender.com)
