# Networkwalks Cybersecurity Internship — Week 3 Lab Report

This repository contains the practical lab documentation, methodology, and evidence for **Week 3 (Password Cracking & Hash Extraction)** of the **Networkwalks Cybersecurity Internship Program**.

---

## Lab Overview

| Module | Task Description | Tools Used | Target File |
| :--- | :--- | :--- | :--- |
| **W3-PM1** | Offline PDF Hash Extraction & Dictionary Attack | `pdf2john`, John the Ripper (CLI), Johnny (GUI) | `My Locked PDF1.pdf` |
| **W3-PM2** | Online PDF Hash Calculation & Password Recovery | Networkwalks Hash Calculator & Password Cracker | `My Locked PDF1 (for NW Tools Lab WK3-PM2).pdf` |

---

## Key Execution Steps

### 1. Offline Password Cracking (W3-PM1)
* Extracted the cryptographic hash from the target PDF file using `pdf2john` in Kali Linux.
* Executed a dictionary-based password recovery attack using **John the Ripper** against the `rockyou.txt` wordlist.
* Verified the recovered credentials via both CLI (`john --show`) and **Johnny** graphical interface.

### 2. Online Hash Extraction & Cracking (W3-PM2)
* Parsed the encrypted PDF locally using the **Networkwalks Hash Calculator** to extract a `pdf2john`/Hashcat-compatible hash string.
* Recovered the document password using the **Networkwalks Password Cracker** utility and unlocked the target file.

---

## Documentation
* **Full Lab Report:** [week3_lab_report.pdf](./week3_lab_report.pdf)
