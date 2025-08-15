# Auto Daily Check-in

This project automates the daily check-in process for a wallet collection API. It retrieves a nonce, logs in, checks wallet status, updates points, and collects wallet data.

## Project Structure

```
auto-daily-checkin
├── src
│   ├── index.js          # Main entry point of the application
│   └── utils
│       └── api.js       # Utility functions for API calls
├── package.json          # NPM configuration file
└── README.md             # Project documentation
```

## Disclaimer
This bot is **not for sale or resale**. It is open source, free to use, and intended for personal and educational purposes only. Do not buy or sell this bot.

## Setup Instructions (Step-by-step)

1. **Clone the repository:**
   ```
   git clone https://github.com/yogiprayoga1313/auto-cekin-aprio.git
   cd auto-cekin-aprio
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Create a `.env` file in the project root:**
   This file will store your private key and Monad RPC URL securely.
   Example content:
   ```
   PRIVATE_KEY=YOUR_PRIVATE_KEY_HERE
   MONAD_RPC_URL=https://testnet-rpc.monad.xyz
   ```
   - Replace `YOUR_PRIVATE_KEY_HERE` with your wallet's private key (keep it secret!).
   - Replace `https://testnet-rpc.monad.xyz` with a valid Monad RPC endpoint.

4. **Run the bot:**
   ```
   node src/index.js
   ```

---

## About This Bot

This project is an advanced auto check-in bot for APR.IO, developed and maintained by thedropsdata.online.

### Features
- Fully automated daily check-in for APR.IO
- Smart contract interaction on Monad chain
- Automatic login, nonce signing, and point update
- Clean and informative terminal output
- Open source and easy to customize

### Why use this bot?
- Save your time, never miss a check-in
- No manual interaction needed
- Secure: runs locally with your own wallet
- Free and open for everyone

### Join the Community
Register and explore more tools at [https://thedropsadata.online](https://thedropsadata.online)
More features and bots coming soon. Register now and be part of the next generation of web3 automation!