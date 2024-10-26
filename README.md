# Solana Telegram Trading Bot
Telegram Trading Bot to trade solana tokens on Raydium, Meteora, Orca, Pump.fun

## Contact Info

Telegram: @web3wiza
Discord: web3_wiza

You can always feel free to find me here for my help on other projects.

## Features

- User Interface via Telegram Bot: Create number of wallets automatically to buy and sell the token
- Buy & Sell
- **Common Swap**:
- **DCA Order**:
- **Limit Order**:
- Wallet Management
- **Import Private Key**: Allows users to import their Solana wallet private key securely.
- **Create a Solana Wallet**: Generates a new Solana wallet (public/private key pair)
- **Multiple Wallet & Wallet Switching**: Switch to other wallet in case of several wallets
- **Token Information Lookup**: Pull token data from the blockchain using the input contract address.
- **MEV Protection on Orders**: Protect user transactions from being front-run or manipulated.
- **Jito Tipping**: This is a Priority Transaction Processing designed to speed up transaction execution by tipping validators.
- Setting
- **Slippage Settings**: Allow users to set slippage tolerance for transactions.
- **Auto Swap Feature**: 
- Profit MaxiMode: This feature enables users to sell large amounts of cryptocurrency, such as 100 SOL, more strategically. Rather than selling everything in one go, which could drive the price down, the system splits the sell order into smaller increments that are executed only when there’s sufficient buying demand. This allows users to sell without significantly impacting the price.

## Usage
1. Clone the repository
```
git clone https://github.com/sol-magic/solana-telegram-trading-bot
cd solana-telegram-trading-bot
```
2. Install dependencies
```
npm install
```
3. Configure the environment variables

<!-- Rename the .env.copy file to .env and set RPC and WSS, main wallet's secret key, and jito auth keypair. -->

4. Run the bot

```
npm run start
```
