# ?? Repo Standing Statement

This repository is a **sovereign original** under **Elmahrosa International � TEOS Egypt**.  
Governance is anchored in [TEOS-FORGE](https://github.com/Elmahrosa/TEOS-FORGE).  
Commercial use requires written approval from Elmahrosa International.  

?? Protected under dual license: PolyForm Noncommercial + TEOS Egypt Sovereign License (TESL).

# TEOS Payment Rail

Sovereign payment rail specification for $TEOS  
Maintained by **Elmahrosa International**

---

## 🎯 Purpose

TEOS Payment Rail defines a **non-custodial, on-chain settlement framework**  
for value transfer using the $TEOS token.

This repository is **specification-first**, not a live payment service.

---

## 📁 Directory Structure

The project is organized as follows:

```
TEOS-Payment-Rail/
├── README.md
├── LICENSE
├── rail/
│   ├── rail-spec.md           # Core technical specification of the payment rail
│   ├── supported-assets.json  # List of supported tokens and their metadata
│   └── settlement-model.md    # Detailed description of the settlement process
├── compliance/
│   ├── regulatory-scope.md    # Regulatory framework and scope of operation
│   └── prohibited-uses.md     # List of activities explicitly disallowed by the rail
├── docs/
│   ├── architecture.md        # High-level system architecture
│   └── glossary.md            # Definitions of key terms and acronyms
└── VERSION                    # Current version of the specification
```

---

## 🔹 Scope

This rail is designed for:

- Domestic digital settlement research
- Regulated fintech pilots
- Closed-loop institutional systems
- Government & academic evaluation

It is **NOT** a public payment network.

---

## 🧱 Core Principles

- **No custody of user funds**: Users retain control of their private keys at all times.
- **No minting or inflation**: The $TEOS token supply is fixed and governed by its mint parameters.
- **No hidden fees**: All transaction costs are transparent and documented.
- **On-chain verifiability**: All operations are recorded on the Solana blockchain for auditability.
- **Compliance-first design**: Built with regulatory frameworks as a foundational constraint.

---

## 🪙 Supported Token

- **Token:** TEOS  
- **Chain:** Solana  
- **Mint:** `AhXBUQmbhv9dNoZCiMYmXF4Gyi1cjQthWHFhTL2CJaSo`  
- **Mint Authority:** Revoked  
- **Freeze Authority:** Revoked  

---

## ⚠️ Important Notice

This repository does NOT:

- Provide payment services  
- Act as a bank, PSP, or wallet  
- Enable merchant onboarding  
- Handle fiat conversion  
- Bypass financial regulation  

Implementation requires **explicit written authorization**.

---

## 📜 License

PolyForm Noncommercial License 1.0.0  
See [LICENSE](./LICENSE)

---

## 🧾 Versioning

The `VERSION` file tracks the current specification version.  
Example format:

```
1.0.0
```

---

## 📚 Documentation

### 📄 `rail-spec.md`
Core technical specification for the TEOS Payment Rail, including:
- Settlement protocols
- Smart contract logic
- On-chain validation rules

### 📄 `supported-assets.json`
JSON file listing all supported tokens and their parameters (e.g., mint addresses, decimals, compliance tags).  
Example format:
```json
{
  "tokens": [
    {
      "name": "TEOS",
      "symbol": "TEOS",
      "chain": "Solana",
      "mint": "AhXBUQmbhv9dNoZCiMYmXF4Gyi1cjQthWHFhTL2CJaSo",
      "decimals": 9,
      "compliance_tags": ["regulated", "non-custodial"]
    }
  ]
}
```

### 📄 `settlement-model.md`
Detailed breakdown of the on-chain settlement process, including:
- Transaction lifecycle
- Atomic swaps
- Finality guarantees

### 📄 `regulatory-scope.md`
Explanation of the regulatory frameworks governing this rail, including:
- Jurisdictional compliance
- KYC/AML integration points
- Reporting requirements

### 📄 `prohibited-uses.md`
List of activities explicitly disallowed by the rail, such as:
- Custodial operations
- Unregulated cross-border transfers
- Token minting or freezing without authorization

### 📄 `architecture.md`
High-level overview of the system architecture, including:
- Layer 1 blockchain integration
- Off-chain coordination layers
- On-chain verification mechanisms

### 📄 `glossary.md`
Definitions of key terms for clarity, such as:
- **Non-custodial**: Users retain ownership of funds at all times
- **Settlement**: Final transfer of value on-chain
- **Rail**: Infrastructure for structured, compliant value transfers

---

© Elmahrosa International — Sovereign Financial Infrastructure
```

---


## ?? Integration Summary
This repository is part of the **Elmahrosa Sovereign Stack**.  
Governance is anchored in **TEOS-FORGE**, with integrations across Bankchain, ERT-LAUNCH, FPBE, and other civic modules.  
See full details in [docs/integrations.md](https://github.com/Elmahrosa/TEOS-FORGE/blob/main/docs/integrations.md).
