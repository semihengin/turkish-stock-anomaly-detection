# 📊 Stock Price Prediction & Anomaly Detection with LSTM and Isolation Forest

This repository contains a **deep learning-based stock price prediction model** using **Long Short-Term Memory (LSTM)** networks and an **anomaly detection model** using **Isolation Forest**. The goal is to predict stock prices based on historical data and detect anomalies in stock movements.

**📅 Project Completed: December 2023**

## 🚀 Project Overview
- **LSTM Models** (`LSTM_daily.ipynb` & `LSTM_weekly.ipynb`) predict future stock prices based on historical trends.
- **Isolation Forest Model** (`IsolationForest.ipynb`) detects outliers and unusual patterns in stock price movements.
- **Data Preprocessing & Visualization** ensure clean input for the models.
- Uses **TensorFlow**, **Scikit-Learn**, **Plotly**, and **Seaborn** for deep learning and visualization.

## 📂 Project Structure
```bash
├── data/                    # CSV datasets
├── notebooks/               # Jupyter Notebook files
├── reports/                 # Reports and research materials
├── src/                     # Python source code
├── README.md                # Project documentation
├── requirements.txt         # Required dependencies
└── .gitignore               # Git ignore file
```

## 📊 Data
The models utilize historical stock data, which should be placed in the `data/` directory. Ensure the dataset is in CSV format and contains the following columns:
- `Date`
- `Open`
- `High`
- `Low`
- `Close`
- `Adj Close`

### **2️⃣ Place the dataset**
Ensure your dataset (e.g., `XU100.IS.csv`) is inside the `data/` directory.

### **3️⃣ Run the Jupyter Notebooks**
Start Jupyter Notebook and open one of the following:
- `LSTM_daily.ipynb` → Daily stock price prediction
- `LSTM_weekly.ipynb` → Weekly stock price prediction
- `IsolationForest.ipynb` → Anomaly detection in stock movements

Modify parameters as needed for optimization.

## 📈 Model Architecture
### **LSTM-Based Stock Price Prediction**
- **Layers:**
  - LSTM layers to capture temporal dependencies
  - Dropout layers to prevent overfitting
  - Dense layers for final predictions
- **Loss Function:** Mean Squared Error (MSE)
- **Optimizer:** Adam

### **Isolation Forest for Anomaly Detection**
- Detects anomalies based on historical stock price patterns.
- Uses an unsupervised learning approach to identify unusual stock movements.
- Visualization highlights normal vs. anomalous trends.

## 📊 Results & Visualization
- **Stock price predictions** plotted using Matplotlib & Plotly.
- **Anomalies detected** using Isolation Forest are highlighted in different colors.

## 🏗️ Future Enhancements
- Implement GRU models for comparison with LSTM.
- Optimize hyperparameters using GridSearch.
- Extend dataset for more accurate predictions.

---
