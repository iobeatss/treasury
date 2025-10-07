<p align="center">
  <img src="https://raw.githubusercontent.com/iobeatss/iobeats-logo-assets/main/hero1.gif"
       alt="IO Beats DAO Banner" width="100%" />
</p>

# 🗳️ IO Beats DAO — Governance & Proposals  

[![Vote Now on Snapshot](https://img.shields.io/badge/Vote%20Now-Snapshot-blueviolet?logo=snapshot&logoColor=white)](https://snapshot.box/#/s:iobdao.eth)
[![DAO Transparency](https://img.shields.io/badge/Transparency-Reports-orange?logo=dune&logoColor=white)](https://dune.com/iobeats_dao)
[![Docs](https://img.shields.io/badge/Documentation-GitHub-green?logo=github)](https://github.com/iobeatss/treasury/tree/main/docs/governance)

---

## 🌍 Overview

The **IO Beats DAO Governance System** allows $IOB holders to propose, discuss, and vote on key topics  
including **treasury management, partnerships, DeFi integrations, and ecosystem development**.  

Every proposal is verified on-chain and published through **Snapshot** for maximum transparency.

> 📘 Full framework (Premium Edition):  
> [`IOB_DAO_Governance_Framework_v1.0_PremiumEdition.pdf`](./IOB_DAO_Governance_Framework_v1.0_PremiumEdition.pdf)

---

## 📡 Live Snapshot Space

> **DAO Space:** <https://snapshot.box/#/s:iobdao.eth>  
> **Network:** Ethereum  
> **Voting System:** Weighted by $IOB holdings  
> **Governance Model:** 1 token = 1 vote

---

## 🧾 Latest Proposals (Auto-Updated)

📁 Data Source → [`data/snapshot/latest.json`](../../data/snapshot/latest.json)

| Proposal | Status | Author | Link |
|-----------|---------|---------|------|
| 🧩 **Genesis Proposal #001 — The Birth of IO Beats DAO** | ✅ Active | `0x04a7b3e5a6c4c6...` | [View on Snapshot](https://snapshot.box/#/s:iobdao.eth/proposal/0x4e0ec421ed5cf0d6b6d07ef97727f15f61b0881bf20df0fdeab14caa868a663c) |
| 💎 **Treasury Transparency v1.0** | 🟡 Ongoing | DAO Treasury | [View on Snapshot](https://snapshot.box/#/s:iobdao.eth/proposal/0x...example...) |
| 🧠 **Governance Expansion v1.1** | ⏳ Planned | DAO Governance | [View on Snapshot](https://snapshot.box/#/s:iobdao.eth/proposal/0x...example...) |

> ✅ *Automatically refreshed by GitHub Actions (every 6 hours via `snapshot-sync.yml`).*

---

## 🧭 How to Propose

1. **Draft** your idea (title, rationale, scope, budget if any).  
2. **Discuss** in the DAO forum/Discord for feedback.  
3. **Submit** on Snapshot under **iobdao.eth** with clear options and timelines.  
4. **Vote** — proposals remain open per the configured voting window.  
5. **Execute** — post-vote actions are executed via the DAO multisig and then verified publicly.

---

## 📘 DAO Snapshot Governance Activation

The **DAO Snapshot Governance Activation Report** outlines how IO Beats DAO initiated its  
governance infrastructure across **Ethereum, Base, Polygon, BNB Chain, and Arbitrum**.  

It includes:
- Governance parameters (quorum, proposal threshold, voting delay)  
- DAO structure and ENS portfolio  
- Multi-chain Snapshot setup  
- Official links (GitHub, Dune, Snapshot)  
- Legal disclaimer

📄 **Read the full report:**  
[`DAO_Snapshot_Governance_Activation_IOB_Vote.pdf`](./DAO_Snapshot_Governance_Activation_IOB_Vote.pdf)

---

## ⚙️ Automation Details

This governance tracker is powered by:
- **GitHub Actions** → Fetches proposals every 6h from Snapshot GraphQL API  
- **Dune Dashboards** → Monitors treasury inflows/outflows  
- **Docs Auto-Updates** → JSON reports are stored in `/data/snapshot/`

🧩 **Workflow:**  
```mermaid
flowchart LR
  A[Snapshot Proposals API] -->|GraphQL Query| B[GitHub Actions Workflow]
  B -->|Store JSON| C[data/snapshot/latest.json]
  C -->|Feeds| D[docs/governance/README.md]
  D -->|Displayed| E[GitHub Pages / Treasury Portal]
