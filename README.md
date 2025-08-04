# Netrum Lite Node

Netrum Lite Node is a state-of-the-art, lightweight, and efficient node designed to empower participants within the decentralized Netrum AI ecosystem. By operating this node, you contribute to scalable AI computation, enhance network robustness, and earn NPT tokens proportionate to your uptime and active participation.

---

## Key Features

- Rapid, seamless installation optimized for both novice and advanced users
- Deep integration with EVM-compatible wallets ensuring secure identity verification and transparent rewards
- Facilitates decentralized AI workloads and mining operations
- Comprehensive CLI for full lifecycle node management: setup, sync, mining, monitoring
- Incentivized token rewards program based on node performance and uptime

---

## System Requirements

- Reliable Linux-based VPS or dedicated server with 24/7 uptime
- Registered base domain name for node identity management linked securely to your wallet
- An EVM-compatible wallet (e.g., MetaMask, TrustWallet) capable of managing transaction signing
- Sufficient ETH funds in the wallet to cover network gas fees associated with node registration and transactions

---

## Installation & Configuration

### 1. System Update & Pre-requisites Installation

Ensure your system packages are current and essential tools are installed.

```bash
sudo apt update && sudo apt upgrade -y
```

### 2. Clone Official Repository

Acquire the latest version of Netrum Lite Node from GitHub.

```bash
git clone https://github.com/netrumlabs/netrum-lite-node.git
```

### 3. Install Dependencies & Configure CLI

Navigate to the project directory, install necessary packages, and configure the CLI tool for your environment.

```bash
cd netrum-lite-node
npm install
npm link
```

---

## Wallet Setup

Proper wallet configuration is vital for node identity and reward mechanisms.

- To generate a new wallet:

```bash
netrum new-wallet
```
*Safeguard your seed phrase securely; it is essential for wallet recovery.*

- To import an existing wallet:

```bash
netrum import-wallet
```

*Input your private key with caution.*

---

## Domain Verification & Node Registration

### 1. Verify Base Domain Linked to Wallet

```bash
net check basename
```

### 2. Obtain Node Identifier

```bash
netrum node-id
```

### 3. Sign Ownership Proof Message

```bash
netrum node sign
```

### 4. Register Node on Netrum Network

```bash
netrum node register
```

---

## Node Operation

### 1. Initiate Network Sync

```bash
netrum sync
```

### 2. Monitor Synchronization Process

```bash
netrum sync log
```

### 3. Activate Mining Services

```bash
netrum mining
```

### 4. Review Mining Logs and Stats

```bash
netrum mining log
```

---

## Rewards & Performance Metrics

- Maintain an uninterrupted node to maximize your NPT token earnings.
- Rewards are dynamically calculated based on network participation, uptime, and computational contribution.

---

## Security Best Practices

- Protect your wallet’s seed phrase and private keys with industry-standard encryption and backup methods.
- Refrain from sharing sensitive credentials.
- Employ secure shell (SSH) access and firewall rules to harden your node server.
- Regularly monitor logs and node health to preemptively identify issues.

---

## Additional Resources & Community

- [Official Netrum Website](https://netrumlabs.com)
- [Comprehensive Documentation & Guides](https://netrumlabs.com/blog/Netrum-Lite-Node-introduction/)
- [Educational Video Tutorials](https://www.youtube.com/@NetrumLabs)
- Engage with the Netrum developer community for collaboration and support.

---

**Take a leading role in decentralized AI innovation — deploy your Netrum Lite Node today!**
