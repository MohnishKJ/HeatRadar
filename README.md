# HeatRadar 🌍

LSTM-based model that forecasts future temperature trends for major cities using historical climate data.

## 🚀 What it does
- Predicts temperature trends for any major city in the dataset
- Forecasts up to 12 months ahead
- Displays expected temperature as a min-max range per month
- Works on global historical climate data spanning decades

## ⚙️ How it works
- Loads and cleans historical city-wise temperature data with Pandas
- Normalizes temperature values using MinMaxScaler for LSTM input
- Uses a 12-month sequence window to predict the next month's temperature
- Recursively predicts further months by feeding predictions back into the sequence
- Converts scaled predictions back to actual temperature values
- Displays results in a clean tabular format using PrettyTable

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Scikit-learn
- PrettyTable

## 💡 Use case
Built to explore long-term temperature trends for cities and get a quick forecast without manually analyzing historical climate data.

# 📊 Screenshot
<img src="CCM.png" width="400">
