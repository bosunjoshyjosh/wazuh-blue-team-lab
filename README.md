# 🛡️ Wazuh Blue Team Lab

This repository documents my personal Blue Team cybersecurity lab using **Wazuh** for threat detection, log analysis, and SIEM experimentation. Built using virtual machines, this lab simulates real-world attack scenarios and defensive response workflows.

> **Updated:** August 08, 2025

---

## 🔧 Lab Stack

- **Wazuh 4.12**
- **Ubuntu 24.04** (Wazuh Manager)
- **Windows 10** (Wazuh Agent)
- **Kali Linux** (Attacker)
- **VirtualBox** (Host-only networking)

---

## 📊 Key Features

- SSH brute force detection  
- Custom Wazuh detection rules  
- Simulated attacks using Kali Linux  
- Automated alert generation  
- Log monitoring (e.g., `auth.log`, Sysmon)  
- PDF incident reports  

---

## 📁 Project Structure

| Folder         | Description                          |
|----------------|--------------------------------------|
| `lab-notes/`   | Step-by-step configuration and setup |
| `screenshots/` | Wazuh dashboard alert captures       |
| `alerts/`      | JSON/raw alert exports               |
| `reports/`     | Incident write-ups and summaries     |

---

## 🚧 In Progress

- [ ] Port scanning detection  
- [ ] Slack/Email alert integration  
- [ ] Wazuh + OSQuery integration  
- [ ] MITRE ATT&CK tag mapping  

---

## 💡 Purpose

This lab helps me practice and demonstrate real-world Blue Team skills such as:

- Threat detection and analysis
- Incident response workflows
- Log correlation using Wazuh SIEM
- Writing custom detection rules

---

## 📎 Related Skills

- SIEM operations  
- Log parsing and analysis  
- Detection engineering  
- Security monitoring  
- Home lab building  
- Report writing (PDFs)

---

## 📜 License

MIT License — feel free to use and adapt.

