# Interception and Analysis; Simulating Real-World Atrtacks in a Controlled Network

## Overview

This project demonstrates how to use Kali Linux and Windows 10 virtual machines (VMs) to simulate and investigate real-world network attacks (ARP spoofing, MITM, and packet sniffing). It examines the posibility of capturing private data in unencrypted settings, inclduing usernames, passwords, and GET/POST queries.

## ⚙️ Lab Setup

- **VirtualBox** with the Host-Only Adapter configuration
- **Attacker**: Kali Linux Virtual Machine
- **Victim**: Windows 10 Virtual Machine
## IPs used:
- **Kali**: 192.168.56.102
- **Windows**: 192.168.56.101   

## 🔧 Tools Used

- Wireshark
- Arpspoof
- Python HTTP Server
- FileZilla FTP Server

## 🔍 Attack Simulations

- HTTP sniffing via GET/POST
- FTP credential capture in plaintext
- ARP Spoofing -> MITM
- Interception via fake login form

## 📸 Screenshots

Images are located in [Images](images). Examples include:

- VM setup 
- Wireshark traffic capture 
- Spoofed ARP packets
- Captured credentials

## 📄 Full Report

You can download and view the full project documentation here:
[📄 Network Sniffing Report](./Network_Sniffing_Report.pdf)




## 🛡️ Takeaways****

- Always encrpyt sensitive traffic (HTTPS, SFTP)
- Monitor for unusual ARP activity
- Use tools like Wireshark for deep traffic inspection

## Key Learnings
- Learned how ARP spoofing operates on a local network
- Utilised Wireshakr to record and analyse actual HTTP/FTPM packets
- Investigated how unencrypted passwords can be intercepted during MITM attacks
- Acquired practical knowledge of Kali Linux and common offensive tools
