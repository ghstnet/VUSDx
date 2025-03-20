**README.md**

# vUSDx Stablecoin

**vUSDx** (Vault USDx) is a decentralized, vault-backed stablecoin pegged to the US Dollar. It is designed for secure and permissioned use within DeFi protocols, particularly ISO-compliant trade bots like **ISO TradeBot**. This token represents a synthetic wrapper around stable assets like USDT or USDC, with a vault-locking mechanism embedded into its economic model.

## ✨ Features
- Pegged to USD via Chainlink price feed
- Admin-mintable and burnable for flexibility in token issuance
- Blacklist and pause functionalities for security
- Designed for use in automated trading systems (e.g., ISO TradeBot)
- Available on both Ethereum and BNB Smart Chain

## 💡 Use Case
vUSDx serves as the primary payment token for the ISO TradeBot ecosystem, allowing users to earn and transact in a dollar-pegged token backed by locked value or conditions.

## 🔑 Security & Control
- Blacklist function to prevent malicious use
- Pausable contract for emergency control
- OpenZeppelin smart contract standards

## 🔢 Tech Stack
- Solidity 0.8.20
- OpenZeppelin Contracts
- Chainlink Oracle
- Remix / Hardhat / Etherscan /

## ⚖️ Token Info
| Property | Value |
|--|--|
| **Token Name** | Vault USDx |
| **Symbol** | vUSDx |
| **Decimals** | 18 |
| **Network** | Ethereum |
| **Type** | ERC20 |

## ✨ Verified Contracts
- [Ethereum Mainnet]()
- [BNB Smart Chain]()

## ⚡ Logo & Metadata
Token metadata and logos have been submitted to TrustWallet, MetaMask, and major listing services. [See /assets/logo.png](./assets/logo.png)

---

## ✨ How to Use
```solidity
IERC20 vusdx = IERC20(0x2e55e55B2A69b2eb26eedb275b4FD6fB6098AaAa);
vusdx.transfer(to, amount);
```

## 📋 License
[MIT](./LICENSE)

## 📈 Roadmap
- [x] Token deployment & verification
- [x] Chainlink USD price integration
- [x] Uniswap + PancakeSwap liquidity pool
- [x] GitHub metadata & logo publishing
- [ ] Website + dApp interface
- [ ] Centralized exchange integration

---

## 📚 Resources
- [Submit logo to TrustWallet](https://github.com/trustwallet/assets)
- [Submit metadata to MetaMask](https://docs.metamask.io/wallet/how-to/add-token/)
- [Chainlink Price Feed Docs](https://docs.chain.link/data-feeds)

---

**Made with ❤️ by GHST & ISO TradeBot Labs**
