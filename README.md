# 🕵️ Chicago Crime Rate Forecasting with Prophet

This project uses **Facebook Prophet** to forecast monthly crime trends in the city of Chicago based on historical data from the Chicago Data Portal.

---

## 📌 Overview
The goal of this project is to model and forecast crime occurrences over time using Prophet, a powerful time series forecasting library developed by Meta.  
It explores trends, seasonality, and long-term patterns in Chicago crime data.

---

## 🧰 Tools & Libraries
- Python
- Pandas, NumPy
- Prophet
- Matplotlib / Plotly
- Jupyter Notebook

---

## 📊 Dataset
The dataset comes from the **[Chicago Data Portal - Crimes 2001 to Present](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2)**.  
Due to its large size (over 1GB), it is **not included** in this repository.

To run the notebook:
1. Download the dataset from the link above.
2. Place it in the same folder as the notebook file.

---

## ⚙️ Steps Performed
1. **Data Cleaning:** Parsed dates and aggregated crime counts by month.  
2. **Exploratory Analysis:** Visualized crime trends over time.  
3. **Forecasting:** Used Prophet to model and predict future monthly crime rates.  
4. **Visualization:** Displayed trend and seasonal components using Prophet’s built-in plots.

---

## 📈 Results
- Prophet successfully captured yearly and monthly seasonality in crime data.  
- Forecast visualizations show expected crime fluctuations and overall trends.
