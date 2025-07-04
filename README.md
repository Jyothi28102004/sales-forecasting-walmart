# sales-forecasting-walmart
Real-time time series sales forecasting using Prophet and Walmart dataset

# 🛒 Sales Forecasting using Walmart Dataset

A real-time, end-to-end time series forecasting project using Python and Meta Prophet model. This project predicts future sales at Walmart stores, helping plan inventory and logistics with data-driven insights.

---

## 📌 Objective

To build a forecasting model that predicts future monthly sales per store, enabling Walmart (or similar retailers) to:
- Optimize inventory levels
- Manage supply chain demands
- Minimize overstock or understock
- Support data-backed business planning

---

## 🗃️ Dataset Description

Three CSV files from [Walmart Store Sales Forecasting dataset](https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting/data):

1. `train.csv`  
   - Contains historical weekly sales data
   - Columns: Store, Dept, Date, Weekly_Sales, IsHoliday

2. `features.csv`  
   - Additional data: Temperature, Fuel_Price, CPI, Unemployment, etc.

3. `stores.csv`  
   - Metadata on each store: Store Type, Size

---

## 🧠 Technologies & Tools

- **Python** (Pandas, Numpy, Matplotlib, Seaborn)
- **Meta Prophet** (Time Series Forecasting)
- **ARIMA** (optional comparison)
- **scikit-learn** (evaluation metrics)
- **Google Colab**
- **GitHub**

---

## 🧪 Project Phases

### ✅ Phase 1: Data Preparation & Cleaning
- Merged `train`, `features`, and `stores` on Store/Date
- Converted weekly data to monthly format
- Aggregated sales per store/month
- Handled missing values
- Standardized column names
- Removed outliers

### ✅ Phase 2: Exploratory Data Analysis (EDA)
- Time series decomposition (trend, seasonality)
- Monthly sales trends per store
- Heatmaps and line plots
- Correlation between economic indicators and sales

### ✅ Phase 3: Forecasting with Prophet
- Forecasted sales using Prophet per store
- Tuned seasonality, changepoints
- Used `ds` and `y` format (Prophet requirement)
- Visualized forecasts, holidays, trends

### ✅ Phase 4: Evaluation
- Compared forecasts with actual sales
- Used RMSE and MAE
- Plotted predicted vs actual sales

---

## 📊 Visualizations

- Sales trend over time (overall + per store)
- Monthly sales seasonality
- Prophet forecast components (trend, weekly, yearly)
- Actual vs Forecast comparison

(Include charts in an `images/` folder or link them here)

---


📌 Real-World Applications
Retail Planning: Stock optimization

Demand Forecasting: Across branches

Business Strategy: Budget allocation

Supply Chain: Scheduling logistics


Author
Jyothi Bhaskar Vardhi
LinkedIn: www.linkedin.com/in/jyothivardhi
GitHub: Jyothi28102004
