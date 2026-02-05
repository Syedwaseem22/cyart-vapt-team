# Capstone Project – Full VAPT Cycle

## Overview
This capstone project simulates a complete Vulnerability Assessment and Penetration Testing (VAPT) engagement following the PTES methodology. The assessment was performed on a VulnHub Kioptrix Level 1 virtual machine in a controlled lab environment.

## Scope
- Target VM: Kioptrix Level 1
- Attacker: Kali Linux
- Target IP: 192.168.43.133

## Methodology
- Reconnaissance
- Scanning and Enumeration
- Vulnerability Identification
- Exploitation
- Post-Exploitation
- Reporting

## Tools Used
- Nmap
- OpenVAS
- Metasploit Framework
- OpenFuck (manual exploit)
- TryHackMe learning resources

## Key Findings
- Samba trans2open buffer overflow (CVE-2003-0201)
- Apache mod_ssl buffer overflow (CVE-2002-0082)
- Outdated services enabling root-level access

## Results
- Successful root compromise via Metasploit and manual exploitation
- Validation of vulnerabilities using OpenVAS
- Remediation steps simulated and verified through rescanning

## Conclusion
This project demonstrates the risks of legacy systems and the importance of timely patching, service hardening, and continuous security testing.

⚠️ Conducted strictly for academic and learning purposes.
