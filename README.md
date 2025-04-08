# 🔍 TruthBounty Backend  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
[![CI/CD](https://github.com/DigiNodes/TruthBounty_Backend/actions/workflows/main.yml/badge.svg)](https://github.com/DigiNodes/TruthBounty_Backend/actions)  
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTORS_GUIDE.md)  

> **Decentralized news verification engine** with tokenized rewards powered by Optimism blockchain.

---

## 🚀 Features  
- **🛡️ Reputation-weighted verification** using staked tokens  
- **💰 Optimism blockchain** integration for ERC-20 rewards  
- **🔗 IPFS evidence storage** with cryptographic proofs  
- **🌐 Worldcoin ID** for Sybil-resistant authentication  
- **📊 Real-time reputation scoring**  
- **🤖 AI-assisted fake news detection** (optional integration)  

---

## ⚙️ Tech Stack  

### Backend Core  
| Technology | Purpose |  
|------------|---------|  
| ![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white) | API framework |  
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) | Primary database |  
| ![TypeORM](https://img.shields.io/badge/TypeORM-FE0902?logo=typeorm&logoColor=white) | ORM |
| ![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white) | Caching/Sessions |  

### Web3 Integration  
| Technology | Purpose |  
|------------|---------|  
| ![Optimism](https://img.shields.io/badge/Optimism-FF0420?logo=optimism&logoColor=white) | Reward distribution |  
| ![Ethers.js](https://img.shields.io/badge/Ethers.js-3C3C3D?logo=ethereum&logoColor=white) | Blockchain interaction |  
| ![IPFS](https://img.shields.io/badge/IPFS-65C2CB?logo=ipfs&logoColor=white) | Evidence storage |  

### DevOps  
| Technology | Purpose |  
|------------|---------|  
| ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) | Containerization |  
| ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=github-actions&logoColor=white) | CI/CD |  

---

## 🛠️ Setup Guide  

### Prerequisites  
- Node.js v18+  
- PostgreSQL 14+  
- Redis 6+  
- Git  

### Installation  
```bash
# Clone repository
- git clone https://github.com/DigiNodes/TruthBounty_Backend.git
- cd TruthBounty_Backend

# Install dependencies
- npm install

# Configure environment
- cp .env.example .env
# Edit .env with your credentials

# Start in development mode
- npm run start:dev

# Or with Docker
docker-compose up -d
```

## 👥 Contributing
### Requirements
1. Read our [Contributor's Guide](https://github.com/DigiNodes/TruthBounty_Backend/blob/main/CONTRIBUTING.md)
2. Follow [Conventional Commits](https://github.com/DigiNodes/TruthBounty_Backend/blob/main/CONTRIBUTING.md)

## 📜 License
MIT © [DigiNodes](https://github.com/DigiNodes)