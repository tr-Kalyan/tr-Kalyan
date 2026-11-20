<div align="center">

# Kalyan TR
### Smart Contract Security Researcher

**Follow the money. Find the break.**

Tracing how value moves through a protocol, challenging its assumptions,  
and turning the bugs that survive into reproducible proof.

Paid Triager @ Pashov Audit Group · Ex-QA & Financial Systems (5+ yrs @ JP Morgan & Franklin Templeton)

[kalyantr.dev](https://kalyantr.dev) · [@kalyan__tr](https://x.com/kalyan__tr) · [kalyansde1@gmail.com](mailto:kalyansde1@gmail.com) · [Findings](https://github.com/tr-Kalyan/web3-security-findings)

<br>

![Available](https://img.shields.io/badge/AVAILABLE-065F46?style=flat-square&labelColor=111827)
![Critical](https://img.shields.io/badge/1_CRITICAL-991B1B?style=flat-square&labelColor=111827)
![High](https://img.shields.io/badge/7_HIGH-DC2626?style=flat-square&labelColor=111827)
![Medium](https://img.shields.io/badge/11_MEDIUM-D97706?style=flat-square&labelColor=111827)
![Low](https://img.shields.io/badge/10_LOW-2563EB?style=flat-square&labelColor=111827)
![Protocols](https://img.shields.io/badge/13+_PROTOCOLS-374151?style=flat-square&labelColor=111827)

</div>

---

### Methodology

The code is the source of truth.

- **Falsification-first** — kill weak hypotheses early
- **Test-before-submit** — reproduce on Foundry / Anchor / Rust
- **Devil’s filter** — who benefits, what triggers, what harms the honest user
- **Cross-check** — AI suggests, spec + code decide
- **Fuzz & invariants** — cover what unit tests miss

---

### Validated Findings

29 findings across contests, private reviews, and bounties.  
*Duplicate = independently found the same bug as the lead reporter.*

| Protocol | Focus | Platform | Findings | Report |
|----------|-------|----------|----------|--------|
| Rain USDR | Multi-collateral synthetic | HackenProof | 3H · 5M | [Profile](https://hackenproof.com/hackers/Kalyan-tr) |
| 0xMarkets | On-chain markets | HackenProof | 1H · 4M | NDA |
| Solv BTC+ | BTC yield / restaking | HackenProof | 1C (Dup) | [View](https://github.com/tr-Kalyan/web3-security-findings) |
| Hyperbridge | ISMP / cross-chain | HackenProof | 1H (Dup) | [View](https://github.com/tr-Kalyan/web3-security-findings) |
| Quantus | Post-quantum L1 · ZK · Substrate | Immunefi | 1H | [View](https://github.com/tr-Kalyan/web3-security-findings) |
| Firelight | On-chain cover · ERC-4626 | Immunefi | 1H | [View](https://github.com/tr-Kalyan/web3-security-findings) |
| Fluid DEX V2 | DEX · first paid contest | Sherlock | 1M | [View](https://github.com/tr-Kalyan/web3-security-findings) |
| Limit Break AMM | AMM · collaborative | Guardian Audits | 1M | [View](https://github.com/tr-Kalyan/web3-security-findings) |
| + more | Jupiter Lend, Monetrix, K2, XRP Ledger… | Various | L/M | [Full list](https://github.com/tr-Kalyan/web3-security-findings) |

---

### Stack

**Languages** Solidity · Rust (Anchor / Substrate / Soroban) · TypeScript  
**Tooling** Foundry (unit · fuzz · invariant) · Slither · Anchor · Mainnet forks  
**Ecosystems** EVM · Solana · Cross-chain (LayerZero · ISMP) · Post-quantum / ZK

---

### Selected Work

| Project | What it is | Tech |
|---------|------------|------|
| Async Settlement RWA Vault | ERC-4626 with real T+1/T+2 settlement | Solidity · Foundry · 1000×128 invariant fuzz · USDC forks |
| Collateralized Debt Solvency Engine | Over-collateralized stablecoin with health-factor liquidation | Solidity · Foundry · pull-over-push · solvency invariants |
| Verifiable RNG Distribution | Gas-optimized lottery (Chainlink VRF v2.5 + binary search) | Solidity · Foundry · O(log N) winner selection |
| ModularGarden | ERC-2535 Diamond + ERC-4337 wallet framework | Solidity · Mentored by Nick Mudge |

---

### Education & Programs

- **Rektoff Launchpad × Solana Foundation** — Rust Security Bootcamp · Grade A (216 pts)  
  Capstone: MetaLend audit (15 findings — admin auth, oracle validation, liquidation math, flash-loan vectors)

- **Blok Capital Builder Cohort #1** — Mentored by Nick Mudge  
  Built ModularGarden (ERC-2535 + ERC-4337)

- **Scaler Master’s Program in Computer Science**

- **5+ years** Software QA & Financial Systems — JP Morgan & Franklin Templeton

---

### Services

Smart contract review · Invariant & fuzz testing · Finding validation & PoC

Available for security reviews, audit collaborations, and associate researcher roles.

---

<div align="center">

**The code is the source of truth.**

[kalyantr.dev](https://kalyantr.dev) · [Findings](https://github.com/tr-Kalyan/web3-security-findings) · [X](https://x.com/kalyan__tr)

</div>
