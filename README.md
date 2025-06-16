# 🎲 Agent Odds – Telegram Web3 Betting Bot

Agent Odds is a Web3-powered Telegram bot and Mini App that allows group members to place verifiable bets on real-world events—right from the chat. Built on Base and powered by Chainlink, Agent Odds is your autonomous, trustless group betting agent.

> 🧠 “I bet $ETH crosses $4k by Sunday.”  
> Agent Odds parses it, verifies it with Chainlink Functions, and pays out on-chain.

---

## 🚀 Features

✅ Natural-language bet creation via Telegram  
✅ Telegram Mini App for bet customization and staking  
✅ On-chain escrow of funds (Base L2)  
✅ Chainlink Functions for real-world event resolution  
✅ Chainlink Automation for deadline tracking  
✅ Chainlink VRF for random winner selection in ties  
✅ Non-custodial, verifiable, and transparent

---

## 🔧 Tech Stack

| Component         | Stack                             |
|------------------|-----------------------------------|
| Telegram Bot      | Node.js + Telegram Bot API        |
| Mini App (UI)     | React + Tailwind + Telegram SDK   |
| Smart Contracts   | Solidity on Base L2               |
| Chainlink         | Functions, Automation, VRF        |
| Wallet Integration| WalletConnect                     |
| Off-chain Storage | PostgreSQL / Redis (optional)     |

---

# Clone the repo
git clone https://github.com/yourusername/agent-odds.git
cd agent-odds

# Install bot & backend
cd bot
npm install

# Install Mini App
cd ../miniapp
npm install
