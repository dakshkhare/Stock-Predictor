# 📈 Bullgorithm — Stock Price Predictor with Streamlit

Welcome to **Bullgorithm**, a machine learning-powered stock price prediction app built with **TensorFlow**, **Streamlit**, and **yFinance**.

Whether you're a curious investor or an ML enthusiast, this project shows how to use deep learning to forecast future stock trends — all wrapped inside an interactive UI.

---

## 🚀 Live Demo

👉 [Try it out here!](https://bullgorithm.streamlit.app)

---

## 🧠 Tech Stack

- 🐍 **Python 3.10**
- 🔮 **TensorFlow / Keras**
- 📊 **yFinance** for real-time stock data
- 🌐 **Streamlit** for frontend deployment

---

## 📷 Screenshots

![screenshot](https://github.com/dakshkhare/Bullgorithm/assets/your-screenshot-placeholder.png)

---

## 🛠 Features

- ✅ Predict future stock closing prices
- 📈 Fetches live stock data using ticker symbols
- 📦 Loads a pre-trained `.keras` model
- 🖥 Deployed on Streamlit Cloud

---

## 🏗️ How It Works

1. User inputs a valid **stock ticker** (e.g., AAPL, TSLA).
2. Live data is fetched via **yFinance**.
3. Data is preprocessed and passed to a trained **deep learning model**.
4. Prediction is displayed interactively on the Streamlit dashboard.

---

## 📁 Project Structure

```bash
├── models/
│   └── Stock Predictions Model.keras
├── app.py
├── requirements.txt
└── runtime.txt
