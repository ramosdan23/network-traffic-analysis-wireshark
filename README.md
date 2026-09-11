# Network Traffic & Protocol Analysis (Wireshark & Kali Linux)

## Overview
Hands-on packet capture evaluations, protocol dissecting, and automated log parsing to detect adversarial activity, protocol anomalies, and command-and-control (C2) communication.

## Tools Used
- **Wireshark:** Frame inspection, display filters, TCP stream reassembly.
- **Nmap:** Port auditing, service version detection, network mapping.
- **Python / Bash:** Custom automation scripts to filter and extract unique external IPs.

## Analysis Artifacts
- **Malware Traffic Triage:** Reconstructing infected `.pcap` sessions to identify infected internal hosts, target C2 IP addresses, and DNS queries.
- **Port & Service Auditing:** Baselines of standard vs. abnormal port behaviors across test subnets.
- **Automation Scripts:**
  - `ip_parser.py`: Parses raw connection logs and filters unique external IPs against private CIDR blocks.
