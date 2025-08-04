# Netrum Lite Node Guide

**Netrum Lite Node** is a lightweight, resource-efficient node for participating in the decentralized Netrum AI network. By running a Lite Node, you help maintain network integrity, contribute to AI tasks, and earn NPT tokens.

---

## 680 Features

- Simple, fast deployment 1 suitable for beginners and experts.
- Secure EVM wallet integration for identity and rewards.
- Decentralized compute and mining on the Netrum AI network.
- Cross-platform CLI for complete control and monitoring.
- Automatic rewards for uptime and participation.

---

## 6e0 System Requirements

![System Requirements for Netrum Lite Node](https://ppl-ai-code-interpreter-files.s3.amazonaws.com/web/direct-files/814fdfa740df2cd9f5a466361c7c46e1/261efc61-51cf-4a7d-ab55-2f1bc014df5e/3e0cfe2d.png)

---

## 6e0 Prerequisites

- Linux-based VPS or dedicated server (recommended for 24/7 uptime)
- Registered base domain name (for node identification)
- EVM-compatible wallet (e.g., MetaMask, TrustWallet)
- Some ETH in your wallet (for gas fees)

---

## 4e6 Installation

1. **Update your server:**
   ```bash
   sudo apt update && sudo apt upgrade
   ```

2. **Clone the official repository:**
   ```bash
   git clone https://github.com/flakz/netrum.git
   ```

3. **Install dependencies:**
   ```bash
   cd netrum-light-node
   npm install
   npm link
   ```

---

## 512 Wallet Setup

- **Create a new wallet:**
  ```bash
  netrum new-wallet
  ```
  *Backup your seed phrase safely.*

- **Import an existing wallet:**
  ```bash
  netrum import-wallet
  ```

---

## 310 Base Domain & Node Registration

1. **Verify your base domain is linked:**
   ```bash
   net check basename
   ```

2. **Get your Node ID:**
   ```bash
   netrum node-id
   ```

3. **Sign and register your node:**
   ```bash
   netrum node sign
   netrum node register
   ```

---

## 4a1 Running the Node

1. **Sync with the network:**
   ```bash
   netrum sync
   netrum sync log
   ```

2. **Start mining:**
   ```bash
   netrum mining
   netrum mining log
   ```

---

## 4b8 Earning Rewards

- Keep your node online to earn NPT tokens.
- Rewards are based on uptime and network participation.

---

## 512 Security

- Store your wallet seed phrase and keys **safely**.
- Never share private keys or sensitive information.

---

## 91d Community & Support

- [Official Website](https://netrumlabs.com)
- [Documentation](https://netrumlabs.com/blog/Netrum-Lite-Node-introduction/)
- [YouTube Tutorials](https://www.youtube.com/@NetrumLabs)

Join the Netrum community for updates, questions, and collaboration.

---

**Start contributing to decentralized AI 1 deploy your Netrum Lite Node today!**

