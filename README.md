# BitOptions

On-chain options trading protocol for the Stacks ecosystem. **BitOptions** leverages Clarity smart contracts to enable the creation, purchase, and exercise of decentralized call and put options.

## 🎯 Overview

**BitOptions** brings advanced financial derivatives to the Stacks network. Users can write options to earn premiums or buy options to hedge their portfolios, all within a trustless and secure environment backed by Bitcoin's finality.

## 🚀 Key Features

### 📉 Options Trading
- Flexible call and put options for SIP-010 tokens.
- Customizable strike prices and expiration dates.
- Fully collateralized writing to ensure contract fulfillment.

### 💰 Yield Generation
- Option writers can earn premiums on their idle assets.
- Automated payout logic based on settlement prices.

### 🛡️ Secure Infrastructure
- Non-custodial management of all collateral.
- Integrated with BitSettlement for reliable contract execution.

## 🧱 Architecture

- **Smart Contracts**: Core options logic (`options-contract.clar`).
- **Frontend**: Next.js App Router for a professional trading interface.
- **Network**: Stacks Mainnet.

## 🛠️ Tech Stack

- **Language**: Clarity, TypeScript
- **Framework**: Clarinet, Next.js
- **Styling**: Tailwind CSS
- **Integration**: @stacks/connect

## 📁 Project Structure

```
BitOptions/
├── smartcontract/          # Option protocols and settlement traits
│   ├── contracts/          # Core options logic
│   └── tests/              # Verification suite
│
└── frontend/               # Next.js web application
    ├── app/                # Trading dashboard
    └── components/         # Orderbook and charts
```

## 📝 License

MIT License - Developed by Richiey1
## Roadmap
