# Nmap Enumeration Lab
Network scanning and enumeration using Nmap in a controlled TryHackMe lab environment.
---

## 📌 Objective
The goal of this lab was to perform network enumeration using Nmap to identify open ports and services on a target machine.
---

## 🛠 Tools Used
- Nmap  
- TryHackMe AttackBox  
---

## 🌐 Target Environment
The target IP address (10.66.155.228) was provided by the TryHackMe lab environment. The machine was hosted in a controlled virtual network designed for practicing network enumeration and security analysis.
---

## 🔍 Scanning Techniques
### TCP Connect Scan (-sT)
Used to perform a full TCP connection scan by completing the three-way handshake.

### SYN Scan (-sS)
Used to perform a stealthier scan by sending SYN packets without completing the full connection.
---

## ⚡ Commands Used
```bash
nmap -sT 10.66.155.228
nmap -sS 10.66.155.228
