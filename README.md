# BlueMoon: 2021 Penetration Testing Report

## Project Summary
This report documents the penetration testing process on the BlueMoon: 2021 machine. The objective is to simulate a full attack lifecycle including reconnaissance, enumeration, and explanation.
---
## Infrastructure & Tools

- **Target IP**: 192.168.1.120
- **Attacker OS**: Kali Linux

### Tools Used:
  - Nmap
  - Gobuster
  - Firefox
  - Wget
  - Steghide
  - Exiftool
  - Strings
---
## Phase 1: Reconnaissance & Enumeration
### 1. Host Discovery
```bash
nmap -sn 192.168.1.0/24
