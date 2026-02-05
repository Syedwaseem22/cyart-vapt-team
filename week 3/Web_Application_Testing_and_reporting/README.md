# Web Application Testing and Reporting

## Overview
This lab focuses on identifying and exploiting common web application vulnerabilities based on the OWASP Top 10. Testing was performed on the Damn Vulnerable Web Application (DVWA) in a controlled lab environment.

## Target Details
- Application: DVWA
- Target IP: 192.168.43.131
- Security Level: Low

## Tools Used
- Burp Suite (Community Edition)
- sqlmap
- OWASP ZAP

## Vulnerabilities Identified
- SQL Injection (Critical)
- Reflected Cross-Site Scripting (Medium)
- Stored Cross-Site Scripting (High)
- Weak session management
- Missing security headers

## Testing Activities
- Manual SQL injection payloads
- Automated SQL injection using sqlmap
- Session interception and manipulation via Burp Suite
- Passive and active scanning with OWASP ZAP

## Reporting
- Executive summary
- Technical findings
- CVSS-based risk assessment
- Remediation recommendations
- Non-technical management briefing

## Outcome
The lab demonstrates how insecure input handling and weak authentication mechanisms can lead to data compromise and unauthorized access.

⚠️ Intended for educational and defensive learning purposes only.
