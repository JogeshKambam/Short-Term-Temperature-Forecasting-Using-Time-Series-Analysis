# Short-Term Temperature Forecasting

This project focuses on short-term temperature forecasting using historical daily weather data. 
The goal is to predict next-day and short-horizon (7-day) average temperatures using time-series analysis techniques.

---

## 📌 Project Overview
- Built as a **personal data science project**
- Uses historical station-based temperature observations
- Applies time-series feature engineering and machine learning
- Designed for short-term forecasting and trend analysis

---

## 📊 Dataset
- Daily average temperature (TAVG) data
- Time period: 2000 – 2025
- A daily date index was reconstructed to enable time-series analysis

---

## ⚙️ Methodology
- Data cleaning and preprocessing
- Creation of lag features (previous days)
- Rolling averages for capturing trends
- Time-aware train-test split
- Random Forest regression model for prediction

---

## 📈 Results
- Good performance for **next-day and 7-day forecasts**
- Accuracy decreases for longer horizons due to error accumulation
- Visual comparison of actual vs predicted temperatures used for evaluation

---

## 🚧 Limitations
- Uses only temperature data
- Does not include other atmospheric variables (humidity, pressure, wind)
- Not intended for long-term or synoptic-scale weather prediction

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📌 Conclusion
This project demonstrates how time-series feature engineering combined with machine learning can effectively support short-term temperature forecasting using historical data.

---

## 📬 Author
Personal project by Jogesh Kambam.
