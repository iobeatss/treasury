# 🗳️ IO Beats DAO — Governance & Proposals  

[![Vote Now on Snapshot](https://img.shields.io/badge/Vote%20Now-Snapshot-blueviolet?logo=snapshot&logoColor=white)](https://snapshot.box/#/s:iobdao.eth)
[![DAO Transparency](https://img.shields.io/badge/Transparency-Reports-orange?logo=dune&logoColor=white)](https://dune.com/iobeats_dao)
[![Docs](https://img.shields.io/badge/Documentation-GitHub-green?logo=github)](https://github.com/iobeatss/treasury/tree/main/docs/governance)

---

## 🌍 Overview

The **IO Beats DAO Governance System** allows $IOB holders to propose, discuss, and vote on key topics  
including **treasury management, partnerships, DeFi integrations, and ecosystem development**.  

Every proposal is verified on-chain and published through **Snapshot** for maximum transparency.  

---

## 📡 Live Snapshot Space

> **DAO Space:** [https://snapshot.box/#/s:iobdao.eth](https://snapshot.box/#/s:iobdao.eth)  
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

> ✅ *Automatically refreshed by GitHub Actions (every 6 hours via `snapshot-sync.yml`)*  

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
