# Email & Phishing Analysis

This repository contains hands-on phishing investigations and tooling designed to simulate real-world SOC triage workflows. The projects demonstrate both manual and automated approaches to email header analysis, malicious URL detection, and threat intelligence lookups.

---

## 🔍 Projects

### 📧 Phishing Case Study – PayPal Spoof (German)  
[📝 Read the Report](./PayPalPhishing/investigation_report.md)  
A detailed analysis of a spoofed PayPal phishing email targeting German users. Includes header inspection, base64 link decoding, VirusTotal analysis, and IOC documentation.  
![Skill: Phishing Triage](https://img.shields.io/badge/Skill-Phishing%20Triage-blue) ![Tool: VirusTotal](https://img.shields.io/badge/Tool-VirusTotal-yellow)

---

### 📧 Phishing Case Study – United Scientific Equipment Impersonation  
[📝 Read the Report](./UnitedScientificEquipment-Phishing/investigation_report.md)  
Business-themed phishing investigation involving a spoofed Singapore domain and a ZIP file containing a malware-laced `.exe`. Includes header and IP analysis, hash validation via `certutil`, VirusTotal confirmation, and full IOC report.  
![Skill: Email Analysis](https://img.shields.io/badge/Skill-Email%20Analysis-blue) ![Tool: Command%20Prompt](https://img.shields.io/badge/Tool-CMD-lightgrey) ![Tool: VirusTotal](https://img.shields.io/badge/Tool-VirusTotal-yellow)

---

### 🛠 Email Header & Link Analyzer (Python Script)  
[🔗 View Tool](./EmailHeaderLinkAnalyzer)  
Python tool that automates phishing investigation steps. Parses headers, extracts and decodes URLs, checks domain mismatches, and integrates with VirusTotal and WHOIS. Generates analyst-ready triage reports.  
![Skill: Automation](https://img.shields.io/badge/Skill-Automation-green) ![Language: Python](https://img.shields.io/badge/Language-Python-blue)

