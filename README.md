# 📊 Liquor Store Sales Forecast & Inventory Optimization (2018–2023)

This project uses historical sales data from 2018–2022 to **forecast 2023 revenue** and generate **inventory stocking recommendations** for a liquor store business. It combines time series forecasting (ARIMA & LSTM) with profit analysis and seasonal trends to help maximize revenue and optimize stock planning.

---

## 📁 Dataset Overview

The dataset includes over 20,000+ transactions from 2018 to 2022, with the following fields:

- `Date`
- `Item Purchased`
- `Brand`
- `Category`
- `Quantity`
- `Unit Price`
- `Total Amount`
- `Cost`

---

## 🔍 Project Objectives

1. **Forecast monthly revenue for 2023** using ARIMA and LSTM.
2. **Identify top-performing items** by revenue and margin.
3. **Generate month-wise stocking recommendations** based on:
   - Historical quantity sold
   - Seasonal demand patterns
   - Year-over-year growth
4. **Calculate expected profit margins and ROI** for the stocking plan.
5. **Export reports** including:
   - 📦 `liquor_store_2023_stocking_plan.csv`
   - 📄 `liquor_store_executive_summary_2023.txt`

---

## ⚙️ Techniques Used

- **Time Series Forecasting**
  - ARIMA modeling (Statsmodels)
  - LSTM deep learning (TensorFlow/Keras)

- **Data Analytics & EDA**
  - Monthly trends, category breakdowns, profit margin analysis
  - ABC inventory analysis

- **Visualization**
  - Plotly Dashboards: Revenue trends, forecast comparisons, category analysis

---

## 🧠 Key Business Insights

- Q4 is consistently the **peak season** (Oct–Dec)
- Spirits and Wine categories generate the highest **profit margins**
- Stocking plan includes **20% safety stock buffer** for demand volatility
- Forecasted ROI on 2023 inventory: **~XX%** (based on model)

---

## 📈 Results

- Forecasted 2023 Revenue: **$X,XXX,XXX**
- Inventory Investment Recommendation: **$XXX,XXX**
- Expected Profit: **$XXX,XXX**
- Top Items: Red Wine, Whiskey, Cigarettes (based on profitability & volume)

---

## 📦 Deliverables

| File                                | Description                                   |
|-------------------------------------|-----------------------------------------------|
| `RJS_Liquor_Sales_2018_2022.csv`    | Cleaned transaction data (2018–2022)          |
| `liquor_store_2023_stocking_plan.csv` | Monthly stocking recommendations              |
| `liquor_store_executive_summary_2023.txt` | Business summary for 2023 planning         |
| Notebook `.ipynb`                   | Full code, visualizations, and analysis steps |

---

## 🚀 How to Run

1. Upload `RJS_Liquor_Sales_2018_2022.csv` to your Colab or local Jupyter environment.
2. Run the notebook step-by-step.
3. Review forecast charts and exportable reports.
4. Adjust inventory plan assumptions as needed (growth %, safety stock).

---

## 🏷️ Author

**Raj Sun (RJS Inc.)**  
Liquor Store Revenue Optimization – 2023 Planning  
Built with Python, Pandas, TensorFlow, Plotly, and 💡 business logic
