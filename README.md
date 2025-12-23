# Hi, I'm Kalyan TR 👋
**Web3 Security Researcher & QA Specialist**  
Former regulated-domain QA (Finance & Healthcare) → pivoting hard into blockchain security.  
I build DeFi protocols, then **assault them** with invariants, fuzzing, and self-audits to prove they hold under real-world pressure.

![Focus](https://img.shields.io/badge/Focus-Smart%20Contract%20Security-blue?style=flat-square&logo=blockchain)
![Tools](https://img.shields.io/badge/Tools-Foundry%20%7C%20Slither%20%7C%20Invariants%20%7C%20Fuzzing-00D1B2?style=flat-square)
![Active](https://img.shields.io/badge/Active-CodeHawks%20%7C%20Code4rena%20%7C%20Sherlock-FF2D20?style=flat-square)
![Status](https://img.shields.io/badge/Status-Open%20to%20audits%20&%20collabs-orange?style=flat-square)

### 🔍 Current Focus
- Competitive audits (CodeHawks First Flights: 5 validated findings, ongoing in Sherlock Aave V4 & Code4rena Panoptic)
- Building institutional-grade DeFi models (async RWAs, Chainlink-integrated protocols)
- Self-auditing everything — invariants, fuzz campaigns, severity-ranked reports

### 🚀 Featured Projects (Security-First)

**Async Settlement RWA Vault** — ERC-4626 with real T+1/T+2 settlement delays for tokenized Treasuries/private credit  
• Instant deposits, **async redemptions** (request → delay → claim) to mirror TradFi reality  
• Stable NAV accounting (virtual liabilities prevent price spikes on queued redemptions)  
• Built-in protections: slippage guard, cancel/rescind (compliance/sanctions), dry-vault errors  
• Full assault: 1000+ invariant fuzz runs, self-audit report (5 findings fixed), fork tests with real USDC  
• Live & verified on Sepolia: [0x9dC96F7D...](https://sepolia.etherscan.io/address/0x9dC96F7D1161F2E40b1D855C57c5FD2a46cFf6b5)  
🔗 [Repo](https://github.com/tr-Kalyan/async-rwa-vault) | [X Thread](https://x.com/kalyan__tr/status/...)  

**Autonomous Weighted Lottery** — Factory-owned Chainlink VRF v2.5 subscription, O(1) weighted randomness, full automation  
• Cumulative sum pattern + timeout recovery  
• Self-audited with Slither (false positives documented)  
• 21+ unit tests + CI/CD pipeline  
🔗 [Repo](https://github.com/tr-Kalyan/VRF-Lotto) | Live Factory on Sepolia

**Overcollateralized Stablecoin (DSC)** — Exogenous collateral (WETH/WBTC), 200% ratio, 10% liquidation bonus  
• Handler-based fuzzing + core solvency invariant  
• Learning vehicle for DeFi mechanics  
🔗 [Repo](https://github.com/tr-Kalyan/defi_stablecoin)

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
