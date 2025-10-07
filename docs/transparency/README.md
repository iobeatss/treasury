# 🪪 IO Beats DAO — Treasury Transparency Reports

[![Dune Dashboard](https://img.shields.io/badge/Dune-Dashboard-blue?logo=dune&logoColor=white)](https://dune.com/iobeats_dao)
[![DAO Governance](https://img.shields.io/badge/DAO-Governance-purple?logo=snapshot&logoColor=white)](https://snapshot.box/#/s:iobdao.eth)
[![GitHub Docs](https://img.shields.io/badge/Docs-GitHub-green?logo=github)](https://github.com/iobeatss/treasury/tree/main/docs/transparency)

---

## 📘 Overview

Welcome to the **IO Beats DAO Transparency Hub**.  
This section centralizes **audited financial reports**, **on-chain dashboards**, and **multichain treasury documents**.  

All transparency materials are **verifiable on-chain**, **publicly accessible**, and **audited by Cyberscope**.

---

## 🌍 Global Transparency Reports

| Report | Version | Date | Link |
|--------|----------|------|------|
| **Global DAO Analytics Report** | v1.0 | Oct 2025 | [PDF](./IOB_DAO_Analytics_Transparency_Report_v1.0.pdf) |
| **Safe Multichain Transparency Report** | v1.0 | Oct 2025 | [PDF](./IOB_Safe_Multichain_Transparency_Report_v1.0.pdf) |
| **Dune Dashboard (Live)** | — | Real-Time | [View on Dune](https://dune.com/iobeats_dao) |
| **Automation Overview (Dune + GitHub)** | v1.0 | Oct 2025 | [PDF](./IOB_Dune_Transparency_Automation_v1.0.pdf) |

---

## 🪙 Per-Chain Transparency Packs

Each blockchain maintains an independent transparency pack containing multisig activity, inflows/outflows,  
staking allocations, and DeFi strategy updates.  

| Chain | Report | Version | Link |
|--------|---------|----------|------|
| **Ethereum** | Treasury Transparency Report | v1.0 | [PDF](./IOB_Treasury_Transparency_ETH_v1.0.pdf) |
| **BNB Chain** | Treasury Transparency Report | v1.0 | [PDF](./IOB_Treasury_Transparency_BNB_v1.0.pdf) |
| **Base (L2)** | Treasury Transparency Report | v1.0 | [PDF](./IOB_Treasury_Transparency_Base_v1.0.pdf) |
| **Polygon** | Treasury Transparency Report | v1.0 | [PDF](./IOB_Treasury_Transparency_Polygon_v1.0.pdf) |
| **Arbitrum** | Treasury Transparency Report | v1.0 | [PDF](./IOB_Treasury_Transparency_Arbitrum_v1.0.pdf) |

> 🔍 Each pack includes wallet addresses, inflow/outflow charts, Dune dashboard snapshots, and Safe verification.

---

## 🧩 Related Documents

| Document | Version | Description | Link |
|-----------|----------|--------------|------|
| **IOB Presale BeatsApe Report** | v1.0 | Presale and token allocation audit | [PDF](./IOB_Presale_BeatsApe_v1.0.pdf) |
| **IOB Payroll Infrastructure** | v1.0 | DAO payroll & Sablier vesting setup | [PDF](../IOB_Payroll_Infrastructure_v1.0.pdf) |
| **IOB Academy Preview** | v1.0 | DAO learning & community development | [PDF](../IOB_Academy_Preview_v1.0.pdf) |

---

## ⚙️ Automation & Dune Integration

Transparency data is continuously updated through:
- **Dune Dashboards** — On-chain inflows/outflows & Safe balances  
- **GitHub Actions** — Automated document sync and version tagging  
- **JSON Logs** — Each chain’s latest data stored in `/data/dune/`  

```mermaid
flowchart LR
  A[Dune API / Safe Explorer] --> B[GitHub Actions Workflow]
  B --> C[data/dune/latest.json]
  C --> D[docs/transparency/README.md]
  D --> E[GitHub Pages / Treasury Portal]
