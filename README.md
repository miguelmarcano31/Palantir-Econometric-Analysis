# Palantir-Econometric-Analysis
Econometric time series modeling (ARIMA) and multivariate VAR analysis on Palantir Technologies stock return &amp; volatility using R.

# 📈 Econometric Time Series & VAR Analysis: Palantir Technologies

## 📌 Executive Summary
This project delivers a comprehensive econometric study on **Palantir Technologies (PLTR)** analyzing stock return volatility, risk patterns, and market interdependence from 2022 to 2024. Using quantitative time-series methodology in **R**, the study models univariable return behavior, volatility clustering, and cross-asset spillovers with the **NASDAQ Composite Index**.

---

## 🛠️ Methodologies & Econometric Models Applied

### 1. Univariate Time Series & Volatility Modeling
- **Stationarity & Diagnostic Testing:** Applied Augmented Dickey-Fuller (ADF) and KPSS tests alongside Jarque-Bera normality tests.
- **Volatility Forecasting:** Fitted an $ARIMA(1,1,5)$ model to capture persistence and volatility clustering during macroeconomic stress periods.
- **Model Validation:** Verified residual white-noise behavior via Ljung-Box tests and ensured model invertibility/stationarity within the unit circle.

### 2. Bivariate VAR Framework & Market Interdependence
- **Vector Autoregression ($VAR(10)$):** Integrated daily NASDAQ returns as an exogenous variable to measure inter-market transmission.
- **Granger Causality:** Evaluated bidirectional lead-lag dynamics between Palantir and broader market indices.
- **Impulse Response Functions (IRF):** Analyzed Palantir’s dynamic response over a 10-day horizon to unexpected market shocks.

---

## 📁 Repository Structure
- `TRABAJO ECONOMETRÍA PALANTIR DEF.pdf`: Complete academic research report containing empirical results, charts, and financial analysis.


---

## 👨‍💻 Author
- **Miguel Marcano** – Business Analytics & Business Administration Student
