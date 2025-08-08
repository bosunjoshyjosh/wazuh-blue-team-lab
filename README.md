# 🛡️ Wazuh Blue Team Lab

**Detection Lab Using Wazuh SIEM, Ubuntu, Windows 10, and Kali Linux**

This repository contains my home cybersecurity lab setup focused on Blue Team operations. It uses **Wazuh** as the central SIEM to detect and respond to simulated attacks across multiple virtual machines. The lab emulates real-world security scenarios, alerting workflows, and defensive techniques.

---

## 🔧 Lab Stack

- **Wazuh 4.12**
- **Ubuntu 24.04** (Wazuh Manager)
- **Windows 10** (Agent)
- **Kali Linux** (Attacker)
- **VirtualBox** + **Host-only networking**

---

## 📊 Key Features

- SSH brute force detection  
- Custom Wazuh rules  
- Simulated attacks using Kali  
- Automated alert generation  
- Log monitoring (`auth.log`, `sysmon`)  
- PDF incident reports  

---

## 📁 Structure

| Folder         | Description                          |
|----------------|--------------------------------------|
| `lab-notes/`   | Step-by-step configurations          |
| `screenshots/` | Wazuh dashboard alert captures       |
| `alerts/`      | JSON/raw alert exports               |
| `reports/`     | Incident write-ups and summaries     |

---

## 📌 In Progress

- [ ] Port scanning detection  
- [ ] Slack/Email alert integration  
- [ ] Wazuh + OSQuery integration
# wazuh-blue-team-lab
Detection Lab Using  Wazuh SIEM, Ubuntu, Window 10, Kali Linux
