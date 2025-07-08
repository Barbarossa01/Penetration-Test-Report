# 🛡️ Penetration Testing Report – CodeNimbus Systems (Demo)

This repository contains a structured penetration testing report conducted on a simulated target environment named **CodeNimbus Systems**. The purpose of this project is to demonstrate real-world offensive security testing skills and documentation practices in a responsible, educational, and ethical manner.

## 📌 Scope of Work

The assessment focuses on identifying vulnerabilities within a web application environment, simulating an authenticated and unauthenticated attacker. The target included login flows, admin interfaces, file servers, and user data endpoints.

## 🔍 Identified Vulnerabilities

| # | Vulnerability | CVSS Score | CWE | Severity |
|---|---------------|------------|-----|----------|
| 1 | SQL Injection (GET `id` param) | 9.1 | CWE-89 | Critical |
| 2 | Stored XSS in Admin Profile | 8.0 | CWE-79 | High |
| 3 | Broken Access Control – Admin Page | 9.6 | CWE-284 | Critical |
| 4 | SSRF in URL Parameter | 9.1 | CWE-918 | Critical |
| 5 | Reflected XSS (`k304` param) | 6.1 | CWE-79 | Medium |
| 6 | Insecure Password Reset (Security Questions) | 9.1 | CWE-640 | Critical |
| 7 | IDOR – View Other Users' Notes | 6.5 | CWE-639 | Medium |
| 8 | Autocomplete-Enabled Password Field | 3.1 | CWE-524 | Low |

Each vulnerability includes:
- Steps to Reproduce
- CVSS v3.1 Calculation
- CWE Reference
- Description & Recommendations

## 📁 Files

- `SecurityAssessmentReport_CodeNimbus_Systems.pdf` – Full penetration testing report
- `screenshots/` – Proof-of-concept evidence
- `readme.md` – This file


## 🧠 Purpose

This is a red-team style demo project built for educational purposes and professional portfolio presentation.  
**No real production system was targeted.**

## 🚨 Disclaimer

> This content is for **educational and ethical** use only. Do **not** attempt to replicate these attacks on systems you do not own or have explicit permission to test.

## 👨‍💻 Author

- **Name:** Muhammad Zain Din
- **Certifications:** eWPT, eJPT, 
- **LinkedIn :** https://www.linkedin.com/in/muhammad-zaindin/

---

## 📬 Contact

Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/muhammad-zaindin/) or open an issue if you have questions.

