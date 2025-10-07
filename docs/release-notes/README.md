# 🧾 IO Beats DAO — Release Notes & Version History

[![Docs](https://img.shields.io/badge/Documentation-GitHub-green?logo=github)](https://github.com/iobeatss/treasury/tree/main/docs/release-notes)
[![Changelog](https://img.shields.io/badge/Changelog-Auto--Generated-blue?logo=githubactions&logoColor=white)](https://github.com/iobeatss/treasury/releases)
[![Transparency](https://img.shields.io/badge/Treasury-Transparency-orange?logo=dune&logoColor=white)](https://dune.com/iobeats_dao)

---

## 📘 Overview

This section archives all **official release notes**, **framework updates**, and **PDF reports**  
for IO Beats DAO’s governance, transparency, and treasury documentation.

Each entry is tied to a **version tag** and **GitHub release**, ensuring full traceability and auditability.

---

## 🗂️ Latest Release

| Version | Date | Description | Link |
|----------|------|--------------|------|
| **v1.1** | Oct 2025 | DAO Governance Framework integration and transparency pack updates. | [v1.1.md](./v1.1.md) |

---

## 🪪 Governance Documents

| Document | Version | Date | Link |
|-----------|----------|------|------|
| **DAO Governance Framework (Premium Edition)** | v1.0 | Oct 2025 | [PDF](../governance/IOB_DAO_Governance_Framework_v1.0_PremiumEdition.pdf) |
| **DAO Snapshot Governance Activation Report** | v1.0 | Oct 2025 | [PDF](../governance/DAO_Snapshot_Governance_Activation_IOB_Vote.pdf) |

---

## 💼 Treasury Transparency Reports

| Report | Version | Date | Link |
|--------|----------|------|------|
| **Safe Multichain Transparency Report** | v1.0 | Oct 2025 | [PDF](../transparency/IOB_Safe_Multichain_Transparency_Report_v1.0.pdf) |
| **DAO Analytics Transparency Report** | v1.0 | Oct 2025 | [PDF](../transparency/IOB_DAO_Analytics_Transparency_Report_v1.0.pdf) |
| **Per-Chain Transparency Packs** | v1.0 | Oct 2025 | [Directory](../transparency/) |

---

## 🧩 Change History

| Version | Key Updates |
|----------|--------------|
| **v1.1** | Added DAO Governance Framework (Premium Edition) · Updated Transparency Pack Index · Added Dune dashboards links |
| **v1.0** | Initial structure setup for Transparency, Governance, and DAO Reports |

---

## ⚙️ Automation Notes

- **GitHub Actions:** Auto-generates changelog entries and PDF index after each release.  
- **Directory Sync:** Keeps `/docs/governance` and `/docs/transparency` in sync.  
- **Workflow File:** `.github/workflows/release-notes.yml` handles PDF discovery and metadata updates.

```mermaid
graph LR
  A[GitHub Release] --> B[Workflow: release-notes.yml]
  B --> C[Update v*.md files]
  C --> D[Commit to /docs/release-notes/]
  D --> E[Trigger Changelog & Index Refresh]
