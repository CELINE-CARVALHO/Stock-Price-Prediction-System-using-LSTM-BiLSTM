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
