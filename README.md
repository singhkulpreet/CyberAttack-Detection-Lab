# Cybersecurity Detection Lab

## 🎯 Objective
This project simulates real-world adversary techniques (mapped to MITRE ATT&CK) using **Kali Linux (Attacker)**, **Windows (Victim)**, **QRadar CE (SIEM)**, and **Wireshark (Traffic Analysis)**.  
It demonstrates how SOC analysts can detect and respond to cyberattacks.

## 🏗️ Lab Setup
- Kali Linux VM (192.168.25.200, vmnet8)
- QRadar CE VM (192.168.25.100, vmnet8)
- Windows Host (192.168.25.1, vmnet8)
- Tools: WinCollect, Wireshark, Hydra, Nmap

## ⚔️ Simulated Attacks
- **T1046 – Network Service Scanning**: Nmap scan
- **T1110 – Brute Force**: Hydra against RDP
- **T1078 – Valid Accounts**: Successful login with compromised credentials

## 📊 Detection
- Logs collected via WinCollect (Windows) and rsyslog (Kali).
- Custom QRadar rules triggered offenses and added attacker IP to a blacklist.
- Wireshark verified attack traffic.

## 📸 Screenshots
See `/qradar_rules_screens` and `/wireshark_captures`.

## 📚 Documentation
- [Full Project Report (DOCX)](Cybersecurity_Detection_Lab_Project.docx)
- [Setup Instructions](setup_instructions.md)
- [Attack Simulations](attack_simulations.md)
- [QRadar Rules](qradar_rules.md)

---
⭐ If you like this project, feel free to fork or use it for learning.
