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

Make sure you have the latest version of **Python** installed.  

This project uses the following Python libraries:

- `tkinter` (standard library – included with Python)
- `threading` (standard library)
- `time` (standard library)
- `datetime` (standard library)
- `warnings` (standard library)
- `scipy` (specifically `scipy.stats.norm`)
- `pandas`
- `numpy`
- `ibapi`
- `yfinance`
- `matplotlib`

---

### Install Dependencies
You can install the required external libraries with:

```bash
pip install scipy pandas numpy ibapi yfinance matplotlib
---------------------------------------------------------------------------------------------------------

📈 Real-World Test

I tested this tool by investing $50 and netting $15 profit.
While that’s not life-changing, it shows the tool is functional and has real-world application potential.
---------------------------------------------------------------------------------------------------------

⚠️ Disclaimer

This project is for educational purposes only.
It’s still a work in progress — think of it as a beta version.
Use at your own risk when trading with real money.
----------------------------------------------------------------------------------------------------------
❤️ About This Project

This project is my personal baby — built by learning from books, tutorials, and hands-on trial and error.
It’s not perfect, but it works efficiently and will continue to evolve.
