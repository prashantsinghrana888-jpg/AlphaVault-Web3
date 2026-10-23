# 🚀 AlphaVault Web3 - Pro Autonomous Trading Terminal

AlphaVault Web3 is a high-performance, autonomous decentralized trading terminal featuring a multi-chain zero-loss circuit breaker, simulated and real-time arbitrage execution, live profit analytics ($/USDT), and an automated profit-splitting architecture routing directly to an admin vault.

---

## 🛠️ Tech Stack & Infrastructure
* **Frontend:** HTML5, CSS3, JavaScript (ES6+ Module)
* **Web3 Integration:** Ethers.js (v5.7.2) for Trust Wallet & MetaMask connectivity
* **Backend Database:** Google Firebase Firestore (Real-time synchronization and log storage)
* **Hosting:** GitHub Pages (`https://prashantsinghrana888-jpg.github.io/AlphaVault-Web3/`)

---

## ✨ Key Features
1. **Multi-Chain Network Support:** Seamless switching between Ethereum Mainnet, BNB Smart Chain (BSC), and Polygon Mainnet.
2. **Zero-Loss Circuit Breaker:** Protects user sessions and validates wallet connection states prior to trade dispatch.
3. **Autonomous Bot Loop:** Automated interval-based arbitrage execution engine generating live transaction logs and live profit counters.
4. **Real-Time Vault Routing:** Automatically calculates and routes the 25% profit share directly to the admin vault (`0x635beb7df4bE1000c4E4d886CEe45336a71810a5`).
5. **Cloud Firestore Sync:** Real-time logging of user session metadata, transaction hashes, and trade statuses into a secure cloud backend.

---

## ⚙️ Setup & Deployment
1. Clone the repository or open it directly in a mobile/desktop code editor (like Acode or VS Code).
2. Configure your Firebase project keys in the `firebaseConfig` object within `index.html`.
3. Host/Deploy the project via GitHub Pages.
4. Open the DApp link inside the Trust Wallet browser to initialize Web3 sessions and test autonomous execution loops.

---
*Developed for production-level Web3 automated asset management and trading terminal systems.*
