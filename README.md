# Opening Range High/Low Indicator (09:30–09:34 NY)

A **TradingView Pine Script v6** indicator that automatically plots the **Opening Range (OR) high and low** from the first five minutes of the regular U.S. market session (09:30–09:34:59 Eastern Time), then extends those levels horizontally until the market close at **16:00 NY time**.

---

## 📌 Features

- **Auto-detects Opening Range** for each trading day.
- Plots:
  - **Yellow line** at OR high.
  - **Red line** at OR low.
- Lines appear only after the OR window completes (09:35 NY onward).
- Lines reset daily and disappear after the session ends.
- Works with **stocks, futures, forex, and commodities**.
- Designed for **intraday timeframes** (1–60 minutes).
- NY time is fixed – no need for manual timezone settings.

---

## 🛠 How It Works

1. Tracks the highest and lowest prices between **09:30:00 and 09:34:59 NY**.
2. Locks in those prices once the OR window ends.
3. Extends horizontal lines from **09:35** to **16:00 NY**.
4. Resets the next trading day.

---

## 🎯 Use Cases

- Identify **key breakout/breakdown levels** for day trades.
- Combine with VWAP, volume, or trend filters for trade confirmation.
- Use as reference for **stop-loss** and **take-profit** placement.

---

## ⚙️ Inputs

| Input        | Description                               | Default  |
|--------------|-------------------------------------------|----------|
| High Line Color | Color of OR high line                   | Yellow   |
| Low Line Color  | Color of OR low line                    | Red      |
| Line Width      | Thickness of plotted lines              | 2        |

---

## 📷 Screenshot
*(Add a chart image here once tested in TradingView)*

---

## 📦 Installation

1. Open a chart in **TradingView**.
2. Click **Pine Editor** at the bottom.
3. Paste the contents of `OpeningRange_0930_0934_NY.pine`.
4. Click **Add to chart**.
5. Save to your scripts for future use.

---

## 📝 License
This project is released under the [MIT License](LICENSE).

---

## 💡 Author Notes
This script is optimized for day traders who rely on **Opening Range breakouts** as part of their strategy. Works on any instrument that trades through the U.S. equity open.
