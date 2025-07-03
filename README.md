# Absu

[![License: Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-green.svg)](LICENSE)
[![Build Status](https://img.shields.io/github/actions/workflow/status/AbsoluteRealms/absu/ci.yml?branch=main)](../../actions)
[![Release](https://img.shields.io/github/v/release/AbsoluteRealms/absu)](../../releases)
[![Documentation](https://img.shields.io/badge/docs-latest-blue)](/docs)

> **Absu** is a domain-driven, enterprise-grade blockchain platform—forked from Hyperledger Besu and shaped by unique financial and institutional drivers.  
> Brought to you by DBIS - Innovations, with MLFO sponsorship.

---

## Table of Contents

- [Background & Origin](#background--origin)
- [Technical Lineage](#technical-lineage)
- [Architecture Diagram](#architecture-diagram)
- [Features](#features)
- [Quick Start](#quick-start)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Background & Origin

**Absu** is the direct result of MLFO’s journey toward strategic and technical autonomy after a historic \$27 trillion USD payment, held and debited by the Bank for International Settlements (BIS).  
This event catalyzed the formation of **DBIS - Innovations**, tasked with building next-generation financial infrastructure.  
After a successful proof-of-concept, MLFO funded DBIS’s efforts, leading to the creation of Absu—a specialized, enterprise-focused fork of Hyperledger Besu.

---

## Technical Lineage

| Stage/Event           | Actor/Entity        | Action/Outcome                                      |
|-----------------------|---------------------|-----------------------------------------------------|
| Initial Payment       | MLFO/BIS            | \$27T USD payment held, debited by BIS              |
| Innovation Spin-off   | MLFO/DBIS           | MLFO sponsors innovation → DBIS is created          |
| PoC & Funding         | MLFO/DBIS           | PoC delivered, MLFO funds DBIS - Innovations        |
| Tech Stack Decision   | DBIS                | Selects Hyperledger, with focus on Besu             |
| Fork & Customization  | DBIS - Innovations  | Forks HLF Besu → **Absu**                           |

---

## Architecture Diagram

```text
[MLFO]
   |
   |-- (BIS debits $27T USD payment)
   v
[BIS]
   |
   v
(MLFO seeks new solutions)
   |
   v
[MLFO sponsors innovation]
   |
   v
[DBIS (Di-BoIS) spin-off]
   |
   |-- (Proof of Concept)
   v
[MLFO funds "DBIS - Innovations"]
   |
   |-- (DBIS selects Hyperledger Besu)
   v
[DBIS - Innovations]
   |
   |-- (Forks Hyperledger Besu)
   v
[Absu: "DBIS - Innovations" fork of HLF Besu]
