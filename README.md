# zk-anon-auth

Zero-knowledge anonymous authentication system using Semaphore and ZK-SNARKs. This project enables users to prove membership or authorization without revealing their identity on-chain.

## 🧱 Project Structure

```

zk-anon-auth/
├─ contracts/      # Solidity smart contracts (Semaphore & Verifier)
├─ circuits/       # ZK circuits (e.g. membership proof)
├─ frontend/       # Demo frontend (React, ethers.js, etc)
├─ scripts/        # Deploy & interaction scripts
├─ docs/           # Documentation & specs
└─ README.md       # This file

````

## 🚀 Deployment Guide (Testnet Sepolia)

### 1. Clone repo & install deps
```bash
git clone https://github.com/syvaira/zk-anon-auth.git
cd zk-anon-auth
````

Install tools (Hardhat, circomlib, snarkjs, etc):

```bash
npm install
```

### 2. Compile & Deploy Contracts

Edit config file, then run:

```bash
npx hardhat compile
npx hardhat run scripts/deploy.js --network sepolia
```

### 3. Generate ZK Proof & Test

Coming soon.

## 🔗 Resources & Links

* 🛠 Semaphore: [https://semaphore.pse.dev/](https://semaphore.pse.dev/)
* 🧪 Testnet Explorer (Sepolia): [https://sepolia.etherscan.io](https://sepolia.etherscan.io)
* 🧩 Verifier Contract: \[Coming Soon]
* ✅ Demo: \[Coming Soon]

---

> Made with 💻 by [@syvaira](https://github.com/syvaira)
