# Hi, I'm Kalyan TR 👋
**Smart Contract Security Engineer & Protocol Architect** Former regulated-domain QA (Finance & Healthcare) → Web3 Security Researcher.  

I build gas-optimized protocols, then **assault them** with invariants, fuzzing, and self-audits to prove they hold under real-world pressure.

![Focus](https://img.shields.io/badge/Focus-Smart%20Contract%20Security-blue?style=flat-square&logo=blockchain)
![Tools](https://img.shields.io/badge/Tools-Foundry%20%7C%20Slither%20%7C%20Invariants%20%7C%20Fuzzing-00D1B2?style=flat-square)
![Active](https://img.shields.io/badge/Active-CodeHawks%20%7C%20Code4rena%20%7C%20Sherlock-FF2D20?style=flat-square)
![Status](https://img.shields.io/badge/Status-Open%20to%20audits%20&%20collabs-orange?style=flat-square)

### 🔍 Current Focus
- **Agentic Commerce:** Building autonomous AI-driven DeFi infrastructure on **Arc (Circle)** for the *Agentic Commerce Hackathon* (Jan 2026).
- **Competitive Audits:** Active on Sherlock (Aave V4) & CodeHawks. 5 validated findings in First Flights.
- **Advanced Architecture:** Implementing O(log N) algorithms and Factory patterns in Solidity.
- **Projects:** Building institutional-grade DeFi models (async RWAs, Chainlink-integrated protocols)


### 🚀 Featured Projects (Security-First)

**Async Settlement RWA Vault** — ERC-4626 with real T+1/T+2 settlement delays for tokenized Treasuries/private credit  
• Instant deposits, **async redemptions** (request → delay → claim) to mirror TradFi reality  
• Stable NAV accounting (virtual liabilities prevent price spikes on queued redemptions)  
• Built-in protections: slippage guard, cancel/rescind (compliance/sanctions), dry-vault errors  
• Full assault: 1000+ invariant fuzz runs, self-audit report (5 findings fixed), fork tests with real USDC  
• Live & verified on Sepolia: [0x9dC96F7D...](https://sepolia.etherscan.io/address/0x9dC96F7D1161F2E40b1D855C57c5FD2a46cFf6b5)  
🔗 [Repo](https://github.com/tr-Kalyan/async-rwa-vault) | [X Thread](https://x.com/kalyan__tr/status/...)  

####  Verifiable RNG Distribution Protocol (Lottery V2)
*A gas-optimized, autonomous distribution engine powered by Chainlink VRF v2.5.*
* **Engineering:** Replaced naive linear loops with **Binary Search (O(log N))** over cumulative sum arrays.
* **Performance:** Reduced winner selection gas cost by **~95%** (Flat cost regardless of player count).
* **Architecture:** Factory Pattern for permissionless deployment + Auto-configured VRF Subscriptions.
* **Security:** Checks-Effects-Interactions, 100% test coverage, and Slither static analysis (Clean).
* **Live:** [Verified Factory on Sepolia](https://sepolia.etherscan.io/address/0xEaF7a29423A1C011643cE37091F2801b78cF573f)
* 🔗 **[View Repository](https://github.com/tr-Kalyan/VRF-Lotto)**

#### Collateralized Debt Solvency Engine (DSCEngine)
*Algorithmic, over-collateralized stablecoin system inspired by MakerDAO DSS.*
* **Core Logic:** Maintains 1:1 USD peg via 200% collateralization thresholds and 10% liquidation incentives.
* **Security:** Implements **OracleLib** with circuit breakers to prevent stale-data insolvency.
* **Fuzzing:** Verified via **Stateful Handler-based Fuzzing** to ensure the "Solvency Invariant" holds under randomized price volatility.
* **Live:** [Verified Factory on Sepolia](https://sepolia.etherscan.io/address/0x5A5471756a1C796d6a29d148EA88127E08922Ce6)
* 🔗 **[View Repository](https://github.com/tr-Kalyan/collateralized_debt_solvency_engine)**

### 🎓 Background & Education
- **Master of Science in Computer Science** (in progress)  
- Former regulated QA (Finance + Healthcare) — deep experience in compliance, risk, and rigorous testing

### 💼 Open to Collaboration
- Smart contract audits & protocol reviews  
- Chainlink-integrated DeFi/RWA projects  
- Security tool development & fuzzing campaigns  

### 📫 Connect
- Email: [kalyansde1@gmail.com](mailto:kalyansde1@gmail.com)  
- X: [@kalyan__tr](https://x.com/kalyan__tr)  
- GitHub: [@tr-Kalyan](https://github.com/tr-Kalyan)

> *"Security isn't a feature — it's the foundation. I build, break, prove, and repeat."*
