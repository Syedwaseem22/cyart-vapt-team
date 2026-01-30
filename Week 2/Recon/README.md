# Reconnaissance Practice

## Objective
To perform Open-Source Intelligence (OSINT) and identify exposed assets related to a target.

## Tools Used
- Shodan
- Maltego
- Sublist3r
- Wappalyzer

---

## Reconnaissance Activities

### 1. Domain & Asset Discovery
- WHOIS lookup performed
- IP address and domain ownership analyzed

### 2. Subdomain Enumeration
Tool:
- Sublist3r

Purpose:
- Identify development and test subdomains

### 3. Technology Stack Identification
Tool:
- Wappalyzer

Detected technologies:
- Apache Web Server
- PHP

---

## Asset Mapping Log

Timestamp | Tool | Finding
--------- | ---- | -------
2025-08-18 10:00:00 | Shodan | Exposed SSH service on port 22
2025-08-18 10:30:00 | Maltego | Subdomain discovered: dev.example.com

---

## Recon Summary (50 Words)
Reconnaissance activities revealed exposed services and development subdomains that increase the target’s attack surface. Publicly accessible SSH and outdated technologies were identified, highlighting the need for asset inventory review and perimeter hardening before exploitation attempts.
