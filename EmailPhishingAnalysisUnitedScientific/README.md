# Phishing Email Analysis – United Scientific Equipment Impersonation

Investigated a suspicious email impersonating a legitimate company and delivering a ZIP file with a malicious executable attachment. The email used a forged sender, originated from an unrelated IP address, and included a typo-laced filename to evade detection.

This project replicates a real-world SOC Level 1 phishing triage scenario and demonstrates email header analysis, attachment inspection, hash verification, and threat intelligence techniques.

---

## Objective

- Determine whether the email is malicious  
- Extract key indicators of compromise (IOCs)  
- Analyze email metadata and sender authenticity  
- Analyze the attached file using hash and sandbox tools  

---

## Tools & Techniques

- Email header review  
- IP geolocation lookup  
- File extraction and inspection  
- SHA256 hash generation via `certutil`  
- VirusTotal malware reputation check  

---

## Summary of Findings

- **Sender:** `yanting@united.com.sg`  
- **Originating IP:** `71.19.248.52` (located in **Canada**, not Singapore)  
- **Attachment (unzipped):** `united scientific equipent.exe` *(note the typo)*  
- **SHA-256 of executable:** `9909753bfb0ac8ab165bab3555233d03b01a9274a92e57c022f87ccbe51ca415`  
- **Reputation Check:** Detected as **malicious** on VirusTotal  
- **Verdict:** Confirmed phishing with malware-laced attachment  

---

## Analyst Skills Demonstrated

- Threat detection & email triage  
- Header and IP origin analysis  
- Attachment and hash analysis  
- Malware identification using VirusTotal  
- Critical thinking in incident response  

---

## Full Report

See the complete [investigation_report.md](./investigation_report.md) for a step-by-step breakdown with tools, reasoning, and screenshots.

---

## Screenshots

Stored in the [`/screenshots`](./screenshots) folder:
- Email header metadata  
- IP geolocation result  
- Extracted malicious file  
- SHA256 hash from Command Prompt  
- VirusTotal detection  

---

## IOCs

Included in [`iocs.txt`](./iocs.txt) for detection engineering and threat hunting.


