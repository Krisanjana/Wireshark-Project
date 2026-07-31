# Wireshark-Project

## Detecting and Investigating Network Port Scanning (Reconnaissance Attack)

# Introduction

In this project, I use Wireshark to detect and investigate a network port scan — one of the earliest stages of a cyberattack known as reconnaissance. Attackers use port scanning to discover open ports and running services on a target machine before launching a real attack. Identifying this behavior early is critical for network defense.

# Skills Learned

- Network Reconnaissance Detection
- TCP/IP Traffic Analysis
- Port Scan Pattern Recognition (SYN Scan, NULL Scan, XMAS Scan)
- IP Geolocation & Threat Intelligence Lookup
- Writing Incident Reports

# Pre-requisites

- Basic understanding of TCP/IP and networking concepts
- Wireshark installed in a safe environment (VMware, VirtualBox, Kali Linux)
- Sample PCAP file downloaded from: https://www.malware-traffic-analysis.net/ or https://www.pcapr.net/

# Lab Setup and Tools

Wireshark: Download and install from https://www.wireshark.org/download.html

VirusTotal: https://www.virustotal.com — for IP reputation lookup

AbuseIPDB: https://www.abuseipdb.com — to check if the scanning IP is blacklisted

Sample PCAP File: A capture file containing port scan traffic for analysis
