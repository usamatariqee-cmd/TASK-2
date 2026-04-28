# TASK-2
 Predict Future Stock Prices (Short-Term)

## Overview

This project uses **Python**, **Yahoo Finance data**, and **Machine Learning** to analyze and predict **Apple Inc. (AAPL)** stock closing prices. Historical stock data is collected using the `yfinance` library, explored through visualizations, and modeled using **Linear Regression**.

The notebook demonstrates a complete beginner-friendly workflow: data collection, exploratory data analysis (EDA), feature selection, model training, evaluation, and prediction.

## Objective

* Download historical stock market data.
* Perform exploratory data analysis.
* Understand relationships between stock features.
* Build a regression model to predict closing price.
* Evaluate model accuracy using standard metrics.

## Dataset Source

Data is retrieved from **Yahoo Finance** using the `yfinance` Python package.

**Ticker Used:** `AAPL` (Apple Inc.)
**Time Period:** Last 1 year of historical data.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels
* yfinance

## Project Files

* `TASK-2.ipynb` → Main notebook with full code, charts, and model.

## Workflow

### 1. Import Libraries

Libraries for data handling, visualization, and machine learning are imported.

### 2. Load Stock Data

Historical Apple stock data is downloaded using:

```python
import yfinance as yf
```

### 3. Exploratory Data Analysis (EDA)

The notebook checks:

* Dataset shape
* Number of records
  n- Missing values
* Statistical summary using `.describe()`
* Feature correlations using heatmap

### 4. Data Visualization

Charts included:

* Histogram of closing prices
* Boxplot for outlier detection
* Input feature distributions
* Scatter plots of features vs close price
* Correlation heatmap
* Residual distribution plot

### 5. Model Training

A **Linear Regression** model is trained using selected inputs:

* Open
  n- High
* Low
* Volume

Target variable:

* Close Price

### 6. Model Evaluation

Metrics used:

* R² Score
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)

### 7. Prediction

The model predicts closing prices from new input values.

## Key Learning Outcomes

* Financial data collection with APIs
* Data cleaning and EDA
* Correlation and multicollinearity analysis
* Regression model training
* Model evaluation techniques
* Predictive analytics basics

## How to Run

1. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels yfinance notebook
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open and run:

```bash
TASK-2.ipynb
```

## Future Improvements

* Try Random Forest Regressor / XGBoost
* Add multiple stocks comparison
* Forecast future dates using time-series models
* Deploy as a web dashboard

## Author
USAMA TARIQ
