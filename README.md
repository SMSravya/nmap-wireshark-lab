# Local Network Port Scanning & Packet Analysis

This project demonstrates how to perform a local network port scan using **Nmap** and validate responses using **Wireshark**.

## Tools Used

- Nmap
- Wireshark
- Kali Linux
- VMware Network Setup

## What You'll Learn

- How to identify active hosts in your network.
- How to detect open/closed ports using TCP SYN scan.
- How to analyze packet-level behavior with filters like:
  - `tcp.flags.syn == 1 && tcp.flags.ack == 0`
  - `tcp.flags.reset == 1`

## Files Included

- `report.tex` – Full LaTeX report.
- Screenshots:
  - `nmap-scan-result.png`
  - `wireshark-syn-filter.png`
  - `wireshark-rst-filter.png`

## Note

All scans were conducted in a virtual lab setup for educational purposes only.
