<h2 align="center">Casey Wilson</h2>

<p align="center">
<strong>Founder &amp; Principal Architect, Soqucoin Labs</strong><br/>
Post-quantum cryptography · Blockchain consensus · Serial inventor · USAF veteran
</p>

<p align="center">
<a href="https://soqucoin.com"><img src="https://img.shields.io/badge/soqucoin.com-0A0F1C?style=for-the-badge&logoColor=white" alt="soqucoin.com"/></a>
<a href="https://soqu.org"><img src="https://img.shields.io/badge/soqu.org-0A0F1C?style=for-the-badge" alt="soqu.org"/></a>
<a href="https://pqcat.io"><img src="https://img.shields.io/badge/pqcat.io-0A0F1C?style=for-the-badge" alt="pqcat.io"/></a>
<a href="https://linkedin.com/in/odenrider"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://x.com/odenridercasey"><img src="https://img.shields.io/badge/@odenridercasey-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/></a>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Mainnet-live_since_13_Oct_2026-2EA043?style=flat-square" alt="Mainnet live"/>
<img src="https://img.shields.io/badge/Halborn_audit-30%2F30_remediated-8B5CF6?style=flat-square" alt="Halborn audit"/>
<img src="https://img.shields.io/badge/Patent_applications-21-0A2540?style=flat-square" alt="21 patent applications"/>
<img src="https://img.shields.io/badge/SBA-SDVOSB-B31B1B?style=flat-square" alt="SDVOSB"/>
</p>

---

I build cryptographic infrastructure for the post-quantum transition. NIST's draft plan (IR 8547) deprecates RSA and elliptic-curve signatures in 2030 and disallows them by 2035, and most of what secures money today was never designed to swap them out. So I'd rather build natively than retrofit.

Soqucoin is the proof: a full-stack Scrypt PoW + AuxPoW Layer 1, based on Dogecoin Core, launched from its own genesis block with ML-DSA-44 (FIPS 204) as its only signature scheme.

---

#### 🔬 What I'm Building

<table>
<tr>
<td width="50%" valign="top">

**[Soqucoin](https://github.com/soqucoin/soqucoin)** · Founding President &amp; Principal Architect
- Full-stack L1 built on NIST post-quantum signatures (FIPS 204 ML-DSA-44) from genesis
- No ECDSA in transaction authorization; 116K lines of secp256k1 removed from the tree
- Scrypt PoW with AuxPoW merge-mining from block 0 (LTC/DOGE compatible)
- Mainnet live since 13 October 2026

</td>
<td width="50%" valign="top">

**[PQCAT](https://pqcat.io)** · Post-Quantum Compliance Assessment Tool
- 11 scanner modules; scores against CNSA 2.0, NIST SP 800-131A and 11 regulatory frameworks
- Confidential Compliance Engine: hash-based binding proofs with graduated selective disclosure
- Enclave edition is free, Apache 2.0, air-gapped, with zero outbound network code
- HNDL (Harvest Now, Decrypt Later) risk quantification

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Soqupool](https://soqupool.com)** · Production Mining Pool
- Scrypt merge-mining pool: SOQ + LTC + DOGE on the same hardware
- Three active nodes across the US, Europe and Asia
- SOQ payouts signed with ML-DSA-44
- 1.69% fee; members who joined before mainnet keep 1.50% for life

</td>
<td width="50%" valign="top">

**[SOQ-TEC](https://github.com/soqucoin/soqtec)** · Colosseum Frontier Hackathon 2026
- Post-quantum custody and cross-chain settlement software for regulated custodians, exchanges and issuers, who operate it under their own licenses
- Out-of-process ML-DSA-44 signing at &lt;11ms
- Demonstrated on test networks only

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[SoquShield SDK](https://github.com/soqucoin/soqushield-sdk)** · Pure Dart PQC Wallet
- ML-DSA-44 key generation, signing and verification
- Bech32m addresses, BIP143 transaction construction
- Ships in the SoquShield wallet (TestFlight + Google Play)

</td>
<td width="50%" valign="top">

**[Lightning SDK](https://github.com/soqucoin/soq-lightning-sdk)** · Post-Quantum L2
- eLTOO payment channels with APO-based state updates
- CTV covenant vaults for off-chain settlement
- ~1,700 payments/sec/node (end-to-end, VPS-tested)

</td>
</tr>
</table>

---

#### 📊 By the Numbers

| | |
|:--|:--|
| **21** | U.S. provisional patent applications (9 Soqucoin L1, 12 PQCAT), assigned to Soqucoin Labs |
| **30 / 30** | Halborn audit findings remediated before mainnet ([case study](https://www.halborn.com/case-studies/post/case-study-halborn-secures-soqucoin-the-first-native-post-quantum-scrypt-pow-blockchain)) |
| **116K** | Lines of legacy elliptic-curve crypto removed from Soqucoin |
| **$100M** | Defense-industry awards I contributed to directly |
| **$72–122M** | Projected first-year impact at a Fortune 100 company |
| **25+** | Years: USAF active duty → DoD civilian → defense industry → Fortune 100 → founder |

---

#### 🛡️ Career Highlights

- **Soqucoin Labs** (founder). Built Soqucoin, a full-stack AuxPoW L1, from an empty repo to a live mainnet, along with the mining pool, cross-chain settlement software (SOQ-TEC, licensed technology), mobile wallet, compliance scanner (PQCAT) and a 21-application patent portfolio. The Halborn engagement also turned up a heap buffer overflow in the upstream NIST Dilithium reference implementation, a fix that matters to every project using that library.

- **U.S. Air Force, DoD and defense industry**. IA architect for 5 DoD networks under RMF. Anti-tamper risk for 1,000+ technologies. Lead Security Engineer on Grey Eagle, Predator and Global Hawk UAS programs. Direct contributor to $100M in defense-industry awards. Started as a combat comms crew chief, with campaign medals for Korea and GWOT.

#### 🎤 Speaking &amp; Recognition

- Speaker and panelist, **Mining Disrupt 2026**
- [Halborn case study](https://www.halborn.com/case-studies/post/case-study-halborn-secures-soqucoin-the-first-native-post-quantum-scrypt-pow-blockchain) on the Soqucoin audit
- Colosseum Frontier Hackathon 2026 (SOQ-TEC)
- SBA-certified Service-Disabled Veteran-Owned Small Business (Soqucoin Labs)

---

#### 📜 Patent Portfolio: 21 Applications Filed

All are U.S. provisional applications assigned to **Soqucoin Labs Inc.** ([full details →](https://soqu.org/docs/patents/))

<details>
<summary><strong>Soqucoin L1: Blockchain (9 applications)</strong></summary>

| ID | Title | Application |
|:---|:------|:------------|
| SOQ-P001 | Practical Attestation Technique (PAT): ML-DSA batch commitment to 100-byte Merkle root | 64/022,954 |
| SOQ-P002 | Lattice-BP++ Confidential Transactions: Ring-LWE commitments &amp; Dilithium stealth addresses | 64/023,515 |
| SOQ-P003 | SoquShield Post-Quantum Mobile Wallet: ML-DSA-44 key management in Dart/Flutter | 64/023,076 |
| SOQ-P004 | LatticeFold UTXO-Bound Batch Verification: recursive lattice folding for near-constant verification | 64/026,715 |
| SOQ-P005 | XMSS-Lite Revolving Vault: hash-based one-time-per-leaf custody | 64/035,857 |
| SOQ-P006 | Quantum Express Cross-Chain Transfer: post-quantum bridge protocol | 64/035,873 |
| SOQ-P007 | USDSOQ Consensus-Enforced Stablecoin: native UTXO asset typing with threshold lattice authority | 64/047,929 |
| SOQ-P010 | SoquObscura Confidential Transactions: lattice-based confidential transfer construction | 64/131,585 |
| SOQ-P011 | SoquObscura Boundary Pin (Construction A): ring-degree headroom criterion | 64/132,552 |

</details>

<details>
<summary><strong>PQCAT: Compliance Assessment (12 applications)</strong></summary>

| ID | Title | Application |
|:---|:------|:------------|
| PQCAT-P001 | Confidential Compliance Engine (CCE): zk-STARK privacy-preserving compliance verification | 63/999,796 |
| PQCAT-P001B | CCE carried forward + forward HNDL risk quantification | 64/023,449 |
| PQCAT-P010 | Cloud-Native PQ Compliance Assessment: automated CNSA 2.0 cloud asset discovery | 64/023,535 |
| PQCAT-P011 | Graduated Selective Disclosure Subsalt: tiered evidence disclosure for multi-party compliance | 64/122,032 |
| PQCAT-P012 | Cryptographic Remediation Transaction: atomic remediation commitments with rollback | 64/122,047 |
| PQCAT-P013 | Firmware Region-Bound Compliance Verdict: hardware-level PQ compliance attestation | 64/122,137 |
| PQCAT-P014 | Backward-Looking Harvest Exposure Clock: retroactive HNDL risk timeline analysis | 64/122,164 |
| PQCAT-P015 | Provenance-Bound Nine-Item Compliance Reporting: per-cell provenance for OMB M-23-02 | 64/125,634 |
| PQCAT-P016 | Cryptographic Agility Index | 64/126,113 |
| PQCAT-P017 | Retro Reconciliation and Fidelity Attribution | 64/126,154 |
| PQCAT-P018 | Plan Builder: derived completeness and refusal | 64/126,407 |
| PQCAT-P019 | Retained-Root Cross-Boundary Disclosure | 64/126,720 |

</details>

---

#### 🎓 Education &amp; Credentials

```
PhD Coursework    Systems Security Engineering, Colorado State
M.S.              Information Systems (Network Security), Dakota State
B.S.              Computer Science, Park University
CISSP             ISC² (2011–2024)
SDVOSB            Service-Disabled Veteran-Owned Small Business
Secret/SAP        Clearance (2001–2016)
```

---

#### 🔧 Tech I Work With

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![ML--DSA--44](https://img.shields.io/badge/ML--DSA--44-8B5CF6?style=flat-square)
![CNSA 2.0](https://img.shields.io/badge/CNSA_2.0-0A2540?style=flat-square)

---

#### 🤝 Work With Us

- **Partners and investors.** Mainnet is live, audited and mining. If you're building custody, settlement or compliance products that have to survive the post-quantum transition, message me on [LinkedIn](https://linkedin.com/in/odenrider).
- **Engineers.** If C++ consensus code, lattice cryptography, Go services or Dart wallets are your thing, start with the [Soqucoin repos](https://github.com/soqucoin) and open an issue. Good pull requests get noticed.

---

<sub>Soqucoin Labs Inc. · Sheridan, WY · [soqucoin.com](https://soqucoin.com) · [soqu.org](https://soqu.org) · [pqcat.io](https://pqcat.io) · [soqupool.com](https://soqupool.com) · [LinkedIn](https://linkedin.com/in/odenrider)</sub>
