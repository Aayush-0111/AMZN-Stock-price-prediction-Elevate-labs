# AMZN-Stock-price-prediction-Elevate-labs
<br>

# 📈 LSTM Stock Price Predictor

This project implements a **Long Short-Term Memory (LSTM)** model using **PyTorch** to predict Amazon (AMZN) stock closing prices based on historical data.

---

## 🔍 Overview

The model learns temporal patterns in historical stock data using a lookback window and predicts the next day's closing price. It uses a PyTorch-based LSTM model trained and evaluated on scaled and windowed time series data.

---

## 🧠 Model Features

- PyTorch-based LSTM implementation
- Lookback window for time series context
- Min-Max Scaling of input data
- GPU acceleration (`cuda`) if available
- Visualizations of actual vs. predicted prices
- Inverse-transformed predictions for interpretability

---

## 📁 Dataset

Download the dataset from: [Google Drive Link](https://drive.google.com/file/d/1MqY9yaql1XQbodFSngsHxGbyLdWRhVXj/view)


---

## 🛠️ Requirements

Install required libraries using:

```bash
pip install pandas numpy matplotlib scikit-learn torch

---


