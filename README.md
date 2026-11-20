# NETWORKWALKS--SAGAR-B084-WK2-PM1--AND-PM5-CYBERSECURITY-LAB-PASSWORD-CRACKING
* *Student:* Sagar Jeswani
* *Batch:* B084
* *Week:* 3

---

## Project Scope
This repository documents the practical work completed during Week 3 of the Cybersecurity & Ethical Hacking Internship at *NETWORKWALKS (Batch B084)*, focusing on password auditing, offline cryptographic hash cracking, and browser-based password recovery workflows.

| Module | Description | Status |
| :--- | :--- | :--- |
| *W3-PM1* | Offline Hash Cracking with John the Ripper (Johnny GUI) | Completed |
| *W3-PM2* | Browser-Based Auditing with NETWORKWALKS Tools | Completed |

---

## W3-PM1 — Offline Hash Cracking with John the Ripper (Johnny GUI)
Working within an authorized lab environment, offline dictionary attacks were carried out against password-protected PDF documents:
1. *Hash Extraction:* Extracted cryptographic hashes from three encrypted PDF files.
2. *Offline Attack Execution:* Ran offline dictionary attacks using *Johnny* (the GUI frontend for *John the Ripper*).
3. *Results:* Recovered all three passwords within seconds, unlocked the encrypted PDFs, and captured the first three flags without triggering failed-login alerts.

---

## W3-PM2 — Browser-Based Auditing with NETWORKWALKS Tools
Browser-based password auditing and cross-verification were performed using the *NETWORKWALKS Hash Calculator and Password Cracker*:
1. *Fourth PDF Recovery:* Recovered the password and captured the flag for a fourth encrypted PDF document.
2. *Cross-Verification:* Tested the first three PDFs through the NETWORKWALKS toolset, confirming identical password recoveries and flags across both offline CLI/GUI and browser-based workflows.
