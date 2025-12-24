# Raydium Copy Trading Bot

A high-performance copy trading bot for Solana, leveraging Raydium AMM pools and gRPC for ultra-low latency trade execution.

## Features

- **Copy Trading:** Automatically mirrors trades from a master account to follower accounts.
- **Raydium AMM Integration:** Executes trades on Raydium pools for deep liquidity and fast settlement.
- **gRPC Communication:** Uses gRPC for efficient, low-latency messaging between components.
- **Typescript:** Written in TypeScript for type safety and maintainability.

## Getting Started

### Prerequisites

- Node.js (v16+)
- Yarn or npm
- Solana CLI
- Raydium SDK

### Installation

```bash
git clone https://github.com/Rabnail-SOL/raydium-grpc-copytrading-bot.git
cd raydium-grpc-copytrading-bot
yarn install
```

### Configuration

1. Copy `.env.example` to `.env` and fill in your Solana wallet and RPC details.
2. Update `config.ts` with your desired trading pairs and settings.

### Running the Bot

```bash
yarn start
```

## Usage

- The bot listens for trades on a master account and replicates them on follower accounts in real time.
- All trades are executed via Raydium AMM pools for optimal speed and price.

## Contributing

Pull requests are welcome! For major changes, please open an issue first.

## Support & Contact

For questions, support, or collaboration inquiries:

- **Telegram**: [@solzarr](https://t.me/solzarr)
- **X(twitter)**: [@solzarr](https://x.com/0xmarcus0401)

## License

MIT

---

*This project is not affiliated with Raydium or Solana. Use at your own risk.*
