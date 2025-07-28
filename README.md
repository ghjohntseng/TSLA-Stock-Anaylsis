# TSLA Stock Analysis 📈

This project performs **automated pattern recognition and strategy suggestion** on Tesla (TSLA) stock price data using Python. It identifies **key turning points**, fits **trend channel lines**, and detects **symmetrical triangle patterns** to generate **trading signals**, including **visualization**, **backtesting**, and even **alert messages**.

---

## 🚀 Features

- 📦 **Data Acquisition**: Fetches 6 months of 1D interval TSLA data via `yfinance`
- 📈 **Pattern Detection**:
  - Detects local maxima and minima (swing highs/lows)
  - Uses linear regression to draw upper and lower trend lines
  - Identifies symmetrical triangle formations (converging trend lines)
- 🧠 **Strategy Engine**:
  - Automatically calculates breakout direction (up or down)
  - Suggests entry price, stop loss, and take profit targets
- 📊 **Multi-panel Visualization**:
  - Price and inflection points
  - Triangle pattern with trend lines
  - Backtested signal overlay
- 🔔 **Breakout Alerts**: Console alerts when a triangle breakout occurs
- 🧪 **Simple Backtest**: Evaluates signals and plots them for review
- 🧹 **All floating-point and Series errors resolved**

---

## 🛠️ Dependencies

```bash
pip install yfinance pandas numpy matplotlib scikit-learn
