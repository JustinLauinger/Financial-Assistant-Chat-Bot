# Financial Assistant Chatbot (Streamlit + OpenAI + yfinance)

Streamlit chatbot that answers stock questions and calls tool functions for price, SMA/EMA, RSI, MACD, and a 1-year price chart.

---

## Features

- Chat UI with **function calling** to run:
  - `get_stock_price(ticker)`
  - `calculate_SMA(ticker, window)`
  - `calculate_EMA(ticker, window)`
  - `calculate_RSI(ticker)`
  - `calculate_MACD(ticker)` → MACD, signal, histogram
  - `plot_stock_price(ticker)` → saves and shows `graph.png`
- Live market data via **yfinance**
- Minimal dependencies

---

## Requirements

- **Python 3.10+**
- Packages:
  - `openai`, `pandas`, `matplotlib`, `streamlit`, `yfinance`


