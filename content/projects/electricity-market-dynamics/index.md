---
title: Electricity Market Dynamics under Renewable Integration
date: '2026-06-01'
summary: A time-series study of load forecasting, renewable-energy interactions, electricity-price dynamics, and market volatility.
tags:
  - Time series analysis
  - Electricity markets
  - Renewable energy
  - Volatility modeling
---

This project conducts an integrated time-series analysis of the DE-AT-LU day-ahead electricity market using 32,849 hourly observations from 2015 to 2018. It examines electricity-load forecasting, renewable-energy integration, price dynamics, and market volatility.

An enhanced SARIMAX model incorporates renewable generation, calendar effects, and Fourier harmonics, reducing the out-of-sample MAPE from 18.73% to 11.45%. VAR models, Granger-causality tests, impulse-response functions, and forecast-error variance decomposition are used to study dynamic interactions among wind generation, solar generation, electricity load, and day-ahead prices.

The project also develops an ARX(7)-GARCH(1,1)-skew-t model to capture persistent volatility, heavy tails, and asymmetric downside risk. The analysis indicates that supply-demand fundamentals explain 28.8% of 20-day price uncertainty.
