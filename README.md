# Network-Scanning-Nmap-Project
Hands-on project using Nmap to identify live hosts, open ports, and services in a network — part of my cybersecurity networking internship preparation.
# Project 1: Network Scanning with Nmap

This project demonstrates my ability to perform basic to advanced network scans using **Nmap**, a powerful open-source network discovery and security auditing tool. It was completed as part of my self-learning journey in **Cybersecurity Networking**.

---

## Objective
To identify live hosts, open ports, and services running in a subnet using Nmap.

---

## Tools Used
- **Nmap**
- **Command Prompt (Windows)**
- **Kali Linux Terminal (optional)**

---

## Steps Performed
1. **Ping Scan**  
   To identify live hosts:
   nmap -sn 192.168.1.0/24

   
2. **Port & Service Scan**  
   To check open ports and services:
   nmap -sV 192.168.1.1-20

   
3. **Aggressive Scan**  
   To detect OS, traceroute, and version info:
   nmap -A 192.168.X.X
   
---

## Screenshots
_Sensitive data such as IP addresses and hostnames have been blurred for safety._

---

## Report
A detailed report with findings and explanations including screenshots is uploaded.  

---

## What I Learned
- How to identify live hosts on a subnet
- How to enumerate services and detect open ports
- Importance of masking sensitive data in public reports
- Hands-on experience with command-line scanning

---

## Status
✅ Completed  



