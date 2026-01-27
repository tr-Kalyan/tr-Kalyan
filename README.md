# Hi, I'm Kalyan TR 👋
**Smart Contract Developer | Security-Focused Engineer**

Former regulated-domain QA (Finance & Healthcare) → Web3 Security.

I build protocols with security-first thinking, then test them with fuzzing and static analysis to find what breaks.

![Focus](https://img.shields.io/badge/Focus-Smart%20Contract%20Security-blue?style=flat-square&logo=blockchain)
![Tools](https://img.shields.io/badge/Tools-Foundry%20%7C%20Slither%20%7C%20Fuzzing-00D1B2?style=flat-square)
![Active](https://img.shields.io/badge/Active-CodeHawks%20%7C%20Sherlock-FF2D20?style=flat-square)
![Status](https://img.shields.io/badge/Status-Open%20to%20audits%20&%20collabs-orange?style=flat-square)

---

### 🔍 Current Focus
- **Bug Hunting:** Participating in Fluid DEX V2 audit contest (Sherlock) — hunting for my first vulnerability in live production code
- **Competitive Audits:** Active on CodeHawks First Flights (5 validated findings in educational contests)
- **Building:** Completed trust-minimized payment infrastructure on Arc Network with Circle USDC integration

---

### 🚀 Featured Projects

#### Policy-Governed Agent Payments (PGAP)
*Trust-minimized payment infrastructure for autonomous AI agents.*
- **Architecture:** Three-layer trust model separating AI reasoning from on-chain enforcement
- **Integration:** Google Gemini AI + Arc Network + Circle USDC
- **Security:** Per-transaction limits, daily caps, cooldowns, allowlists, nonce-based replay protection
- **Testing:** Stateless fuzz testing of policy invariants (caps, cooldowns, replay safety)
- **Threat Model:** AI treated as an untrusted proposer; worst-case loss bounded by on-chain policy
- **Live:** [Treasury on Arc Sepolia](https://testnet.arcscan.app/address/0x9fB95CE21352d7FAB5A8A79aEB1E30B76F11B034)
- 🔗 **[View Repository](https://github.com/tr-Kalyan/policy-governed-agent-payments)**

#### Async Settlement RWA Vault
*ERC-4626 vault with T+1/T+2 settlement delays for real-world asset tokenization.*
- **Core Feature:** Async redemptions (request → delay → claim) aligned with traditional finance settlement
- **Security:** Stateless fuzz testing (1000+ runs), Slither static analysis, self-audit (5 issues found and fixed)
- **Testing:** Fork tests with real USDC on Sepolia
- **Live:** [Verified on Sepolia](https://sepolia.etherscan.io/address/0x9dC96F7D1161F2E40b1D855C57c5FD2a46cFf6b5)
- 🔗 **[View Repository](https://github.com/tr-Kalyan/async-rwa-vault)**

#### Verifiable RNG Distribution Protocol (Lottery V2)
*Gas-optimized lottery using Chainlink VRF v2.5 with binary search winner selection.*
- **Optimization:** O(log N) binary search replacing O(N) loops (~95% gas reduction)
- **Architecture:** Factory pattern for permissionless deployment
- **Security:** Checks-Effects-Interactions pattern, Slither clean, 100% test coverage
- **Live:** [Verified Factory on Sepolia](https://sepolia.etherscan.io/address/0xEaF7a29423A1C011643cE37091F2801b78cF573f)
- 🔗 **[View Repository](https://github.com/tr-Kalyan/VRF-Lotto)**

#### Collateralized Debt Solvency Engine (DSCEngine)
*Over-collateralized stablecoin system with liquidation mechanism.*
- **Core Logic:** 200% collateralization threshold, 10% liquidation incentive
- **Security:** Oracle circuit breaker for stale price protection
- **Testing:** Stateless fuzz testing to verify solvency invariants
- **Live:** [Verified on Sepolia](https://sepolia.etherscan.io/address/0x5A5471756a1C796d6a29d148EA88127E08922Ce6)
- 🔗 **[View Repository](https://github.com/tr-Kalyan/collateralized_debt_solvency_engine)**

---

### 🛡️ Security Research

**Current Status**
- Participating in Fluid DEX V2 audit contest (Sherlock) — first live protocol audit
- 5 validated findings in CodeHawks First Flights (educational contests)
- Learning production audit methodology through competitive platforms

**Testing Approach**
- Slither static analysis for common vulnerability classes
- Foundry stateless fuzz testing for edge cases and invariant violations
- Manual code review for logic errors and economic exploits
- Fork testing against mainnet state when applicable

> **Note:** I’m early in my security research journey. The above reflects my actual experience level — educational contest findings, not production discoveries yet. Actively leveling up through real audit contests like Fluid DEX V2.

---

### 🎓 Background & Education
- **Master of Science in Computer Science** (in progress)
- Former QA Engineer in regulated industries (Finance & Healthcare)
- Transitioned from traditional software testing to smart contract security

---

### 🧰 Tech Stack

**Languages:**  
Solidity, TypeScript, JavaScript, HTML/CSS

**Frameworks:**  
Foundry, Hardhat, ethers.js

**Testing & Security:**  
Foundry Fuzz Testing (stateless), Slither Static Analysis, Fork Testing

**Tools:**  
Git, GitHub, VSCode, Remix

**Integrations:**  
Chainlink (VRF, Price Feeds), Circle USDC, Arc Network, OpenZeppelin

---

### 💼 Open to Collaboration

**Interested in**
- Smart contract security research and auditing (learning phase)
- DeFi protocol development (especially RWA and agent-based systems)
- Building security testing frameworks

**Best Fit**
- Teams needing systematic testing and security-conscious development
- Projects integrating Circle, Arc, or Chainlink
- Early-stage protocols where I can contribute to architecture and testing

---

### 📫 Connect

📧 Email: [kalyansde1@gmail.com](mailto:kalyansde1@gmail.com)  
🐦 X (Twitter): [@kalyan__tr](https://x.com/kalyan__tr)  
💼 GitHub: [@tr-Kalyan](https://github.com/tr-Kalyan)

---

### 📊 GitHub Stats

![Kalyan's GitHub stats](https://github-readme-stats.vercel.app/api?username=tr-Kalyan&show_icons=true&theme=radical)

---

### 🎯 2026 Goals
- [ ] Find first valid bug in a production protocol audit
- [ ] Complete 10+ audit contests on Sherlock / CodeHawks
- [ ] Build an automated testing tool for common DeFi vulnerabilities
- [ ] Contribute to at least 3 protocol security improvements
- [ ] Transition into a junior smart contract auditor role

---

**Last Updated:** January 2026
