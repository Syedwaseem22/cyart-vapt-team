# Privilege Escalation and Persistence Lab

## Practical Application
This lab focuses on elevating privileges after initial compromise and maintaining long-term access.

---

## Objectives
- Perform system enumeration.
- Identify privilege escalation paths.
- Achieve administrative/root access.
- Establish persistence safely.

---

## Tools Used
- Meterpreter
- LinPEAS
- PowerSploit

---

## Activity Log

| Task ID | Technique     | Target IP     | Status  | Outcome    |
|--------:|--------------|---------------|---------|-----------|
| 010     | SUID Exploit | 192.168.43.131 | Success | Root Shell |

---

## Escalation Method

LinPEAS identified misconfigured SUID binaries. Exploitation allowed execution with elevated privileges, granting full system control.

---

## Persistence Summary 

A cron-based persistence mechanism was deployed to trigger a reverse shell at regular intervals. Access remained available after user logout and service restarts. Defensive recommendations include monitoring scheduled tasks, auditing privileged files, and implementing integrity verification.

---

## Checklist
- Run LinPEAS  
- Search for SUID / sudo misconfigs  
- Review kernel exploits  
- Establish persistence  
- Document artifacts  

---

## Skills Demonstrated
- Post-exploitation enumeration
- Linux privilege escalation
- Persistence mechanisms
- Blue-team awareness

---

## Author
Syed Waseem

