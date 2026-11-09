# HGW_DPP_registery
# HGW Eco Smart System - Digital Product Passport (DPP) Registry

This repository contains the smart contract for the Digital Product Passport (DPP) registry, part of the HGW Eco Smart System (Reuse Market) - an AI & Web3 Powered Infrastructure for Circular Economy and Regenerative Finance (ReFi).

## 🚀 Live Deployment Details
- **Network:** Celo Sepolia Testnet (Chain ID: 11142220)
- **Contract Address:** `0xB928681Bd9aED3b2a338Ee9a13a34578B4fB2682`
- **Explorer Link:** [View on Celo Sepolia Blockscout](https://celo-sepolia.blockscout.com/address/0xB928681Bd9aED3b2a338Ee9a13a34578B4fB2682)

## 📜 Contract Features
- `registerDPP(string assetId, string dppHash)`: Registers a new DPP record for a physical asset (e.g., VIN, equipment ID).
- `getRecordCount(string assetId)`: Returns the number of records for a specific asset.
- `getLatestDPP(string assetId)`: Returns the latest hash and registrant address for an asset.
- Emits `DPPRegistered` event upon successful registration.

## 🛠 Tech Stack
- Solidity ^0.8.19
- Deployed via Web3GPT on Celo Sepolia
- Open Source (MIT License)