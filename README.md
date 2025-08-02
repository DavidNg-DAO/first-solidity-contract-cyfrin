# SimpleStorage Smart Contract 🚀

![Solidity](https://img.shields.io/badge/Solidity-0.8.18-blue)
![License](https://img.shields.io/badge/License-MIT-green)

My first Solidity smart contract deployed on Ethereum Sepolia testnet, completed as part of the [Cyfrin Updraft](https://updraft.cyfrin.io/) course taught by [Patrick Collins](https://twitter.com/PatrickAlphaC).

## 📜 Contract Overview
A simple smart contract that demonstrates:
- Storing and retrieving unsigned integers on-chain
- Basic Solidity syntax and structure
- Ethereum transaction lifecycle

## 🛠️ Tech Stack
- **Language**: Solidity 0.8.18
- **Tools**: Remix IDE
- **Network**: Ethereum Sepolia Testnet

## 🌐 Deployment Details
- **Transaction Hash**: [0x162a...60615](https://sepolia.etherscan.io/tx/0x162a91a8f59664cbffa7332fc5bceea5bac974664147750f925d8f48ebd60615)
- **Contract Address**: [View on Etherscan](https://sepolia.etherscan.io/address/YOUR_CONTRACT_ADDRESS)

## 📖 Usage
### Interact via Remix:
1. Compile `SimpleStorage.sol`
2. Deploy to Sepolia testnet
3. Call these functions:
   ```javascript
   // Store a number
   await simpleStorage.store(42);
   
   // Retrieve the number
   await simpleStorage.retrieve(); // Returns: 42
