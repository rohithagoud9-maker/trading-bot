# Trading Bot (Binance Futures Testnet)

# Overview
This is a simple Python-based trading bot that connects to the Binance Futures Testnet using the python-binance library. It allows users to place market and limit orders in a safe test environment for learning purposes.
# Features
- Connects to Binance Futures Testnet
- Market Buy & Sell Orders
- Limit Buy & Sell Orders
- Secure API key handling using `.env`
- Simple menu-driven interface
- Basic logging system for tracking trades
# Tech Stack
- Python 3.x
- python-binance
- python-dotenv
# Project Structure
trading-bot/
│
├── trading_bot.py        # Main bot script
├── requirements.txt      # Dependencies
├── .env.example          # API key template
├── README.md             # Project documentation
└── trading_bot.log       # Auto-generated logs
#Setup Instructions
# 1. Clone the repository
cd trading-bot

### 2. Install dependencies
pip install -r requirements.txt

### 3. Setup environment variables
Rename `.env.example` to `.env` and add your API keys:

API_KEY=your_api_key
API_SECRET=your_api_secret

---

# Run the Bot
python trading_bot.py


 # How It Works
- Connects to Binance Futures Testnet
- Fetches account balance
- Places market or limit orders based on user input
- Logs all activity in `trading_bot.log`
  # Future Improvements
- Add trading strategies (RSI, EMA, MACD)
- Add stop-loss and take-profit
- Build GUI dashboard
- Add automated trading mode

- # author
- Ediga.Rohita Bhavya Saisri

## 👨‍💻 Author
Beginner Trading Bot Project for Internship Submission
