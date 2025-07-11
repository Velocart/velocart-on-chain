# Velocart On-Chain Contracts

Smart contracts for Velocart, built using Cairo for Starknet. These contracts manage product listings, purchases, and order data on-chain.

## 🧱 Tech Stack

- Cairo 1.0
- Starknet Foundry or Protostar
- Starknet CLI for deployment

## 📦 Contracts

- `ProductRegistry.cairo`: Stores and manages product info
- `OrderManager.cairo`: Handles purchases and order state
- `AccessControl.cairo`: (optional) Admin permissions

## 🚀 Getting Started

```bash
git clone https://github.com/your-org/velocart-onchain.git
cd velocart-onchain
```

### Using Foundry

```bash
snforge test
```

### Using Protostar

```bash
protostar build
protostar test
```

## 🚀 Deployment

```bash
starknet deploy --network sepolia --contract target/ProductRegistry.sierra.json
```

## 📁 Project Structure

```
contracts/
  └── ProductRegistry.cairo
  └── OrderManager.cairo
tests/
  └── test_product.cairo
```

## 🛡️ Security

- Input validation
- Access control on admin-only functions
- Future upgradability via proxies (planned)

## 📄 License

MIT © 2025 Velocart Team
