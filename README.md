# 🥑 Avocado Price Forecasting with Prophet

## 📌 Overview

This project utilizes the [Facebook Prophet](https://facebook.github.io/prophet/) library to perform time series forecasting on avocado prices in the United States. Using historical data, we analyze trends, seasonality, and predict average prices for the next 365 days.

---

## 📊 Dataset

The dataset includes the following key features:
- `Date`: The date of the record
- `AveragePrice`: The average price of avocados on that date
- `year`: Extracted from the date for visual analysis

> *Note: The dataset is preprocessed and sorted by date before applying the model.*

---

## ⚙️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `prophet` (formerly fbprophet)

---

## 🚀 Forecasting Process

1. **Data Preprocessing**
   - Sort dataset by date
   - Rename columns for Prophet compatibility (`ds`, `y`)
   
2. **Exploratory Data Analysis**
   - Line plot of price over time
   - Count plot of records per year

3. **Modeling**
   - Train Prophet model on historical data
   - Generate future dataframe (365 days ahead)
   - Predict future prices
   - Visualize predictions and Prophet components (trend, seasonality)

---

## 📈 Sample Output

- **Price Forecast Plot**  
  ![Forecast](forecast_plot.png)

- **Trend & Seasonality Components**  
  ![Components](components_plot.png)

---

## 🧠 Insights

- Prophet successfully identifies trends and seasonal cycles in avocado pricing.
- This type of analysis can help retailers, wholesalers, and economists plan better for future market conditions.

---


