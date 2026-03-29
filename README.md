# 🏭 ICS Security Testbed - Final Year Project

**By Talha Younas (CSEC221102004)**  
**Supervisor:** Mr. Mazhar Ali Shahid  
**Khwaja Fareed University of Engineering & IT, Rahim Yar Khan**

---

## 📌 About This Project

This is my **Final Year Project** for Bachelor of Science in Cyber Security.

**Title:** Design, Implementation, and Penetration Testing of a Vulnerable Industrial Control System (ICS) Testbed with MITRE ATT&CK Mapping

---

## ✨ My Contributions (Original Work)

| # | Contribution | Description |
|---|--------------|-------------|
| 1 | **Custom Attack Scripts** | Wrote 3 Python scripts for Modbus injection, DoS, and reconnaissance |
| 2 | **MITRE ATT&CK Mapping** | Mapped all 7 attack techniques to MITRE ATT&CK for ICS framework |
| 3 | **Network Traffic Analysis** | Captured and analyzed pcap files using Wireshark |
| 4 | **SQLite Database Logging** | Created logging system for attack documentation |
| 5 | **Comprehensive Documentation** | Full FYP report with methodology and findings |

---

## 🚀 Attacks Performed

| Attack | MITRE ID | Impact |
|--------|----------|--------|
| Modbus Command Injection | T0836 | Changed tank level 45% → 100% |
| Network Scanning | T0842 | Discovered all ICS components |
| ARP Spoofing (MITM) | T0886 | Intercepted Modbus traffic |
| SSH Brute Force | T0842 | Gained unauthorized access |
| DoS on PLC | T0814 | PLC became unresponsive |
| Firmware Manipulation | T0800 | Altered PLC logic |
| Data Destruction | T0885 | Corrupted process values |

---

## 📁 My Custom Files

