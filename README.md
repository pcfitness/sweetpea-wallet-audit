# sweetpea-wallet-audit
Full transparency audit of SweetPeaToken.xyz wallets flagged by RugCheck. Script + output included.

# 🌱 Sweet Pea Wallet Transparency Audit

**Audit Date:** July 5, 2025  
**Audit Purpose:** To verify all wallets flagged in RugCheck are post-launch, inactive, and non-malicious.

---

## ✅ What We Did

We scanned every `.json` keypair located in `C:\SolanaWallets` using a custom Solana CLI script via WSL. Each wallet was audited for:

- SOL balance  
- SWEETP holdings  
- Junk SPL token accounts  

---

## 📋 Results Summary

- 100% of wallets created **after launch**  
- 0 SOL in every wallet  
- 0 SWEETP across all wallets  
- No additional SPL tokens or suspicious activity detected  

---

## 🧰 Audit Script

See `audit.sh` for the full reproducible bash script.

---

## 🌐 Verification

All wallet addresses are public and viewable on [Solscan](https://solscan.io). This audit is fully transparent and reproducible by the community.

---

**Sweet Pea launched fairly via pump.fun.  
No insiders. No preloads. Just truth in the mint.**
