# Canadian Gasoline CPI Forecasting

This project analyzes and forecasts monthly gasoline prices in Canada using time series methods in R.

## 📊 Project Overview
- Forecast range: Jan 2000 – Feb 2025
- Data Source: Statistics Canada
- Goal: Forecast Gasoline CPI for March 2025 to February 2026

## 🧪 Methods Used
- ARIMA
- Exponential Smoothing (ETS)
- Drift, Mean, and Seasonal Naive models
- Data transformations (Box-Cox, Differencing)

## 📈 Best Model
- ETS(M,A,A) had the best performance (MAPE = 2.85%)

## 📁 Project Files
- `project.Rmd` — Code notebook with full analysis
- `data/` — Cleaned CPI dataset
- `visualizations/` — All plots and model diagnostics
- `final-report.docx` — Written summary of methods and results

## 🔍 Forecast Insight
The ETS model forecasts gasoline CPI to remain stable with seasonal peaks in summer months.

---

> Built with R, tidyverse, forecast, and other time series packages.

