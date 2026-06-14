# Kalyan TR

Smart contract security researcher. Background in regulated-domain QA (5+ years, JP Morgan & Franklin Templeton) before transitioning to Web3 security full-time. Competing on Code4rena, Sherlock, HackenProof, and Cantina. 

---

## Validated Findings

| Protocol | Platform | Findings | Reports |
|---|---|---|---|
| Fluid DEX V2 | Sherlock | 1M | [View →](https://github.com/tr-Kalyan/web3-security-findings/tree/main/sherlock/Fluid-dex%20V2) |
| Hyperbridge | HackenProof | 1H | [View →](https://github.com/tr-Kalyan/web3-security-findings/tree/main/HackenProof/HyperBridge%20Protocol) |
| Solv BTC+ | HackenProof | 1C | [View →](https://github.com/tr-Kalyan/web3-security-findings/tree/main/HackenProof/Solv%20Protocol) |
| Limit Break AMM | GuardianAudits | 1M | [View →](https://github.com/tr-Kalyan/web3-security-findings/tree/main/GuardianAudits/LimitBreak) |
| Jupiter Lend | Code4rena | 2L | [View →](https://github.com/tr-Kalyan/web3-security-findings/tree/main/code4rena/Jupiter%20Lend) |
| Monetrix | Code4rena | 2L | [View →](https://github.com/tr-Kalyan/web3-security-findings/tree/main/code4rena/Monterix) |

> Duplicate (Valid) — independently identified the same vulnerability as the lead reporter. The bug is confirmed; credit is shared.

---

## Open to Audits and Jobs

Available for audit collaborations, solo engagements, and junior/associate security researcher roles. If you are running a contest, building a protocol, or hiring — reach out.

📧 [kalyansde1@gmail.com](mailto:kalyansde1@gmail.com) · 🐦 [@kalyan__tr](https://x.com/kalyan__tr)

---

## Methodology

- **Falsification-first** — kill weak hypotheses before investing in a PoC
- **Test-before-submit** — validate findings with Foundry or Anchor PoCs
- **Devil's filter** — who benefits, what is the concrete trigger, what is the honest user harm
- **Cross-check** — AI tools as a suggestion layer, verify against spec and code
- **Fuzz and invariant testing** — use Foundry fuzz and invariant suites to find edge cases the unit tests miss and confirm protocol invariants hold under arbitrary inputs

---

## Stack

**Languages:** Solidity · Rust (Anchor/Solana) · Soroban/Stellar

**Tooling:** Foundry (unit, fuzz, invariant) · Slither

**Ecosystems:** EVM · Solana · Stellar

**Cross-chain:** LayerZero · ISMP/Hyperbridge

---

## Education & Programs

- **Rektoff Launchpad × Solana Foundation** — Rust Security Bootcamp, graduated with Grade A (216pts). Capstone: MetaLend audit, 15 findings across admin auth, oracle validation, liquidation math, and flash loan vectors.

![Rektoff Graduation Certificate](./RektOff%20-%20Kalyan%20Tunga%20Ramesh.png)

- **Blok Capital Builder Cohort #1** — ERC-2535 Diamond, ERC-4337 (mentored by Nick Mudge)
- Master of Science in Computer Science (in progress)


---

## Projects

- **ModularGarden** — ERC-2535 Diamond + ERC-4337 Account Abstraction wallet framework (mentored by Nick Mudge, Blok Capital Cohort #1)
- **Verifiable RNG Distribution Protocol** — Gas-optimized lottery system using Chainlink VRF v2.5 and binary search cumulative sum for O(log N) winner selection. Factory pattern with auto-subscription management.
- **Async Settlement RWA Vault** — ERC-4626 vault enforcing real T+1/T+2 settlement delays for tokenized real-world assets (Treasuries, private credit). Stable NAV accounting, slippage protection, compliance rescind, and admin yield injection. Validated with unit tests, invariant fuzzing (1000 runs × 128 depth), and fork tests against mainnet Circle USDC.
