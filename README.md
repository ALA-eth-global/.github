<div align="center">

<img width="893" height="279" alt="Gemini_Generated_Image_qe3q9yqe3q9yqe3q-removebg-preview" src="https://github.com/user-attachments/assets/a7528cfa-ac50-4cfd-a613-1fc665559e79" />

# ALA: Autonomus Liquidity Agents

**AMM built by a network of data scientists**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Ethereum Sepolia](https://img.shields.io/badge/Deployed-Ethereum%20Sepolia-blue)](https://sepolia.etherscan.io)

</div>

---

## 🌟 About ALA

### 🎯 Core Features

- ✅ **Dynamic Fees**: Real-time fee adjustments based on market conditions
- ✅ **Rehypothecation**: Automatic capitalization of idle funds in ERC4626 vaults
- ✅ **AI-Powered Analytics**: Data-driven decision making with The Graph AMP
- ✅ **Delta Management**: Spread capture and value optimization
- ✅ **Threshold System**: Intelligent rebalancing optimization

---

## 📦 Repositories

Our codebase is organized into specialized repositories:

### 🔗 Core Components

| Repository | Description | Status |
|------------|-------------|--------|
| **[ala-protocol](https://github.com/ALA-eth-global/ala-protocol)** | Uniswap V4 Hook implementation with dynamic fees and rehypothecation | 🟢 Active |
| **[data](https://github.com/ALA-eth-global/data)** | Data service for fetching market data from The Graph and DefiLlama | 🟢 Active |
| **[frontend](https://github.com/ALA-eth-global/frontend)** | Next.js frontend for model creation, testing, and analytics | 🟢 Active |
| **[testing](https://github.com/ALA-eth-global/testing)** | Backtesting engine for strategy evaluation and alpha calculation | 🟢 Active |
| **[model-creation-example](https://github.com/ALA-eth-global/model-creation-example)** | Example pipeline for creating and testing trading strategies | 🟢 Active |

---

## 🚀 Quick Start

### Prerequisites

- [Foundry](https://getfoundry.sh/) for smart contract development
- [Node.js](https://nodejs.org/) for backend and frontend services
- Access to Ethereum Sepolia testnet

### Getting Started

1. **Clone the protocol repository:**
   ```bash
   git clone https://github.com/ALA-eth-global/ala-protocol.git
   cd ala-protocol
   git checkout feature/eth-sepolia
   ```

2. **Install dependencies:**
   ```bash
   forge install
   ```

3. **Deploy to Ethereum Sepolia:**
   ```bash
   forge script script/DeployALAHook.s.sol --rpc-url sepolia --broadcast --verify
   ```

For detailed setup instructions, visit the [ala-protocol README](https://github.com/ALA-eth-global/ala-protocol).


---

## 🔗 Deployed Contracts

The ALA Protocol has been successfully deployed on **Ethereum Sepolia**:

- **ALADynamicFeeHook**: Main hook contract with dynamic fee logic
- **PoolExecutor**: Utility contract for operation execution
- **ERC4626 Vaults**: Rehypothecation vaults for WETH and USDC

📋 **Full deployment details**: [ala-protocol/README.md#deploy-on-chain-ethereum-sepolia](https://github.com/ALA-eth-global/ala-protocol#-deploy-on-chain-ethereum-sepolia)

---

## 📈 Alpha Generation

[ALA_hackathon (3).pdf](https://github.com/user-attachments/files/23695049/ALA_hackathon.3.pdf)

Our backtesting engine calculates **Alpha (α)** using the official evaluation metric:

$$
\alpha = \frac{\text{NAV}_{\text{strat}}(T) - \text{NAV}_{\text{bench}}(T)}{\text{NAV}_{\text{bench}}(T)}
$$

Where:
- $\text{NAV}_{\text{strat}}(T)$: Net Asset Value of the ALA strategy at time T
- $\text{NAV}_{\text{bench}}(T)$: Net Asset Value of the static benchmark at time T

Learn more in our [testing repository](https://github.com/ALA-eth-global/testing).

---

## 📚 Documentation

- **[Protocol Documentation](https://github.com/ALA-eth-global/ala-protocol)**: Smart contract implementation and deployment
- **[Data Service](https://github.com/ALA-eth-global/data)**: API endpoints and data fetching
- **[Frontend Guide](https://github.com/ALA-eth-global/frontend)**: User interface and model creation
- **[Testing Engine](https://github.com/ALA-eth-global/testing)**: Backtesting and alpha calculation
- **[Model Creation](https://github.com/ALA-eth-global/model-creation-example)**: Strategy development pipeline

---

## 🤝 Contributing

We welcome contributions! Please see individual repository READMEs for contribution guidelines.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/ALA-eth-global/ala-protocol/blob/main/LICENSE) file for details.

---

## 🔍 Resources

- **Etherscan Sepolia**: [View Transactions](https://sepolia.etherscan.io)
- **The Graph**: [Subgraph Explorer](https://thegraph.com)
- **Uniswap V4**: [Documentation](https://docs.uniswap.org)

---

<div align="center">

**Built with ❤️ for the Ethereum ecosystem**

[Website](#) • [Documentation](#) • [Discord](#) • [Twitter](#)

</div>

