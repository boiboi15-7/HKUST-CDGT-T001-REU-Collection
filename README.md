# HKUST-CDGT-T001-REU-Collection
The repository for the REU NFT collection created by messigoat10 on the Sepolia testnet

# Reu NFT Collection

An ERC-721 NFT smart contract deployed on the Ethereum Sepolia Testnet featuring IPFS metadata integration and pseudo-random attribute generation.

---

## 🚀Contract Overview

- **Network:** Ethereum Sepolia Testnet
- **Contract Address:** `0x3F624c103e523A475ddb15f4dF616F263F3407e5`
- **Token Standard:** ERC-721 (OpenZeppelin)
- **Solidity Version:** `0.8.34`
- **Metadata Storage:** IPFS (via Pinata)

---

## ✨ Features

- **ERC-721 Compliant:** Built on battle-tested OpenZeppelin standards for secure token minting and ownership tracking.
- **Decentralized Storage:** Artwork and JSON metadata hosted on IPFS via Pinata to ensure data permanence.
- **On-Chain Pseudo-Randomness:** Generates unique token characteristics on-chain during the minting transaction.

---

## 🛠️ How to Deploy & Interact in Remix

### 1. Deployment
1. Open [Remix IDE](https://remix.ethereum.org/).
2. Load `ReuNFT.sol` into your workspace.
3. Select Solidity Compiler version `0.8.34` and compile.
4. Under **Deploy & Run Transactions**, select **Injected Provider - MetaMask**.
5. Input your IPFS Base URI (`ipfs://bafybeifrff6yjyf7esz4rsfusasdjbxmckfm3a3ch7qvbm756usovunoze/`) as the constructor argument and click **Transact**.

### 2. Minting Tokens
- Execute `requestNFT()` under **Deployed Contracts** in Remix to mint a token (Token ID `0`).
- Check token supply using `totalSupply()`.
- Retrieve random assignment details via `s_randomWords(0)`.

---

## 🔗 Verification Links

- **Sepolia Etherscan:** `https://sepolia.etherscan.io/address/0x3F624c103e523A475ddb15f4dF616F263F3407e5`
- **IPFS Base Metadata:** `ipfs://bafybeifrff6yjyf7esz4rsfusasdjbxmckfm3a3ch7qvbm756usovunoze/0`
