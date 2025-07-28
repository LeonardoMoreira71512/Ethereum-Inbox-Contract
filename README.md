# 📬 Ethereum Smart Contract Project – Inbox

This project demonstrates how to create, test, and deploy a simple smart contract using **Hardhat**, **Solidity**, **Ethers.js**, and the **Ethereum Sepolia testnet**.

---

## 🔍 Overview

This project contains a basic smart contract called `Inbox`, which allows users to:

- ✅ Store a message on the blockchain  
- ✏️ Update that message  
- 🔎 View the current message  

The goal is to show the full development workflow of a smart contract using modern Ethereum development tools.

---

## 🛠 Technologies Used

| Tool        | Description                                      |
|-------------|--------------------------------------------------|
| **Hardhat** | Ethereum development environment (compiling, testing, deployment) |
| **Solidity**| Programming language for smart contracts         |
| **Ethers.js**| Interact with the blockchain & smart contracts  |
| **Web3.js** | Blockchain communication (optional/extra)        |
| **Chai**    | Assertion library for contract testing           |

---

## 📋 Prerequisites

### 🦊 MetaMask
- A browser wallet used to manage accounts and sign transactions  
- Required to connect to the **Sepolia** network  
- ⚠️ **Use a development wallet only** — never use your main wallet!  

### 🔌 Infura
- Ethereum node provider for sending transactions to Sepolia  
- Register at [https://infura.io](https://infura.io) and create a new project  
- Copy your Sepolia endpoint URL  

### 🧪 Sepolia ETH
- You will need **test ETH** to deploy the contract  
- Request test ETH via a Sepolia faucet:  
  👉 [https://sepoliafaucet.com](https://sepoliafaucet.com)

---

## 🚀 Project Setup

### 1. MetaMask Setup
- Install the MetaMask browser extension  
- Create a new development account  
- Connect to the **Sepolia** test network  
- Copy your **private key** (`Account Details > Show Private Key`) — this will be used in `.env`

### 2. Infura Setup
- Go to [infura.io](https://infura.io)  
- Create a project  
- Copy your **Sepolia endpoint URL**

### 3. Local Setup
```bash
# Clone the repository
git clone https://github.com/your-user/inbox-smart-contract.git
cd inbox-smart-contract

# Install dependencies
npm install

# Create .env file and add:
PRIVATE_KEY=your_private_key_here
INFURA_URL=https://sepolia.infura.io/v3/your_project_id_here
