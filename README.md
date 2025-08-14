# Day 4 Lab: 🧮 DHCP & 🌐 DNS Setup

---

## **🛠 Tools**
- Windows 11 PC 💻
- PowerShell 🖥️
- Command Prompt 🖱️
- Wireshark 🔍
- Network Adapter: Ethernet 🌐
- DNS IP: 8.8.8.8

---

## **Part 1 – DHCP Server Setup**

- Set my Ethernet adapter to DHCP 🔄  
- Verified my IPv4, gateway, and lease times using `ipconfig /all` 📋  
- Released and renewed my IP to test lease functionality 🔁  
- Captured DHCP packets in Wireshark and confirmed Discover → Offer → Request → Ack sequence 🛰️  

---

## **Part 2 – DNS Setup (PowerShell)**

- Opened PowerShell as admin ⚡  
- Verified adapter name was Ethernet 🖥️  
- Set DNS server to 8.8.8.8 🧭  
- Confirmed the DNS configuration worked ✅  
- Tested name resolution with `nslookup lab.local` 🌐  
- Cleared DNS cache to ensure fresh queries 🧹  
- Captured DNS packets in Wireshark and observed query → response traffic 📡  

---

## **📝 Network+ Notes / What I Learned**

- DHCP automatically assigns IPs and manages leases dynamically 🏷️  
- Releasing and renewing IPs is crucial for testing DHCP behavior 🔁  
- DNS translates human-readable names into IP addresses 🌐  
- PowerShell can fully configure network settings without GUI 💻  
- Wireshark is essential for visualizing DHCP and DNS traffic 🔍  
- Always verify network adapter names and settings before changes ⚙️  

---
