[![Latest Release](https://img.shields.io/github/v/release/iobeatss/treasury?display_name=tag&sort=semver)](https://github.com/iobeatss/treasury/releases)
[![Release workflow](https://img.shields.io/github/actions/workflow/status/iobeatss/treasury/release-treasury.yml?branch=main&label=Release%20workflow)](https://github.com/iobeatss/treasury/actions/workflows/release-treasury.yml)

# 💎 iO Beats — Treasury Transparency

[![Milestones](https://img.shields.io/badge/Milestones-Roadmap-blue)](#-roadmap--milestones)
[![Audit](https://img.shields.io/badge/Audit-Cyberscope-brightgreen.svg)](https://raw.githubusercontent.com/cyberscope-io/audits/main/iob/audit.pdf)
[![Solidity](https://img.shields.io/badge/Solidity-0.8.24-blue.svg?logo=solidity)](https://docs.soliditylang.org/en/v0.8.24/)
[![Deployment](https://img.shields.io/badge/Deployed-MultiChain-purple.svg)](https://github.com/iobeatss/IOB-Smart-contract#deployment)
[![Docs](https://img.shields.io/badge/Docs-Available-brightgreen.svg)](https://github.com/iobeatss/iobeats-docs)
[![Appendix B](https://img.shields.io/badge/Appendix%20B-v1.1%20Safe%20Multisig-orange.svg)](./docs/IOB_Treasury_AppendixB_v1.1.pdf)

This repository contains all official documents related to **iO Beats Treasury governance, safes, locks, and vesting schedules**.  
It is designed for **investors, exchanges (CEX), and the community** to ensure **maximum transparency**.

> **Update (v1.1):** Appendix B has been upgraded to the **Safe Multisig Treasury Strategy** (4/7 governance), with **on-chain proofs**, **deflationary presale** (unsold tokens burned), and a **Legal Disclaimer**.

---

## 📄 Treasury Documentation

- **Appendix B v1.1 — Safe Multisig Treasury** → [`PDF`](./docs/IOB_Treasury_AppendixB_v1.1.pdf)  
- **Vesting & Lock Strategy v1.1** → [`PDF`](./docs/IOB_Vesting_Lock_Strategy_v1.1.pdf)  
- **Lock Distribution v1.1 (Multi-chain Table)** → [`PDF`](./docs/IOB_Treasury_Lock_Distribution_v1.1.pdf)  
- **Changelog** → [`CHANGELOG.md`](./CHANGELOG.md)

**On-chain Proofs**
- **Ethereum (Mainnet) — Treasury Safe (4/7)**  
  - **Safe Address:** `0xA2952C5F625e59E21012FB92A8D8269Fdb324554`  
    ↳ [`Etherscan`](https://etherscan.io/address/0xA2952C5F625e59E21012FB92A8D8269Fdb324554)  
  - **First transaction (confirmation):**  
    `0x3dc91e19fc3489a26a35fd986754cdb651ffbbc42cdb2c9956eef6d0758e8f4`  
    ↳ [`Etherscan`](https://etherscan.io/tx/0x3dc91e19fc3489a26a35fd986754cdb651ffbbc42cdb2c9956eef6d0758e8f4)  
  - **Multisig Confirmation Report (PDF):**  
    [`docs/proofs/2025-10-01_Multisig_Transaction_Report.pdf`](./docs/proofs/2025-10-01_Multisig_Transaction_Report.pdf)

**Legacy (archived):**
- Appendix B v1.0 — Locks & Vesting → [`PDF`](./docs/IOB_Treasury_AppendixB_Locks_Vesting.pdf)

**Other references:**
- Audit Ready: Treasury Safe Multichain → [`PDF`](./docs/IOB_Treasury_Safe_Multichain_AuditReady.pdf)  
- Safe Structure → [`PDF`](./docs/IOB_Safe_Structure.pdf)  
- Multisig Architecture → [`PDF`](./docs/IOB_Safe_Multisig_Architecture.pdf)  
- Governance & Branding → [`PDF`](./docs/IOB_Treasury_Governance.pdf)  
- Treasury Multichain Report (EN) → [`PDF`](./docs/IOB_Treasury_Multichain_EN.pdf)  
- Executive Summary → [`PDF`](./docs/IOB_Treasury_Multichain_Executive_Summary.pdf)  
- Vault Addresses → [`addresses.md`](./docs/addresses.md)  
- Roadmap → [`ROADMAP.md`](./docs/ROADMAP.md)  
- Milestones → [`MILESTONES.md`](./docs/MILESTONES.md)  

---

## 🔐 Governance
- **Multisig Policy:** 4/7 required signatures  
- **Signers:** Founder, CoFounder, TechLead, CFO, Governance, Security, Backup  
- **Chains:** Ethereum · Base · Polygon · Arbitrum · BNB Chain  
- **Transparency:** On-chain proofs via official Safe addresses (see `addresses.md`)  
- **Presale:** Deflationary — all unsold tokens are burned

---

## 🏷 Labels
To organize issues and tasks, the following labels are used:  
- `transparency` → dashboards, reports, public data  
- `governance` → DAO, Snapshot votes  
- `automation` → GitHub Actions, scripts  
- `reporting` → reports, exports  
- `vesting` → on-chain locks, schedules  
- `frontend` → UI, dashboards  
- `docs` → documentation  

---

## 📌 Roadmap & Milestones

### 🚀 Milestone v1.0 — Release Treasury Transparency Pack  
**Due date:** 2025-10-04  
**Objective:** Establish the foundation of treasury transparency.  
- Lock vaults on all chains  
- Publish addresses & Appendix B  
- Initial transparency documentation  

---

### 🔎 Milestone v1.1 — Transparency & Governance Expansion  
**Due date:** 2025-12-31  
**Objective:** Extend transparency and activate DAO governance.  
- Dune Dashboard for real-time transparency  
- DAO Snapshot governance voting  

---

### ⚡ Milestone v2.0 — Full Treasury Automation  
**Due date:** 2026-06-30  
**Objective:** Automate treasury management and reporting.  
- Monthly reporting automation (GitHub Actions + PDF)  
- On-chain vesting → public reports  
- Public IO Beats treasury dashboard (UI)  

---

## 🌐 Related Links
- [Main Website](https://iobeats.com)  
- [Music Player](https://open.iobeats.com)  
- [Whitepaper](https://github.com/iobeatss/iobeats-docs/blob/main/iobeats-white-paper.pdf)  
- [Pitch Deck](https://github.com/iobeatss/iobeats-docs/blob/main/iobeats-pitch-deck.pdf)  

---

⚠️ **Note:** Vault addresses are placeholders until locks are executed on-chain.
