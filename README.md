# R2Money-Auto-Bot

An automated bot for interacting with the R2 Money protocol on the Sepolia testnet. This bot allows users to perform swaps between USDC and R2USD tokens, as well as stake R2USD to receive sR2USD tokens.

## Features

- Swap USDC to R2USD
- Swap R2USD to USDC
- Stake R2USD to sR2USD
- Check token balances
- Support for multiple wallets
- Proxy support for IP rotation

## Prerequisites

- Node.js v16 or higher
- Ethereum wallet with private key
- Sepolia ETH for gas fees
- Sepolia USDC tokens

## Installation

1. Clone the repository:
```bash
git clone https://github.com/19seniman/r2-moneyy-new.git
cd r2-moneyy-new
```

2. Install dependencies:
```bash
npm install
```

3. Create an  nano .env file with your private key(s):
```
PRIVATE_KEY_1=your_private_key_here
PRIVATE_KEY_2=another_private_key_here
# Add more keys as needed
```

4. (Optional) Create a `proxies.txt` file with your proxies (one per line):
```
http://username:password@host:port
http://host:port
```

## Usage

Run the bot with:

```bash
node index.js
```

