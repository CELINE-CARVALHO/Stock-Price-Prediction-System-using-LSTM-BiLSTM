#  Stock Price Prediction System using LSTM & BiLSTM

An end-to-end **deep learning–based stock price prediction platform** that uses **LSTM and Bidirectional LSTM neural networks** to forecast future stock prices. The project includes automated data collection, feature engineering with technical indicators, model training, ensemble prediction, and an interactive **Gradio web interface**.

---

##  Features

- **Automated Stock Data Fetching** using Yahoo Finance (`yfinance`)
-  **Deep Learning Models**
  - LSTM
  - Bidirectional LSTM
  - Ensemble averaging for improved prediction stability
-  **Technical Indicators**
  - Simple Moving Average (SMA)
  - Exponential Moving Average (EMA)
  - Relative Strength Index (RSI)
  - Volume Change
-  **Interactive Gradio Web App**
  - Train models with live logs
  - Visualize actual vs predicted prices
  - Predict next-day stock price
  - Preview dataset
  - Download trained models & scalers
- **Model Persistence**
  - Keras `.keras` format
  - Scalers saved using Joblib
  - Downloadable ZIP archives

---

## Tech Stack

- **Programming Language:** Python
- **Libraries & Frameworks:**
  - TensorFlow / Keras
  - Scikit-learn
  - Pandas, NumPy
  - yfinance
  - Matplotlib
  - Gradio
- **Model Types:** LSTM, Bidirectional LSTM
- **Deployment:** Gradio Web Interface

---

##  Project Structure

```bash
├── app.py                     # Main application (Gradio UI + training pipeline)
├── stock_models/              # Saved models and scalers
│   ├── AAPL_lstm_saved_model/
│   ├── AAPL_bilstm_saved_model/
│   ├── AAPL_scaler.joblib
├── requirements.txt
├── README.md
```

## Installation & Setup
1. Clone the Repository
git clone https://github.com/your-username/stock-price-prediction.git
cd stock-price-prediction

2️ Install Dependencies
pip install -r requirements.txt

3️ Run the Application
python app.py


The Gradio app will launch in your browser.

 Model Training Pipeline

Download historical stock data (Yahoo Finance)

Generate technical indicators

Scale features using MinMaxScaler

Create time-series sequences

Train:

LSTM Model

Bidirectional LSTM Model

Save trained models & scalers

Ensemble predictions for final output

Prediction Output

The system predicts:

Next-day closing price

Expected percentage change

Validation plot (Actual vs Predicted prices)

Validation Visualization

80–20 train-test split

Line plots comparing actual vs predicted prices

Automatically generated within the app

Downloadable Artifacts

Trained LSTM model (.zip)

Trained Bidirectional LSTM model (.zip)

Scaler (.joblib)

Disclaimer

This project is for educational and research purposes only.
It should not be used for real-world financial or trading decisions.

Author

Celine Carvalho
GitHub: [https://github.com/CELINE-CARVALHO](https://github.com/CELINE-CARVALHO)

Future Improvements

Add Transformer-based models

Multi-day price forecasting

Hyperparameter tuning

Real-time data streaming

Cloud deployment (AWS / GCP)


---
