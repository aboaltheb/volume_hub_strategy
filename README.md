# Volume Hub – TradingView Strategy (Pine Script v5)

**Volume Hub** is a Pine Script **strategy** designed for XAUUSD/Gold trading on TradingView.  
It combines a trend-flip engine with ATR/Percent Take-Profit and Stop-Loss management, MACD cloud filtering, and multiple position control.

## 🧩 Features
- Adaptive ATR-based trend continuation logic  
- Take Profit & Stop Loss via ATR or Percent  
- Prevent multiple simultaneous positions  
- MACD cloud overlay (EMA high/low ribbons)  
- Entry, SL, and TP labels for visual clarity  
- Alert for trend-direction changes  

## ⚙️ Inputs
- Sensitivity Multiplier (0.5–5)  
- ATR Length & Method  
- TP/SL Mode (ATR or Percent)  
- Cloud Moving Average Length  
- Position Management Toggle  

## 📈 How to Use
1. Open TradingView → **Pine Editor** → paste `VolumeHub.pine`.  
2. Click **Add to Chart** → open **Strategy Tester**.  
3. Adjust sensitivity, ATR, and TP/SL for your preferred timeframe (e.g., 5m or 15m).  

> Note: This script is for educational and analytical use only. Backtest results don’t guarantee future performance.

## 📂 Files
- `VolumeHub.pine` – Full strategy code  
- *(Optional)* `sample_chart.png` – Example chart screenshot  

## 👤 Author
Developed by **Mohamed AL-dahwa**  
FinTech & Trading Systems Developer  
📧 mohamedaldahwa@gmail.com  

## 📜 License
MIT License – open to modify and credit.
