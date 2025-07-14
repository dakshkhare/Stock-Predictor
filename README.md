# 📈 Bullgorithm — Stock Price Predictor with Streamlit

Welcome to **Bullgorithm**, a machine learning-powered stock price prediction app built with **TensorFlow**, **Streamlit**, and **yFinance**.

Whether you're a curious investor or an ML enthusiast, this project shows how to use deep learning to forecast future stock trends — all wrapped inside an interactive UI.

---

## 🧠 Tech Stack

- 🐍 **Python 3.10**
- 🔮 **TensorFlow / Keras**
- 📊 **yFinance** for real-time stock data
- 🌐 **Streamlit** for frontend deployment

---

## 📷 Screenshots

<img width="1362" height="852" alt="Image" src="https://github.com/user-attachments/assets/aefb67b5-94e3-41c4-a44f-9d28f11abf6d" />

<img width="1289" height="866" alt="Image" src="https://github.com/user-attachments/assets/70534a57-cc34-46a0-bf9e-074515b3ed0f" />

<img width="1269" height="873" alt="Image" src="https://github.com/user-attachments/assets/de639f4d-35c6-4a2d-b0ce-eb086a164eca" />

<img width="1339" height="878" alt="Image" src="https://github.com/user-attachments/assets/eed8387b-c9da-4aef-a196-9292dca79006" />

<img width="1258" height="876" alt="Image" src="https://github.com/user-attachments/assets/6d6e047d-899a-4768-a8f8-0c0fb2860d01" />

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
