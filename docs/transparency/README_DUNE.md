<p align="center">
  <img src="https://raw.githubusercontent.com/iobeatss/iobeats-logo-assets/main/hero1.gif"
       alt="IO Beats Treasury Banner" width="100%" />
</p>

# 📊 IOB_Dune_Transparency_Automation_v1.0  
*Automated Multichain Safe Analytics & Treasury Sync*
[![Ethereum Sync](https://github.com/iobeatss/treasury/actions/workflows/dune-ethereum.yml/badge.svg)](../../.github/workflows/dune-ethereum.yml)
[![BNB Sync](https://github.com/iobeatss/treasury/actions/workflows/dune-bnb.yml/badge.svg)](../../.github/workflows/dune-bnb.yml)
[![Base Sync](https://github.com/iobeatss/treasury/actions/workflows/dune-base.yml/badge.svg)](../../.github/workflows/dune-base.yml)
[![Polygon Sync](https://github.com/iobeatss/treasury/actions/workflows/dune-polygon.yml/badge.svg)](../../.github/workflows/dune-polygon.yml)
[![Arbitrum Sync](https://github.com/iobeatss/treasury/actions/workflows/dune-arbitrum.yml/badge.svg)](../../.github/workflows/dune-arbitrum.yml)

---

## 🌍 Overview
The **Dune Transparency Program** automatically synchronizes on-chain Safe analytics across
**Ethereum, BNB Chain, Base, Polygon, and Arbitrum**.

Each chain has a dedicated Dune dashboard and a GitHub Actions workflow that fetches
real-time inflows / outflows / balance data and stores the exported results as JSON at  
`data/dune/<chain>/latest.json`.

These datasets feed the IO Beats **Treasury Transparency Reports** and **Dune** visual dashboards.

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
flowchart LR
    A[Dune Query (SQL)] -->|API Call| B[GitHub Actions Workflow]
    B -->|Execution ID| C[Fetch JSON Results]
    C -->|Write Files| D[data/dune/<chain>/latest.json]
    D -->|Feeds| E[IO Beats Transparency Reports & Dashboards]
