# Network Scanning and Enumeration using Nmap

## Overview
This project demonstrates basic network reconnaissance and service enumeration using the Nmap tool. The objective is to identify active hosts, open ports, and running services within a network.

## Tools Used
- Nmap
- Linux (Kali Linux / Ubuntu)

## Steps Performed

1. Host discovery to identify active systems in the network.
2. Port scanning to detect open ports.
3. Service enumeration to identify services running on discovered ports.
4. Analysis of scan results to understand potential security risks.

## Sample Commands

### Host Discovery
```bash
nmap -sn 192.168.1.0/24
## Step 2: Add TCP SYN Scan
Type or paste this:

```markdown
### TCP SYN Scan

```bash
nmap -sS 192.168.1.10

## Step 3: Add Service Version Detection (Optional but Recommended)
Below the TCP SYN scan section add:

```markdown
### Service Version Detection

```bash
nmap -sV 192.168.1.10
