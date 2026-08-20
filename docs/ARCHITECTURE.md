# 🏛️ Aegis Scam Firewall — Architectural Specification

## Threat Vector Analysis
Modern mobile threat actors utilize multi-stage social engineering vectors:
1. **Financial Panic**: Fake utility bills (e.g., "Electricity will be disconnected tonight").
2. **Account Suspension**: Impersonation of national banks (SBI, HDFC, ICICI, PNB) requesting KYC re-verification.
3. **Lottery & Reward Phishing**: High-urgency cash prize claims with malicious tracking links.

## Multi-Pass On-Device Detection Pipeline

### Layer 1: Deterministic Heuristic Engine
- **Entropy Analysis**: Evaluates Shannon entropy of message bodies and embedded URLs to detect obfuscated character sets.
- **Urgency Scoring**: Synthesizes temporal pressure terms ("within 2 hours", "immediate", "suspended").
- **Statutory Identifier Matching**: Cross-references sender alphanumeric headers against verified government and financial institution whitelist registries.

### Layer 2: Vectorization & Probabilistic NLP
- **Quantized TF-IDF Feature Extraction**: Sub-millisecond unigram/bigram token mapping designed for edge ARM CPUs.
- **Multinomial Naive Bayes Inference**: High-precision probabilistic class estimation operating with `< 0.2 µs` execution overhead and minimal thermal profile.

### Layer 3: Risk Governor & Adaptive Action
- **Quarantine Logic**: High-confidence threats trigger immediate notification suppression and security quarantine.
- **Visual Warning Injection**: Medium-confidence alerts display contextual caution overlays with safe link previews.

---
*Maintained by Anbuselvan T. ([@Anbu-2006](https://github.com/Anbu-2006)). All Rights Reserved.*
