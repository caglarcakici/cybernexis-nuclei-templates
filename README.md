# CyberNexis Nuclei Templates

A curated collection of high-quality, **low false-positive**, and **safe-to-run** Nuclei templates developed by CyberNexis

## 🎯 Purpose

This repository focuses on:

* Detection-first security scanning
* Attack Surface Management (ASM)
* Safe vulnerability exposure identification
* Enterprise-ready scanning logic

## 📦 Included Templates

### cPanel / WHM

* **cPanel WHM Auth Bypass Exposure (CVE-2026-41940)**

  * Detects exposure conditions without exploitation
  * Checks:

    * Pre-auth session issuance
    * Canonical host behavior
    * WHM API accessibility

## 🚀 Usage

```bash
nuclei -u https://target:2087 -t cpanel/
```

## ⚠️ Design Principles

* ❌ No exploitation logic
* ✅ Safe for production environments
* ✅ Minimal false positives
* ✅ Multi-step verification

## 🧠 About CyberNexis

CyberNexis is a UK-based cybersecurity company specializing in:

* Red Teaming
* Penetration Testing
* Attack Surface Management (ASM)
* Threat Intelligence

## 📬 Contact

* Website: https://cybernexis.co.uk

---
