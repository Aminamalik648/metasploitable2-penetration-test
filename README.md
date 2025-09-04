# metasploitable2-penetration-test
# Metasploitable2 Penetration Testing Lab

## Overview
This project documents a penetration testing exercise performed on the **Metasploitable2 vulnerable machine** using **Kali Linux**.  
The goal of this lab was to scan, identify, and exploit known vulnerabilities for educational purposes.

## Objectives
- Perform Nmap scanning to discover open ports and services.
- Exploit three vulnerabilities to gain access:
  1. **vsftpd 2.3.4 Backdoor (FTP – Port 21)**
  2. **Samba smbd Usermap Script Command Execution (Ports 139 & 445)**
  3. **UnrealIRCd 3.2.8.1 Backdoor (Port 6667)**

## Tools Used
- **Nmap** – for network scanning and service enumeration.
- **Metasploit Framework** – for exploiting identified vulnerabilities.
- **Kali Linux** – attacker machine.
- **Metasploitable2** – target machine.

## Report Contents
- **Nmap Scan Results**
- Detailed steps of each exploitation
- Placeholder sections for screenshots
- Findings and recommendations for patching

## Legal Disclaimer
This project was conducted in a **legal, isolated lab environment** using Metasploitable2 — a purposefully vulnerable machine created for penetration testing practice.  
**Do not attempt these techniques on unauthorized systems.**

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/metasploitable2-penetration-test.git

