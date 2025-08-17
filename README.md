# Time-series
# Time Series Analysis & Visualization in Python

This project demonstrates *time series data analysis and visualization* using Python, with a focus on stock market data.  
It covers preprocessing, statistical tests, visualization techniques, and transformations to prepare the data for forecasting models.

---

## 📌 Features
- *Data Preprocessing*  
  - Parsing dates into DatetimeIndex  
  - Handling missing values and unwanted columns  
  - Resampling daily data into monthly averages  

- *Exploratory Analysis & Visualization*  
  - Line plots for stock price trends  
  - Autocorrelation Function (ACF) plots for seasonality detection  
  - Moving averages for smoothing fluctuations  

- *Statistical Techniques*  
  - *Augmented Dickey-Fuller (ADF) Test* for stationarity check  
  - *Differencing* to remove trend and achieve stationarity  
  - Comparison of original vs transformed data  

---

## 🛠 Technologies Used
- *Python*  
- *Pandas, NumPy* (data manipulation)  
- *Matplotlib, Seaborn* (visualization)  
- *Statsmodels* (time series analysis)  

---

## 📂 Project Workflow
1. *Load Data* → Import CSV with stock data and parse Date column.  
2. *Clean Data* → Drop irrelevant columns and handle missing values.  
3. *Visualize Trends* → Plot stock "High" prices over time.  
4. *Resample Data* → Monthly averages to highlight long-term trends.  
5. *Seasonality Detection* → ACF plot to detect repeating patterns.  
6. *Stationarity Test* → Run ADF test on original and differenced data.  
7. *Transform Data* → Apply differencing and moving averages for smoothing.  

---

## 📊 Example Outputs
- Line plots of stock prices over time  
- Monthly resampled stock prices  
- Autocorrelation plots (seasonality detection)  
- Stationarity check with ADF test  
- Smoothed data using moving averages  

---

## 🚀 How to Run
1. Clone the repository: https://github.com/BYaswanth-code/Time-series.git
   ```bash
  
  
   

Credits: This project is inspired from https://www.geeksforgeeks.org/data-analysis/time-series-data-visualization-in-python/
