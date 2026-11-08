# FENIX PRO ULTIMATE TERMINAL

**Developed by Ashfak Arya**

Unified Multi-Broker Indian Stock Market Trading Terminal, Real-Time Stock Search & Market Watch Engine, Paper & Live Trading Suite across 15 Indian Brokers, and AI Hedge Fund Multi-Agent Quantitative Research Platform.

## Features
- **15 Supported Indian Brokers**: Zerodha, Upstox, Angel One, Fyers, Dhan, Alice Blue, Finvasia, 5paisa, IIFL, Kotak Neo, Mastertrust, Motilal Oswal, Anand Rathi, Symphony, Groww.
- **Real-Time Stock Search & Live Ticker**: Instant lookup across NSE, NFO, BSE, and MCX with live LTP fetching.
- **Advanced Candlestick Charting**: Multi-timeframe selection (`1m`, `5m`, `15m`, `1H`, `1D`), color themes, and technical indicator overlays (`EMA 20`, `VWAP`, `RSI`).
- **Separate Paper vs. Live Trading Workspaces**: ₹10,00,000 virtual portfolio with full order book, trade book, and live margin calculation.
- **AI Hedge Fund 7-Agent Committee & Strategy Backtester**: Automated multi-agent investment evaluation and quantitative backtesting.

## Deployment on Render
1. Create a new Web Service on Render and link this repository.
2. Build Command: `pip install -r requirements.txt`
3. Start Command: `uvicorn fenix_app.main:app --host 0.0.0.0 --port $PORT`
