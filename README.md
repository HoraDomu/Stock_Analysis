# 📊 Stock Analysis & Volatility Analyzer

A Python-based tool that provides **two main functions**:

1. **Stock Analyzer** – Opens a window where you can input a stock ticker and view detailed data.  
2. **Volatility Analyzer** – Requires [IBKR Trader Workstation](https://www.interactivebrokers.com/en/trading/ib-api.php). Once installed, it can pull live data on the selected stock and analyze its volatility.  

---

## 🚀 Features
- Simple, interactive GUI for stock lookup.
- Volatility analysis powered by IBKR Trader Workstation.
- Built with Python — latest version recommended.
- Lightweight and efficient (tested with real trades).
- Currently in **beta** – subject to change as improvements are made.

---

## 📦 Requirements
- [Python (latest version)](https://www.python.org/downloads/)
- Required modules (most should install without issue):
  - `tkinter`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `yfinance`
  - `ibapi`
  - `scipy`

Install all dependencies with:
```bash
pip install -r requirements.txt
