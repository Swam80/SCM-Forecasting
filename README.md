# 🛒 Demand Forecasting & Inventory Optimization (Walmart Retail)

## 📌 Impact Summary

* Built an end-to-end demand forecasting pipeline at Store–Department–Weekly level
* Improved forecast accuracy by **XX% (WMAE reduction)** over baseline models *(to be updated)*
* Simulated inventory decisions to reduce **stockout risk and overstock** *(to be updated)*
* Identified key demand drivers: **holidays, promotions, and macroeconomic factors**

---

## 🎯 Business Problem

Retailers require accurate demand forecasts to optimize inventory planning and avoid stockouts or excess inventory.

This project focuses on forecasting weekly demand at the Store–Department level and translating predictions into actionable inventory decisions.

---

## 🎯 Objectives

* Build accurate demand forecasting models
* Identify key drivers of demand (holidays, promotions, macro factors)
* Compare baseline vs machine learning models
* Simulate inventory decisions using forecasts
* Evaluate impact using supply chain KPIs

---

## 📦 Dataset

* Historical weekly sales data from Walmart
* Data includes:

  * Store, Department, Date
  * Weekly Sales
  * Holiday indicator
  * Temperature, Fuel Price, CPI, Unemployment
  * Promotional markdowns

---

## 📊 Key Metrics

### Forecast Accuracy Metrics

* **WMAE (Weighted Mean Absolute Error)**
* **MAPE (Mean Absolute Percentage Error)**
* **RMSE (Root Mean Squared Error)**

### Supply Chain Metrics

* **Forecast Bias** = Forecast − Actual
* **Stockout Rate** = % of times Actual > Forecast
* **Overstock Rate** = % of times Forecast > Actual
* **Service Level (Fill Rate Proxy)** = min(Forecast, Actual) / Actual

---

## 🧠 Approach

1. **Data Cleaning & Merging**

   * Combined sales, features, and store datasets

2. **Exploratory Data Analysis**

   * Trend, seasonality, and store-level analysis

3. **Feature Engineering**

   * Lag features (weekly history)
   * Rolling statistics
   * Time-based features
   * Promotion intensity

4. **Baseline Models**

   * Naive forecast (last week)
   * Moving average

5. **Machine Learning Models**

   * Linear Regression
   * Random Forest
   * XGBoost

6. **Model Evaluation**

   * Compared using WMAE, MAPE, RMSE

7. **Inventory Simulation**

   * Converted forecasts into inventory decisions
   * Evaluated stockouts and overstock

---

## 📈 Results *(To Be Updated)*

* Best Model: **TBD**
* WMAE Improvement: **XX%**
* Stockout Reduction: **XX%**
* Overstock Reduction: **XX%**

---

## 🔍 Key Insights *(To Be Updated)*

* Holiday periods show significant demand spikes
* Promotions (markdowns) strongly influence sales
* Store size and type impact overall performance

---

## 🛠️ Tech Stack

* **Python** (Pandas, NumPy, Scikit-learn)
* **XGBoost**
* **Matplotlib / Seaborn**
* **Power BI / Tableau**

---

## 📁 Repository Structure

```
├── data/
├── notebooks/
├── src/
├── README.md
```

---

## 🚀 Future Improvements

* Implement deep learning models (LSTM, TFT)
* Incorporate real-time demand signals
* Optimize safety stock dynamically

---

## ▶️ How to Run

1. Clone the repository
2. Install required dependencies
3. Run notebooks in order

---

## 📬 Contact

For questions or collaboration, feel free to connect.
