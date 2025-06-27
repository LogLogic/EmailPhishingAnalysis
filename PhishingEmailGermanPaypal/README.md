# Phishing Email Analysis – German PayPal Spoof

Investigated a suspicious email written in German that impersonated PayPal and was delivered to a leaked personal email address. The email used a spoofed sender, an obfuscated malicious link, and social engineering to trick the recipient into clicking.

This project replicates a real-world SOC Level 1 phishing triage scenario and demonstrates email header analysis, link decoding, OSINT techniques, and threat detection workflow.

---

## Objective

- Identify whether the email is malicious
- Extract key indicators of compromise (IOCs)
- Analyze header metadata, embedded URLs, and sender authenticity
- Apply threat intelligence sources like VirusTotal

---

## Tools & Techniques

- Email header review
- VirusTotal
- German-to-English translation for context

---

## Summary of Findings

- **Return-Path:** `bounce@rjttznyzjzjydnillquh.designclub.uk.com`
- **Malicious link domain:** `storage.googleapis.com` (used to host phishing content)
- **Reputation Check:** Marked as phishing on VirusTotal
- **SHA-256 of email body:** `13945ecc33afee74ac7f72e1d5bb73050894356c4bf63d02a1a53e76830567f5`
- **Verdict:** Confirmed phishing

---

## Analyst Skills Demonstrated

- Threat detection & investigation  
- Email header analysis  
- Link and domain reputation checking  
- OSINT usage  
- Critical thinking in incident response

---

## Full Report

See the complete [investigation_report.md](./investigation_report.md) for a step-by-step breakdown with tools, logic, and screenshots.

---

## Screenshots

Stored in the [`/screenshots`](./screenshots) folder:
- Original email
- Emai source
- Return-Path evidence
- Phishing link
- VirusTotal analysis

---

## IOCs

Included in [`iocs.txt`](./iocs.txt) for future enrichment and alert rule creation.


