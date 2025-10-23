# 🌀 LHDNS — Ledger-based Hashed Decentralized Naming System

**Status:** Open Source  
**Version:** v1.0  
**License:** Apache 2.0  

---

## 🌐 Overview
**LHDNS (Ledger-based Hashed Decentralized Naming System)** is a next-generation naming architecture that replaces centralized DNS trust anchors with a **ledger-backed, privacy-preserving, and censorship-resistant resolution layer**.

It introduces **ephemeral hash-tokens**, **rotating nonces**, and **decentralized consensus** to ensure that name lookups are verifiable, unlinkable, and privacy-safe.  
LHDNS is designed for global interoperability — bridging traditional DNS with decentralized systems through gateways, browser APIs, and dual-stack compatibility.

---

## 📘 Included Documents

| File | Description |
|------|--------------|
| **`LHDNS_Whitepaper_v1.0.pdf`** | The main whitepaper outlining the architecture, design principles, protocol flow, governance, and roadmap. |
| **`LHDNS_Appendix_A_TechnicalModules.pdf`** | Canonical module specifications, message formats, cryptographic parameters, and operational logic. |
| **`LHDNS_Annex_A_ExtendedTechnicalReport.pdf`** | Extended technical deep-dive and formal analysis of the system. |
| **`LHDNS_Appendix_B_Glossary.pdf`** | Definitions of all core terms and cryptographic concepts used in the project. |
| **`LHDNS_Appendix_C_References.pdf`** | References to foundational work and related research in decentralized naming, cryptography, and distributed systems. |
| **`LHDNS_Appendix_D_ThreatScenarios.pdf`** | Threat models, attack trees, and corresponding mitigation strategies. |

---

## 🧩 Core Principles

- **Decentralization of trust** — no single authority or root zone.  
- **Ephemeral state** — short-lived ledger entries and session-based identifiers.  
- **Privacy & Unlinkability** — rotating nonces, onion routing, cover traffic.  
- **Cryptographic integrity** — signatures, verifiable hashes, ledger-backed proofs.  
- **Censorship resistance** — multi-path routing, decentralized consensus.  
- **Scalability & deployability** — designed for real-world adoption and gradual DNS migration.  

---

## 🛠 Technical Summary

| Component | Technology |
|------------|-------------|
| Signature | Ed25519 |
| Key Exchange | X25519 |
| Encryption | XChaCha20-Poly1305 |
| Hash | SHA-256 / BLAKE3 |
| Ledger Model | Gossip-based ephemeral entries |
| Governance | DAO with token-weighted voting |
| Token | LHD (utility token for fees, staking, and governance) |

---

## 🧠 Governance & Economics
- **DAO governance** controls parameters like TTL, PoW difficulty, and relay incentives.  
- **LHD token** powers staking, relay rewards, and validator participation.  
- **Treasury** supports audits, grants, and ecosystem development.  

---

## 🔐 Security Model
LHDNS defends against:
- Passive surveillance and traffic correlation  
- Active censorship and resolver hijacking  
- Sybil, Eclipse, and replay attacks  
- Service descriptor poisoning and DoS flooding  

Defenses include: ephemeral keys, PoW throttling, cover traffic, staking + slashing, multipath relays, and verifiable signatures.

---

## ⚙️ Roadmap (Simplified)

| Phase | Description | Timeline |
|-------|--------------|-----------|
| 0 | Prototype design, initial validation | 0–6 months |
| 1 | Private testnet + SDKs | 6–12 months |
| 2 | Public testnet + gateway rollout | 12–18 months |
| 3 | Pilot deployments, early governance | 18–24 months |
| 4 | Mainnet launch | 24–36 months |
| 5 | Ecosystem expansion & post-quantum readiness | 36m+ |

---

## 🤝 Contributing
LHDNS is fully open-source.  
You can contribute by:
- Reviewing and improving documentation  
- Implementing SDKs and client libraries  
- Running validator or relay nodes  
- Suggesting governance parameters via pull requests  

> All contributions must comply with the [Apache 2.0 License](./LICENSE).

---

## 📫 Contact
**Author:** Ahmad Hemmati  
**Website:** [https://www.twincodesworld.com](https://www.twincodesworld.com)  
**Repository:** [https://github.com/twincodesworld/LHDNS](https://github.com/twincodesworld/LHDNS)  
**Email:** contact@twincodesworld.com  
---

### ✳️ Citation
If you reference this project in research or articles:

```Hemmati, A. (2025). LHDNS: Ledger-based Hashed Decentralized Naming System. GitHub Repository. https://github.com/twincodesworld/LHDNS```

---

> “Freedom begins when information flows without permission.”  
> “Think Different To Be Different”  
> — *LHDNS Whitepaper, v1.0*
