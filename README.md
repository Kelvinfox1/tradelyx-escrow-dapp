# 🚀 TradeLyX Escrow DApp

A blockchain-powered escrow system for secure agricultural transactions on the TradeLyX marketplace using Ethereum and USDC stablecoins.

## 🌍 Context

This system aims to remove trust barriers in cross-border agri-trade, enabling farmers and buyers in Africa (e.g. Kenya, Nigeria) to safely transact with automated, tamper-proof escrow powered by smart contracts.

## 🧱 Technologies Used

- Solidity (Smart Contracts)
- Ethereum / Arbitrum (L2 options)
- USDC (ERC-20 stablecoin)
- React + Ethers.js (Frontend)
- M-Pesa / TransFi API (Fiat On-Ramp)
- Chainlink (Optional Oracle)

## 📁 Structure

- `contracts/` — Escrow smart contract
- `frontend/` — React-based DApp UI
- `scripts/` — Deployment and interaction scripts
- `docs/` — Documentation and whitepapers
- `project_roadmap.md` — Developer roadmap and task board

## 🚀 Getting Started

```bash
# Install backend dependencies
npm install --prefix contracts/

# Install frontend dependencies
cd frontend && npm install

# Compile contracts
npx hardhat compile
