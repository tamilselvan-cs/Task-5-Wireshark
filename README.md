# Task-5: Wireshark TCP Capture

This repository contains my packet-capture exercise for the internship **Task-5**.

## 📄 Description
I captured live network traffic on Kali Linux using **Wireshark**.  
During a 60-second capture only **TCP** packets were observed, demonstrating how most modern internet traffic (such as HTTPS) is carried over the TCP transport protocol.

## 🗂 Contents
| File/Folder | Purpose |
|-------------------|--------------------------------------------|
| `capture.pcapng` | Raw Wireshark capture file (TCP traffic) |
| `report.md` | Detailed analysis of the TCP packets |
| `screenshots/` | Screenshots of Wireshark filters and stats |

## 🔑 Key Points
- Shows **TCP three-way handshake** and encrypted HTTPS sessions.
- Useful for learning how TCP headers (source/destination ports, flags, sequence numbers) look in a real capture.

## ⚠️ Notes
- Capture contains only **test traffic** and no sensitive personal information.
- All data was generated on a controlled network for educational purposes.

---

Author:C Tamilselvan  
Date: 2025-09-29
