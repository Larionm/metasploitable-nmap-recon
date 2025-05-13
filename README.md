# metasploitable-nmap-recon
Nmap scan results and analysis of Metasploitable 2 vulnerable VM
# 🔍 Metasploitable 2 Nmap Recon Project

## 📌 Project Overview
This project demonstrates a real-world Nmap scan conducted against the intentionally vulnerable Metasploitable 2 virtual machine. The goal was to enumerate open ports, detect running services, and gather OS-level details — key tasks for any SOC analyst during initial reconnaissance and threat hunting.

## 🛠 Tools Used
- **Kali Linux** (Attacker VM)
- **Metasploitable 2** (Target VM)
- **Nmap 7.95**

## 📡 Scan Details
The scan was executed using the following command:

```bash
nmap -T4 -F -sV -Pn 192.168.56.101 -oN metasploitable-scan.txt
## 📈 Next Steps

This project represents the reconnaissance phase of a simulated SOC investigation. Building on this, the following steps are planned:

- Analyze logs from vulnerable services (e.g., Telnet, FTP, MySQL) using tools like **Splunk** or **Security Onion**
- Simulate alert triage based on exposed services identified in the scan
- Create detection rules for suspicious network activity (e.g., port scanning, brute-force attempts)
- Explore open-source threat intelligence tools like **AlienVault OTX** and **AbuseIPDB**
- Begin documenting a playbook for vulnerability triage and response

These next steps will help bridge the gap between scanning and real-world SOC analyst workflows, demonstrating practical, hands-on knowledge of threat detection and response.
