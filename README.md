---

### 🍵 4️⃣ NSE Tata Global Beverages — Multivariate LSTM
```markdown
# 🍵 NSE Tata Global Beverages — Multivariate LSTM

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge)
![LSTM](https://img.shields.io/badge/Model-Multivariate%20LSTM-orange?style=for-the-badge)
![Equity](https://img.shields.io/badge/Domain-Equity%20Market-green?style=for-the-badge)

## 📘 Overview
Predicts **next-day closing price** of NSE Tata Global Beverages using multivariate LSTM  
with **technical indicators and liquidity features**.

---

## 📊 Dataset
**Attributes:** Date, Open, High, Low, Close, Volume, Turnover  
**Goal:** Predict next-day Close  
📁 *Path:* `Datasets/Main 4.csv`

---

## 🧠 Model
LSTM(128) → Dropout(0.3) → LSTM(64) → Dense(1)
Features: RSI, MACD, ATR, SMA, Volume Trends

yaml
Copy code
**Metrics:** RMSE, MAE, MAPE  
**Baselines:** Univariate LSTM, ARIMA  

---

## 🚀 Run the Project
```bash
git clone https://github.com/pranaychowdary765/-NSE-Tata-Global-Beverages-.git
cd NSE-Tata-Global-Beverages
pip install -r requirements.txt
python main.py
📈 Result Summary
Indicator-based multivariate model shows improved accuracy and slice stability under varying liquidity.


