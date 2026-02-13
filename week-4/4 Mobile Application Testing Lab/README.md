# Mobile Application Testing Lab

## Practical Application
This lab covers static and dynamic analysis of Android applications.

---

## Objectives
- Identify insecure data storage.
- Reverse engineer application logic.
- Bypass authentication controls.
- Document risk and remediation.

---

## Tools Used
- MobSF
- Frida
- Drozer

---

## Static Analysis Log

| Test ID | Vulnerability     | Severity | Target App |
|--------:|------------------|----------|-----------|
| 016     | Insecure Storage | High     | test.apk  |

---

## Dynamic Testing Summary (50 words)

Frida hooks intercepted authentication routines at runtime, enabling bypass of credential validation. Sensitive functions were invoked directly without proper authorization checks. Developers should implement server-side validation, certificate pinning, and anti-tampering protections.

---

## Checklist
- Run MobSF  
- Inspect permissions  
- Hook functions with Frida  
- Test IPC exposure  
- Validate encryption usage  

---

## Skills Demonstrated
- Reverse engineering
- Runtime manipulation
- Mobile threat modeling
- Secure coding awareness

---

## Author
Syed Waseem
