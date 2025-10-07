# 📊 IOB Dune Transparency Automation v1.0  
*Automated Multichain Safe Analytics & Treasury Sync*

  <a href="../../.github/workflows/dune-ethereum.yml"><img src="https://github.com/iobeatss/treasury/actions/workflows/dune-ethereum.yml/badge.svg" alt="Ethereum Sync" /></a>
  <a href="../../.github/workflows/dune-bnb.yml"><img src="https://github.com/iobeatss/treasury/actions/workflows/dune-bnb.yml/badge.svg" alt="BNB Sync" /></a>
  <a href="../../.github/workflows/dune-base.yml"><img src="https://github.com/iobeatss/treasury/actions/workflows/dune-base.yml/badge.svg" alt="Base Sync" /></a>
  <a href="../../.github/workflows/dune-polygon.yml"><img src="https://github.com/iobeatss/treasury/actions/workflows/dune-polygon.yml/badge.svg" alt="Polygon Sync" /></a>
  <a href="../../.github/workflows/dune-arbitrum.yml"><img src="https://github.com/iobeatss/treasury/actions/workflows/dune-arbitrum.yml/badge.svg" alt="Arbitrum Sync" /></a>


---

## 📄 Download PDF Report

[![PDF Download](https://img.shields.io/badge/Download-Dune_Automation_v1.0-orange?logo=adobeacrobatreader)](./IOB_Dune_Transparency_Automation_v1.0.pdf)

---

## 🌍 Overview

The **Dune Transparency Program** automatically synchronizes on-chain Safe analytics across  
**Ethereum, BNB Chain, Base, Polygon, and Arbitrum**.

Each chain has a dedicated Dune dashboard and a GitHub Actions workflow that fetches  
real-time inflows / outflows / balance data and stores the exported results as JSON under  
`data/dune/<chain>/latest.json`.

These datasets feed the IO Beats **Treasury Transparency Reports** and **Dune** visual dashboards.

---

---

## 🔗 Live Dashboards

| Chain | Dashboard Link | Query ID | Workflow | Latest Data |
|------:|----------------|:--------:|:--------:|:-----------:|
| **Ethereum** | [View on Dune](https://dune.com/iobeats_dao/iobeats-dao-ethereum-safe) | `5913366` | [`dune-ethereum.yml`](../../.github/workflows/dune-ethereum.yml) | [`latest.json`](../../data/dune/ethereum/latest.json) |
| **BNB Chain** | [View on Dune](https://dune.com/iobeats_dao/iobeats-dao-bnb-safe) | `5915771` | [`dune-bnb.yml`](../../.github/workflows/dune-bnb.yml) | [`latest.json`](../../data/dune/bnb/latest.json) |
| **Base** | [View on Dune](https://dune.com/iobeats_dao/iobeats-dao-base-safe) | `5915633` | [`dune-base.yml`](../../.github/workflows/dune-base.yml) | [`latest.json`](../../data/dune/base/latest.json) |
| **Polygon** | [View on Dune](https://dune.com/iobeats_dao/iobeats-dao-polygon-safe-analytics) | `5915833` | [`dune-polygon.yml`](../../.github/workflows/dune-polygon.yml) | [`latest.json`](../../data/dune/polygon/latest.json) |
| **Arbitrum** | [View on Dune](https://dune.com/iobeats_dao/iobeats-dao-arbitrum-safe-analytics) | `5916028` | [`dune-arbitrum.yml`](../../.github/workflows/dune-arbitrum.yml) | [`latest.json`](../../data/dune/arbitrum/latest.json) |

---

## ⚙️ Automation Architecture

```mermaid
%%{init: {'theme': 'default', 'themeVariables': { 'primaryColor': '#f97316', 'edgeLabelBackground':'#ffffff', 'fontSize': '14px'}}}%%
flowchart LR
    A["Dune Query (SQL)"] -->|"API Call"| B["GitHub Actions Workflow"]
    B -->|"Execution ID"| C["Fetch JSON Results"]
    C -->|"Write Files"| D["data/dune/<chain>/latest.json"]
    D -->|"Feeds"| E["IO Beats Transparency Reports & Dashboards"]
