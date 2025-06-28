# Email & Phishing Analysis

This repository contains hands-on phishing investigations and tooling designed to simulate real-world SOC triage workflows. The projects demonstrate both manual and automated approaches to email header analysis, malicious URL detection, and threat intelligence lookups.

---

## 🔍 Projects

### 📧 Phishing Case Study – PayPal Spoof (German)  
[📝 Read the Report](https://github.com/LogLogic/EmailPhishingAnalysis/blob/main/PhishingEmailGermanPaypal/investigation_report.md) 
A detailed analysis of a spoofed PayPal phishing email targeting German users. Includes header inspection, base64 link decoding, VirusTotal analysis, and IOC documentation.  

---

### 📧 Phishing Case Study – United Scientific Equipment Impersonation  
[📝 Read the Report](https://github.com/LogLogic/EmailPhishingAnalysis/blob/main/EmailPhishingAnalysisUnitedScientific/investigation_report.md)  
Business-themed phishing investigation involving a spoofed Singapore domain and a ZIP file containing a malware-laced `.exe`. Includes header and IP analysis, hash validation via `certutil`, VirusTotal confirmation, and full IOC report.  

---

### 🛠 Email Header & Link Analyzer (Python Script)  
[🔗 View Tool](https://github.com/LogLogic/EmailHeaderLinkAnalyzer)  
Python tool that automates phishing investigation steps. Parses headers, extracts and decodes URLs, checks domain mismatches, and integrates with VirusTotal and WHOIS. Generates analyst-ready triage reports.  

