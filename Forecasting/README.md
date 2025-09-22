# Time Series Forecasting

### This folder contains R scripts and R Markdown files focused on large-scale time series forecasting, developed for a Kaggle-style competition. The work applies and compares multiple forecasting models across hundreds of series with varying horizons and frequencies.

### What’s Inside

#### Baseline Forecasting

Simple benchmarks such as Naive forecasts and ETS models to establish a performance baseline.

#### Advanced Models

TBATS for handling trend and complex seasonalities.

ARIMA, Auto ARIMA, and ARIMAX with variants (log and filtered).

Regression-based approaches including linear and polynomial regression.

#### Cross-Validation & MAE Tracking

Training/test splits to evaluate forecast accuracy.

Calculation of Mean Absolute Error (MAE) for each series.

Residual diagnostics to assess model fit and white noise assumptions.

#### Kaggle Submission

Automated pipeline to forecast 600 series and generate predictions in Kaggle submission format (Id, Predicted).

### Purpose

This project reflects my interest in forecasting and applied time series modelling. I wanted to practice building, tuning, and evaluating models at scale, and to understand the trade-offs between model complexity, accuracy, and leaderboard performance.

It’s a place where I:

-  Test different forecasting approaches across diverse datasets.

-  Explore how parameter tuning impacts MAE and generalization.

-  Learn how forecasting competitions balance theory, automation, and performance.
