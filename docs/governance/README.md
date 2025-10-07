# 🗳️ IO Beats DAO — Governance & Proposals  

[![Vote Now on Snapshot](https://img.shields.io/badge/Vote%20Now-Snapshot-blueviolet?logo=snapshot&logoColor=white)](https://snapshot.box/#/s:iobdao.eth)
[![DAO Transparency](https://img.shields.io/badge/Transparency-Reports-orange?logo=dune&logoColor=white)](https://dune.com/iobeats_dao)
[![Docs](https://img.shields.io/badge/Documentation-GitHub-green?logo=github)](https://github.com/iobeatss/treasury/tree/main/docs/governance)

---

## 🌍 Overview

The **IO Beats DAO Governance System** defines how $IOB holders participate in decentralized decision-making  
on topics such as **treasury management, partnerships, DeFi integrations, and community development**.  

Every proposal is published through **Snapshot** and executed via **Safe multisig**, ensuring full transparency.

> 📘 Full framework, constitution, and legal disclosure are available below as official DAO documents.

---

## 📘 Official Governance Documents

| Document | Version | Date | Link |
|-----------|----------|------|------|
| **IOB DAO Constitution** | v1.0 | Oct 2025 | [📄 PDF](./IOB_DAO_Constitution_v1.0_Premium.pdf) |
| **DAO Legal Disclosure & Risk Statement** | v1.0 | Oct 2025 | [📄 PDF](./IOB_DAO_LegalDisclosure_v1.0_Premium.pdf) |
| **DAO Governance Framework (Premium Edition)** | v1.0 | Oct 2025 | [📄 PDF](./IOB_DAO_Governance_Framework_v1.0_PremiumEdition.pdf) |
| **Snapshot Governance Activation Report** | v1.0 | Oct 2025 | [📄 PDF](./DAO_Snapshot_Governance_Activation_IOB_Vote.pdf) |

> 🧠 These documents define the DAO’s structure, membership, quorum rules, proposal cycles, security clauses, and legal posture.

---

## 🧾 Latest Proposals

📁 Data Source → [`data/snapshot/latest.json`](../../data/snapshot/latest.json)

| Proposal | Status | Author | Link |
|-----------|---------|---------|------|
| 🧩 **Genesis Proposal #001 — The Birth of IO Beats DAO** | ✅ Active | `0x04a7b3e5a6c4c6...` | [View on Snapshot](https://snapshot.box/#/s:iobdao.eth/proposal/0x4e0ec421ed5cf0d6b6d07ef97727f15f61b0881bf20df0fdeab14caa868a663c) |
| 💎 **Treasury Transparency v1.0** | 🟡 Ongoing | DAO Treasury | [View on Snapshot](https://snapshot.box/#/s:iobdao.eth/proposal/0x...example...) |
| 🧠 **Governance Expansion v1.1** | ⏳ Planned | DAO Governance | [View on Snapshot](https://snapshot.box/#/s:iobdao.eth/proposal/0x...example...) |

> ✅ *Automatically refreshed by GitHub Actions (every 6 hours via `snapshot-sync.yml`).*  

---

## 🧩 Governance Structure

| DAO Branch | Network | Function |
|-------------|----------|----------|
| **Main DAO** | Ethereum | Core Governance |
| **Treasury DAO** | Base | Fund Management |
| **Creator DAO** | Polygon | Artist & Community Proposals |
| **Expansion DAOs** | BNB / Arbitrum | DeFi and Ecosystem Growth |

> All branches follow the **4-of-7 multisig model** with transparent Dune dashboards and Cyberscope audits.

---

## ⚙️ Governance Parameters

- Quorum: **25M IOB**  
- Proposal Threshold: **2.5M IOB**  
- Voting Delay: **1 hour**  
- Voting Period: **48 hours**  
- Approval Ratio: **51% FOR**  
- Vote Cap: **3M IOB per wallet**  
- Voter Incentive: **0.5% DAO Rewards**

---

## ⚙️ Automation Flow

```mermaid
flowchart LR
  A[Snapshot API] --> B[GitHub Actions Workflow]
  B --> C[data/snapshot/latest.json]
  C --> D[docs/governance/README.md]
  D --> E[GitHub Pages / Treasury Portal]
