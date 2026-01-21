# Radiotomy-oncore-xion
Core protocol for the Oncore cultural economy on the XION blockchain. Includes CosmWasm smart contracts, bonding‑curve token logic, factories, registries, SDK, indexer, governance modules, and integration specs for the Oncore platform.
Here’s a **clean, sharp, protocol‑grade README** you can drop directly into your new repo.  
It’s concise, professional, and sets the right tone for a CosmWasm‑based blockchain protocol.

---

# **Oncore XION Protocol**

Core protocol implementation for the **Oncore cultural economy** on the **XION blockchain**.  
This repository contains the smart contracts, specifications, SDK, and indexing modules that power the on‑chain layer of the Oncore platform.

Oncore enables a sovereign cultural economy for music creators and fans through:

- Artist career tokens  
- Project tokens with bonding‑curve funding  
- The ONC platform token  
- Creator and platform treasuries  
- Governance and world‑state mechanics  
- A Living World system that influences economic behavior  

This repo houses the **entire protocol layer**, separate from the Base44 application.

---

## **Repository Structure**

```
oncore-xion-protocol/
  ├── specs/           # Architecture & contract specifications
  ├── contracts/       # CosmWasm smart contracts (Rust)
  ├── sdk/             # TypeScript client SDK for apps (incl. Base44)
  ├── indexer/         # SubQuery/Numia indexer for on-chain events
  ├── governance/      # Governance modules & weighting logic
  ├── integration/     # Integration docs & contract address registry
  ├── scripts/         # Deployment & optimization scripts
  └── tests/           # cw-multi-test integration tests
```

---

## **Technology Stack**

- **CosmWasm (Rust)** — smart contracts  
- **XION blockchain** — execution environment  
- **cw-multi-test** — contract testing  
- **SubQuery / Numia** — indexing  
- **TypeScript** — SDK and integration layer  

---

## **Development Status**

This repository is part of the **Oncore → XION migration**, following a phased architecture:

- **Phase 3:** Core token layer (ONC, ArtistToken, ProjectToken)  
- **Phase 4:** AMM / DEX  
- **Phase 5:** Treasuries & payout splits  
- **Phase 6:** Governance & Living World hooks  
- **Phase 7:** Gasless UX, indexing, production hardening  

Specs for each phase are included in `/specs`.

---

## **License**

This project is licensed under the **MIT License**, enabling open collaboration and ecosystem growth.

---

## **Contributing**

Contributions are welcome.  
Please review the specs in `/specs` before submitting PRs to ensure alignment with the protocol architecture.

---

## **Related Repositories**

- **Oncore App (Base44):** https://github.com/Radiotomy/oncore  
  *(Frontend + AI systems + Living World + UX)*

---
