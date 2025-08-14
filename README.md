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

### Set my Ethernet adapter to DHCP 🔄
  
<img width="965" height="479" alt="D9OIDkL" src="https://github.com/user-attachments/assets/06342606-c7e9-4d57-b925-95e0df49ee0f" />

---

<img width="651" height="224" alt="YOTSl2n" src="https://github.com/user-attachments/assets/e71e9504-65d8-4444-957f-432e82a670e8" />

### Verified my IPv4, gateway, and lease times using `ipconfig /all` 📋

<img width="513" height="125" alt="jdkHyHb" src="https://github.com/user-attachments/assets/3c31b4b4-6aeb-43f2-8e63-fdf6448e8a9e" />

---

<img width="738" height="244" alt="IXmlVuE" src="https://github.com/user-attachments/assets/471b20f0-aab8-40bb-afe8-15485244a5a1" />

---

## **Part 2 – DNS Setup (PowerShell)**

### Opened PowerShell as admin ⚡  
### Verified adapter name was Ethernet 🖥️

<img width="492" height="209" alt="KuGqICg" src="https://github.com/user-attachments/assets/638df4ab-5125-4889-9427-8201c1d90c25" />
  
### Set DNS server to 8.8.8.8 🧭

<img width="837" height="185" alt="7fYc1FT" src="https://github.com/user-attachments/assets/5cd068d4-2655-4c5f-9bb2-6a252f0fc16a" />

### Confirmed the DNS configuration worked ✅

<img width="672" height="65" alt="L2PIunP" src="https://github.com/user-attachments/assets/4dfa3456-40e3-4ed7-9b9c-2ab9e3664ecb" />

### Tested name resolution with `nslookup lab.local` 🌐

<img width="672" height="65" alt="L2PIunP" src="https://github.com/user-attachments/assets/6bc91250-3795-4f6f-b877-f2646b83e2e8" />

### Captured DNS packets in Wireshark and observed query → response traffic 📡

<img width="914" height="125" alt="3PD9SWh" src="https://github.com/user-attachments/assets/bc2d6040-19bb-4274-9e56-e39f06fddf2d" />

---

## **📝 Network+ Notes / What I Learned**

- DHCP automatically assigns IPs and manages leases dynamically 🏷️  
- Releasing and renewing IPs is crucial for testing DHCP behavior 🔁  
- DNS translates human-readable names into IP addresses 🌐  
- PowerShell can fully configure network settings without GUI 💻  
- Wireshark is essential for visualizing DHCP and DNS traffic 🔍  
- Always verify network adapter names and settings before changes ⚙️  

---
