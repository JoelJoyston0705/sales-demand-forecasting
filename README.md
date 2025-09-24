# Sales Demand Forecasting

## 📌 Problem
Forecast product demand to optimize inventory and reduce stockouts.

## 📊 Dataset
- [Store Item Demand Forecasting - Kaggle](https://www.kaggle.com/c/demand-forecasting-kernels-only)

## 🔧 Tech Stack
- Python (Prophet, LSTM, Pandas, NumPy)
- Flask / Streamlit
- Matplotlib / Plotly

## 🚀 Approach
1. Clean and prepare time-series data
2. Apply Prophet for baseline forecasting
3. Build LSTM deep learning model
4. Deploy forecasting tool as a web app

## 📈 Results
- Prophet RMSE ~300
- LSTM improves forecast accuracy
- Interactive tool for CSV uploads

## 📂 Repository Structure
sales-demand-forecasting/
│── data/              # raw CSVs
│── notebooks/         # EDA & testing notebooks
│── src/               # scripts: preprocessing, Prophet, LSTM
│── results/           # plots, metrics, outputs
│── app/               # Flask/Streamlit web app
│── README.md          # project description
│── requirements.txt   # dependencies
│── .gitignore         # ignore temp files

## ✨ Future Work
- Add hyperparameter tuning for LSTM model
- Deploy the Streamlit app online
- Include real-time inventory data for forecasting
- Explore Prophet model enhancements


## ✨ Future Work
- Deploy on Heroku
- Add ARIMA + hybrid models


