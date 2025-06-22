# 🛡️ Packet Sniffing Tool

A lightweight, Python-based packet sniffer for educational and cybersecurity learning purposes. This tool captures raw packets from the network interface and displays basic information such as source/destination MAC addresses and protocol type.

---

## ⚙️ Features

- Captures raw network packets at Layer 2 (Ethernet)
- Displays:
  - Source MAC Address
  - Destination MAC Address
  - Protocol type
- CLI-based and easy to extend
- Minimal dependencies — runs on native Python socket module

---

## 📁 Project Structure

PRODIGY_CS_05/
├── Packet_Sniffing_Tool.py
├── README.md
└── LICENSE

---

## 🐍 Requirements

- Python 3.x
- Kali Linux or any Linux distro that supports raw sockets (AF_PACKET)

> ❗ No external libraries needed (e.g., Scapy not required)

---

## 💻 Used In

This tool is designed to be used in:

- **Kali Linux** (recommended)
- **Ubuntu / Debian-based distros**
- Any **Linux** OS that supports raw socket operations (Layer 2)

> ⚠️ **Not compatible with Windows** due to lack of `AF_PACKET` socket support.

---

## 🚀 How to Run (Kali Linux)

### 🔧 1. Clone the repository

```bash
git clone https://github.com/arisha1003/PRODIGY_CS_05.git
cd PRODIGY_CS_05
```
🔒 2. Run the tool with root permissions

```bash
sudo python3 Packet_Sniffing_Tool.py
```
You should see:
```bash
🔍 Packet Sniffer Started... Press Ctrl+C to stop.
[+] Packet: Source MAC: ... → Dest MAC: ... | Protocol: ...
```
To stop the sniffer, press Ctrl+C.

---
📚 What You Learn
. How to use Python's socket library for low-level network access

. Understanding of MAC addresses and Ethernet frames

. Basics of packet analysis in a Linux environment

---
⚠️ Disclaimer
This tool is created strictly for educational and ethical purposes. Use it only in lab environments or on networks you have explicit permission to monitor.
---
