### Hey, I'm Casey 👋

**Systems Architect · Post-Quantum Cryptography · Serial Inventor · USAF Veteran**

I build things at the intersection of cryptography, compliance, and blockchain — where the 2030 NIST quantum deadline makes most existing infrastructure obsolete. I'd rather build natively than retrofit.

---

#### 🔬 What I'm Building

<table>
<tr>
<td width="50%" valign="top">

**[Soqucoin](https://github.com/soqucoin/soqucoin)** — Founding President & Principal Architect
- First blockchain engineered from genesis on NIST post-quantum crypto (FIPS 204 ML-DSA-44)
- No ECDSA in transaction authorization: removed 116K lines of secp256k1
- [Halborn security audit](https://www.halborn.com/case-studies/post/case-study-halborn-secures-soqucoin-the-first-native-post-quantum-scrypt-pow-blockchain): all findings remediated
- Scrypt PoW + AuxPoW merge-mining (LTC/DOGE compatible)

</td>
<td width="50%" valign="top">

**[PQCAT](https://pqcat.io)** — Post-Quantum Compliance Assessment Tool
- Enterprise scanner: 10 modules, 11 compliance frameworks (CNSA 2.0, FedRAMP, FISMA, PCI, HIPAA)
- Confidential Compliance Engine — hash-based binding proofs with graduated selective disclosure
- Dual-edition with air-gapped Enclave mode for classified environments
- HNDL (Harvest Now, Decrypt Later) risk quantification engine

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[SOQ-TEC](https://github.com/soqucoin/soqtec)** — Colosseum Frontier Hackathon 2026
- Post-quantum custody and cross-chain settlement software for regulated custodians, exchanges and issuers, who operate it under their own licences
- Out-of-process ML-DSA-44 signing at <11ms latency
- Demonstrated on test networks only

</td>
<td width="50%" valign="top">

**[SoquShield SDK](https://github.com/soqucoin/soqushield-sdk)** — Pure Dart PQC Wallet
- ML-DSA-44 key generation, signing, verification
- Bech32m addresses, BIP143 transaction construction
- TestFlight + Play Store, automated 5-platform CI/CD

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Soqupool](https://soqupool.com)** — Foundry-Grade Mining Pool
- Production KYC Scrypt AuxPoW merge-mining pool (SOQ + LTC + DOGE)
- 300 GH/s stress-tested, post-quantum signed SOQ payouts
- Flat 1.50% fee, kept permanently by members who join before mainnet (1.69% after)

</td>
<td width="50%" valign="top">

**[Lightning SDK](https://github.com/soqucoin/soq-lightning-sdk)** — Post-Quantum L2
- eLTOO payment channels with APO-based state updates
- CTV covenant vaults for off-chain settlement
- ~1,700 payments/sec/node (end-to-end, VPS-tested)

</td>
</tr>
</table>

---

#### 📊 By the Numbers

| Metric | |
|:-------|:--|
| **22** | Patent applications filed (21 Soqucoin ecosystem + Fortune 100 ONCLAVE) |
| **$72–122M** | Projected first-year impact at Fortune 100 (ONCLAVE) |
| **25+** | Years: USAF Active Duty → DoD Civilian → F500 → Founder |
| **116K** | Lines of legacy crypto removed from Soqucoin |
| **5** | Successful FedRAMP 3PAO audits led at Fortune 100 |

---

#### 📜 Patent Portfolio — 22 Applications Filed

All Soqucoin ecosystem patents are U.S. provisional applications assigned to **Soqucoin Labs Inc.** ([full details →](https://soqu.org/docs/patents/))

<details>
<summary><strong>Soqucoin L1 — Blockchain (9 patents)</strong></summary>

| ID | Title | Application |
|:---|:------|:------------|
| SOQ-P001 | Practical Attestation Technique (PAT) — ML-DSA batch commitment to 100-byte Merkle root | 64/022,954 |
| SOQ-P002 | Lattice-BP++ Confidential Transactions — Ring-LWE commitments & Dilithium stealth addresses | 64/023,515 |
| SOQ-P003 | SoquShield Post-Quantum Mobile Wallet — ML-DSA-44 key management in Dart/Flutter | 64/023,076 |
| SOQ-P004 | LatticeFold UTXO-Bound Batch Verification — recursive lattice folding for near-constant verification | 64/026,715 |
| SOQ-P005 | XMSS-Lite Revolving Vault — hash-based one-time-per-leaf custody | 64/035,857 |
| SOQ-P006 | Quantum Express Cross-Chain Transfer — post-quantum bridge protocol | 64/035,873 |
| SOQ-P007 | USDSOQ Consensus-Enforced Stablecoin — native UTXO asset typing with threshold lattice authority | 64/047,929 |
| SOQ-P010 | SoquObscura Confidential Transactions — lattice-based confidential transfer construction | 64/131,585 |
| SOQ-P011 | SoquObscura Boundary Pin (Construction A) — ring-degree headroom criterion | 64/132,552 |

</details>

<details>
<summary><strong>PQCAT — Compliance Assessment (12 patents)</strong></summary>

| ID | Title | Application |
|:---|:------|:------------|
| PQCAT-P001 | Confidential Compliance Engine (CCE) — zk-STARK privacy-preserving compliance verification | 63/999,796 |
| PQCAT-P001B | CCE carried forward + forward HNDL risk quantification | 64/023,449 |
| PQCAT-P010 | Cloud-Native PQ Compliance Assessment — automated CNSA 2.0 cloud asset discovery | 64/023,535 |
| PQCAT-P011 | Graduated Selective Disclosure Subsalt — tiered evidence disclosure for multi-party compliance | 64/122,032 |
| PQCAT-P012 | Cryptographic Remediation Transaction — atomic remediation commitments with rollback | 64/122,047 |
| PQCAT-P013 | Firmware Region-Bound Compliance Verdict — hardware-level PQ compliance attestation | 64/122,137 |
| PQCAT-P014 | Backward-Looking Harvest Exposure Clock — retroactive HNDL risk timeline analysis | 64/122,164 |
| PQCAT-P015 | Provenance-Bound Nine-Item Compliance Reporting — per-cell provenance for OMB M-23-02 | 64/125,634 |
| PQCAT-P016 | Cryptographic Agility Index | 64/126,113 |
| PQCAT-P017 | Retro Reconciliation and Fidelity Attribution | 64/126,154 |
| PQCAT-P018 | Plan Builder — derived completeness and refusal | 64/126,407 |
| PQCAT-P019 | Retained-Root Cross-Boundary Disclosure | 64/126,720 |

</details>

<details>
<summary><strong>Fortune 100 (1 patent)</strong></summary>

| ID | Title |
|:---|:------|
| ONCLAVE | AI/ML Compliance Automation Engine — FedRAMP/STIG continuous monitoring (patent pending) |

</details>

---

#### 🛡️ Career Highlights

- **Soqucoin Labs**: Founded the first native post-quantum L1 blockchain. Built the mining pool, cross-chain settlement software (SOQ-TEC, licensed technology), mobile wallet, compliance scanner (PQCAT), and 21-patent IP portfolio from zero. [Halborn-audited](https://www.halborn.com/case-studies/post/case-study-halborn-secures-soqucoin-the-first-native-post-quantum-scrypt-pow-blockchain). Stagenet live; mainnet block 1 is scheduled for 8 October 2026.

- **Fortune 100**: Invented ONCLAVE (patent pending), an AI/ML compliance automation engine. Led FedRAMP Rev 5 / 20x / ConMon automation across $18M ARR programs. 5 successful 3PAO audits. STIG compliance: 40% → 80%+ across 2,000+ controls.

- **U.S. Air Force**: IA architect for 5 DoD networks under RMF. Anti-tamper risk for 1,000+ technologies. Lead Security Engineer on Grey Eagle/Predator/Global Hawk UAS programs. Combat comms crew chief with campaign medals (Korea, GWOT).

---

#### 🎓 Education & Credentials

```
PhD Coursework    Systems Security Engineering, Colorado State
M.S.              Information Systems — Network Security, Dakota State
B.S.              Computer Science, Park University
CISSP             ISC² (2011–2024)
SDVOSB            Service-Disabled Veteran-Owned Small Business
Secret/SAP        Clearance (2001–2016)
```

---

#### 🔧 Tech I Work With

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![ML--DSA--44](https://img.shields.io/badge/ML--DSA--44-8B5CF6?style=flat-square)
![FedRAMP](https://img.shields.io/badge/FedRAMP-0A2540?style=flat-square)

---

<sub>Soqucoin Labs Inc · New York, NY · [soqu.org](https://soqu.org) · [pqcat.io](https://pqcat.io) · [soqupool.com](https://soqupool.com) · [LinkedIn](https://linkedin.com/in/odenrider)</sub>
