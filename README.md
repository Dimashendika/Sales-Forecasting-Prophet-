# Sales Forecasting Using Prophet – Rossmann Stores

This project uses **Facebook Prophet** to forecast daily sales for Rossmann stores. The model captures seasonality trends to support better business planning in inventory, staffing, and promotions.

## 📦 Dataset
- Source: [Rossmann Store Sales – Kaggle](https://www.kaggle.com/c/rossmann-store-sales/data)
- Format: Multiple CSV files (sales, store info)
- Size: ~1 million rows of historical sales data across multiple stores

## 🛠 Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Prophet (Facebook)

## 🎯 Objective
- Forecast daily sales using Prophet
- Understand sales patterns and seasonality
- Support data-driven decisions in operations and marketing

## 🔍 Methodology
1. Data Cleaning & Merging
2. Exploratory Data Analysis (EDA)
3. Time Series Formatting for Prophet
4. Model Training & Forecasting
5. Interpretation & Recommendations

## 📊 Key Insights

- 🎄 **Christmas season** drives sales and customer peaks — strong yearly seasonality.
- 📅 **Monday** sees the highest sales, mid-week dips, and slight weekend recovery — clear weekly pattern.
- 📉 The **24th** shows the lowest traffic, while the **30th and 1st** spike — likely due to salary cycles.
- ❗ Outliers outside the forecast band suggest **unlogged external events** like holidays or promotions.
- 📈 Forecast confidence intervals widen over time — highlighting the need for regular model updates.

## ✅ Recommendations

- 🛒 Prioritize **inventory and staffing** around early-week and December peaks.
- 🎯 Launch **mid-week promotions** to improve low-traffic days.
- 📆 Include **special events and holidays** as regressors in future Prophet models.
- 🔁 Use **rolling forecasts** with regular updates to maintain accuracy.
- 📦 Plan **safety stock buffers** during uncertain periods to reduce stockouts.

## 📍 Conclusion

Prophet successfully captures Rossmann's sales seasonality and provides a reliable forecasting baseline. These insights enable smarter **resource allocation**, **marketing strategies**, and **supply chain planning** to meet customer demand effectively.
