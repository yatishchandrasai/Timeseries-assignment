# Timeseries-assignment

# Oil Price Forecasting Case Study

Predict daily WTI crude prices (Jul 2020–Dec 2022) and produce 24-month forecasts using:
- **Classical** Box–Cox → ARMA(7,1,7)  
- **Deep Learning** Stacked LSTM

Out-of-sample evaluation uses actual prices to June 2025 (RBRTEd.xls).

---

## 📖 Description

This project demonstrates how to:
1. **Clean & preprocess** real-world commodity data  
2. **Stabilize variance** (Box–Cox) and enforce stationarity (differencing)  
3. **Select & fit** an ARMA model via AIC grid search  
4. **Build & train** a multilevel LSTM for sequence forecasting  
5. **Evaluate & compare** models using RMSE and diagnostic plots  
6. **Embed domain knowledge** (pandemic shocks, OPEC decisions, inventory reports, seasonality, volatility) to interpret results and guide future enhancements

---



