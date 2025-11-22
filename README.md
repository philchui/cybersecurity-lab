# Cybersecurity Lab

This repository contains my hands-on cybersecurity home lab used to learn and demonstrate skills in networking, Windows and Linux administration, security monitoring, SIEM, detection engineering, and incident response.

The goal of this lab is to build real technical ability while creating a portfolio that clearly shows practical, hire-ready cybersecurity skills.

---

## Lab Overview

This lab simulates a small enterprise environment, including:

- Windows Server (Active Directory Domain Controller)
- Windows 10/11 workstation
- Ubuntu Linux server (logging, SSH, syslog)
- Attack simulations (bruteforce, phishing, malware)
- Wireshark packet captures & analysis
- Splunk / Graylog SIEM pipelines
- Centralized log collection and detection rules

Architecture diagram:  
**[`diagrams/home-lab-overview.png`](diagrams/home-lab-overview.png)**

---

## Repository Structure

### **`diagrams/`**
High-level visual documentation of the lab.
- `home-lab-overview.png`
- `network-topology.png`
- `windows-domain.png`

---

### **`notes/`**
Structured learning notes from building the lab and studying Security+ concepts.
- `windows.md`
- `linux.md`
- `networking.md`
- `wireshark.md`
- `splunk-siem.md`
- `incident-response.md`

---

### **`windows-lab/`**
Windows Server + Windows workstation configuration, automation, and hardening.
- `scripts/` — PowerShell scripts (process exports, service exports)
- `configs/` — DSC configurations, GPO baselines
- `reports/` — Hardening checklists, audit notes

---

### **`linux-lab/`**
Linux hardening, logging, and security configurations.
- `scripts/` — Syslog setup, Fail2ban installation
- `configs/` — SSH configuration, rsyslog config
- `reports/` — Hardening and audit document
