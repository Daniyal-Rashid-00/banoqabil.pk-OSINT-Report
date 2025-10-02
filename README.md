# BanoQabil — OSINT Report  
**Author:** Daniyal Rashid  
**Date:** July 2025  
**Repo:** Public OSINT engagement and findings for `banoqabil.pk`.  

---

## 📌 Executive Summary
This report documents an **Open Source Intelligence (OSINT)** investigation on `banoqabil.pk`.  
The goal was to map publicly available information such as domains, subdomains, hosting details, and exposed metadata.  

🔎 **High-level findings:**  
- 38 subdomains identified  
- Security headers missing on key endpoints  
- TLS configuration could be hardened  

The full PDF report provides details, screenshots, and prioritized remediation steps.

---

## 📂 Files
- [`Banoqabil-OSINT-Report.pdf`](./Banoqabil-OSINT-Report.pdf) — full PDF report  
- [`assets/preview.png`](./assets/preview.png) — executive summary preview (optional)  

---

## 🛠️ Scope & Methodology
- **Scope:** Domain, DNS, WHOIS, subdomains, hosting environment  
- **Techniques:** Passive reconnaissance, certificate transparency search, DNS enumeration  
- **Tools used:** Amass, Sublist3r, crt.sh, Shodan, and manual verification  

---

## ✅ Key Findings
- Multiple subdomains exposed with outdated frameworks  
- Security misconfigurations (missing `X-Frame-Options`, `Content-Security-Policy`)  
- TLS settings allowed weak ciphers  

---

## 📌 Recommendations
- Harden TLS to enforce modern ciphers  
- Add missing security headers across web apps  
- Regular subdomain monitoring to detect shadow IT or forgotten assets  

---

## 📜 License
- **Report PDF & documentation:** [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) — attribution required, non-commercial use only  
- **Any code/scripts (if added later):** MIT License  

---

## ⚠️ Disclaimer
This repository contains **redacted and client-approved findings**. Sensitive information has been removed.  
For full details, please contact me directly.  
