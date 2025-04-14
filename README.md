# Raydium Volume Bot

A powerful bot that boosts SPL token volume on Raydium by distributing SOL to multiple wallets and executing automated buy/sell operations.

## Features

| Feature | Description |
|---------|-------------|
| **Automated Wallet Creation** | Creates multiple wallets automatically for trading operations |
| **Automated SOL Distribution** | Distributes SOL efficiently to all generated wallets |
| **Endless Buy/Sell Operations** | Conducts continuous trading to boost volume metrics |
| **Configurable Parameters** | Customize buy amounts, intervals, distribution settings, and more |

## Quick Start

| Step | Command/Action |
|------|----------------|
| 1. Clone repository | `git clone https://github.com/crypto-artisan/solana-volume-bot-v1.git` |
| | `cd solana-volume-bot-v1` |
| 2. Install dependencies | `npm install` |
| 3. Configure settings | Rename `.env.copy` to `.env` and set your parameters |
| 4. Start the bot | `npm run start` |

### Environment Configuration

Rename the `.env.copy` file to `.env` and configure:
- RPC and WSS endpoints
- Main wallet's secret key
- Jito auth keypair (if using)

## Version Comparison

| Feature | Version 1 | Version 2 | Version 3 |
|---------|-----------|-----------|-----------|
| Wallet Handling | Fixed wallets with repetitive actions | Dynamic wallet creation | Advanced wallet rotation |
| Transaction Speed | Standard | Enhanced | 20 tx/second (500 tx/minute) |
| Maker Numbers | Limited | Increased | Maximized |
| Buy/Sell Ratio | Equal | More buys than sells | Optimized for market conditions |
| SOL Gathering | Collects tokens | Sells tokens first, then gathers SOL | Advanced management |
| Privacy | Detectable patterns | Improved obfuscation | No repeated makers |
| Throughput | Limited | Higher | 1M+ volume per hour possible |

## Version 2 Improvements

| Issue in Version 1 | Solution in Version 2 |
|-------------------|---------------------|
| ❌ **Repetitive wallet usage** | ✅ **Dynamic wallet creation** - Transfers to new wallets after operations |
| ❌ **Limited maker count** | ✅ **Automatic maker increase** - New wallets for each round |
| ❌ **Inefficient token gathering** | ✅ **Smart gathering** - Sells tokens first, reclaims rent (0.00203 SOL) |
| ❌ **Equal buy/sell ratio** | ✅ **Buy pressure emphasis** - Random double buys before selling |

## Version 3 Capabilities

Version 3 delivers extreme performance with:
- 500 transactions per minute 
- 20 transactions per second
- No repeated maker patterns
- Potential for millions in volume per hour

### Live Example

View Version 3 in action: [DexScreener Example](https://dexscreener.com/solana/boisf5dnefrbsodmiupkpauglaggx9gdjl1csgmcjqnn)

---

For access to Version 2 or 3 (private repositories), please contact me via Telegram.

## Contact

- [Telegram](https://t.me/JohnDAT0218)
- [Github](https://github.com/crypto-artisan)