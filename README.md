
# Product Demand Forecasting using Time Series (ARIMA & Prophet)

This project demonstrates demand forecasting for products using simulated SAP-like data. It applies two powerful time series models — ARIMA and Prophet — to forecast weekly demand by Material ID and Location.

## 📌 Project Objective

To simulate product demand across multiple locations and forecast future demand using time series analysis. This aligns with real-world demand planning scenarios in SAP IBP (Integrated Business Planning).

## 🛠️ Tools & Libraries
- Python, Pandas, NumPy
- Statsmodels (ARIMA)
- Facebook Prophet
- Matplotlib
- Jupyter Notebook

## 📁 Dataset

A synthetic dataset is generated to simulate weekly demand for 2 materials across 2 locations from 2021 to 2024. Columns include:
- `Material_ID`
- `Location`
- `Date`
- `Demand`

## 📈 Forecasting Models
### ARIMA:
- Trained ARIMA(1,1,1) model on weekly demand
- Plotted 12-week forecast horizon

### Prophet:
- Used Prophet to capture seasonality and trends
- Generated forecast and plotted confidence intervals

## 📊 Visualization
- Time series plots of historical demand and model forecasts
- Prophet's built-in forecasting visual

## 📦 Use Case
This project mimics SAP IBP functionality, providing value to supply chain analytics teams by demonstrating how predictive modeling can improve inventory and demand planning.

## 📄 Output
- Jupyter notebook with end-to-end modeling
- Forecast plots for decision support
- Exportable `.csv` files for Tableau dashboards

---

## ✅ How to Run

1. Clone the repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook product_demand_forecasting.ipynb
   ```

---

## 💼 Ideal For
- Data Science Portfolios
- Supply Chain Analytics Demonstrations
- Job Interviews in SAP IBP, S/4HANA, or data-driven demand planning roles
