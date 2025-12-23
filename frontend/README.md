

# DataCrypt: Turning Failure into IP<div align="center">

  <img src="public/logo.png" alt="FailVault Logo" width="120" />

  <br />

  <h3>The Decentralized Archive for Negative Scientific Results</h3>

  

  <p>    <a href="https://failvault-demo.vercel.app">View Demo</a> •

    <a href="https://youtu.be/demo-video-link">Watch Video</a> •

    <a href="#-getting-started">Documentation</a>

  </p>

</div>

---## The Problem**Science has a "Positive Publication Bias."**

Researchers spend months conducting experiments that fail or yield negative results. Because journals rarely publish these findings, this data rots in drawers.* **Wasted Time:** Other scientists unknowingly repeat the same failed experiments.* **Wasted Resources:** Billions of dollars in grant money are burned on redundant research.* **Zero ROI:** Researchers get no credit or compensation for negative results.## 💡 The Solution: FailVault

FailVault is a **Decentralized Science (DeSci)** marketplace that allows researchers to mint their failed experiments as **IP-NFTs**.* **🛡️ Encrypted IP:** Sensitive data (raw datasets, logs) is encrypted and stored on IPFS/Arweave, accessible only to those who purchase an unlock.* **⛓️ Immutable Proof:** We mint a proof-of-existence NFT on the **Polygon Amoy Network**, timestamping the discovery.* **💰 Monetization:** Researchers earn ETH/POL whenever another scientist unlocks their data to save time.## ⚡ Tech Stack



| Component | Technology | Description |

| :--- | :--- | :--- |

| **Frontend** | Next.js 14, Tailwind CSS | Responsive, glassmorphism UI with Lucide React icons. |

| **Blockchain** | Polygon Amoy Testnet | Low-cost, fast transactions for minting IP-NFTs. |

| **Smart Contracts** | Solidity, Hardhat | Handles minting, ownership, and unlock logic. |

| **Storage** | IPFS / Supabase | Hybrid storage for public metadata and encrypted private data. |

| **Auth** | Ethers.js / MetaMask | Web3 wallet connection and transaction signing. |## 📸 Screenshots



| Landing Page | Publishing Portal |

|:---:|:---:|

| ![Landing](public/screenshots/landing.png) | ![Publish](public/screenshots/publish.png) | ![Admin](public/screenshots/) | ## 🛠️ Getting Started### Prerequisites* Node.js (v18+)* MetaMask Wallet (connected to Polygon Amoy)### Installation1. **Clone the repo**

   ```bash

   git clone [https://github.com/cxgx4/DataCryptic.git](https://github.com/cxgx4/DataCryptic.git)

   cd failvault

Install dependencies

Bash



npm install# or

yarn install

Set up Environment Variables

Create a .env.local file in the root directory:

Bash



NEXT_PUBLIC_SUPABASE_URL=your_supabase_url

NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_key

Run the Development Server

Bash



npm run dev

Open the App

Visit http://localhost:3000 in your browser.

⛓️ Smart Contract Info

Network: Polygon Amoy Testnet

Contract Address: 0x2A5799Cc7E9708b39D14014C143451ABf4938fBd

Explorer: View on Amoy PolygonScan

🤝 Contributing

Built for the [CodeQuest] 2025.

Team: [Cherry Ghosh] & [Debdutta Ghosh] & [Debasmita Chatterjee]

📄 License

Distributed under the MIT License. See LICENSE for more information.
