Overview

This repository documents Week 4 Advanced Vulnerability Assessment and Penetration Testing (VAPT) activities.
It covers advanced exploitation techniques, API security testing, privilege escalation, network protocol attacks, mobile application testing, and a full capstone VAPT engagement, combining theoretical knowledge and hands-on practical labs.

All activities were performed in controlled lab environments (VulnHub, TryHackMe, HackTheBox, DVWA) strictly for educational purposes.

🧠 Learning Objectives

Understand and execute multi-stage exploit chains

Perform API security testing aligned with OWASP API Top 10

Achieve privilege escalation and persistence

Conduct network protocol attacks (MitM, SMB relay)

Analyze and exploit mobile application vulnerabilities

Deliver professional pentest reports and remediation guidance

🛠 Tools & Technologies Used

Operating System: Kali Linux

Frameworks: Metasploit Framework

Scanning & Enumeration: Nmap, Gobuster, OpenVAS

Web & API Testing: Burp Suite, Postman, sqlmap

Privilege Escalation: LinPEAS, PowerSploit

Network Attacks: Responder, Ettercap, Wireshark

Mobile Security: MobSF, Frida, Drozer

Reporting: Google Docs, PDF

📂 Repository Structure
cyart-vapt-team/
└── Week 4/
    ├── Documentation/
    │   ├── Pdf/
    │   ├── Screenshots/
    └── README.md

🧪 Practical Labs Summary
1️⃣ Advanced Exploitation Lab

Target: VulnHub VM (Mr. Robot / Metasploitable 2)

Techniques: Exploit chaining, RCE, Meterpreter access

Example Exploit: WebDAV File Upload → RCE

Outcome: Remote shell and privilege escalation

2️⃣ API Security Testing Lab

Target: DVWA API

Standards: OWASP API Top 10 (2023)

Findings:

Broken Object Level Authorization (BOLA)

Injection vulnerabilities

Tools: Burp Suite, Postman, sqlmap

3️⃣ Privilege Escalation & Persistence

Enumeration: LinPEAS

Techniques: SUID exploitation, kernel misconfigurations

Persistence: Cron job backdoor

Result: Root shell obtained

4️⃣ Network Protocol Attacks

Attacks: SMB Relay, ARP Spoofing

Tools: Responder, Ettercap, Wireshark

Outcome: NTLM hash capture and traffic interception

5️⃣ Mobile Application Penetration Testing

Static Analysis: MobSF (Insecure storage)

Dynamic Testing: Frida authentication bypass

Target: Android APK

Severity: High-risk data exposure

6️⃣ Capstone Project – Full VAPT Engagement

Target: HackTheBox VM (Lame)

Exploit: VSFTPD 2.3.4 Backdoor RCE

Framework Used: PTES

Deliverables:

Executive Summary

Attack Timeline

Risk & Remediation Plan

Stakeholder Briefing

🛡 Remediation Highlights

Patch vulnerable services and plugins

Enforce least privilege

Secure API authorization checks

Disable insecure protocols (SMBv1, WebDAV)

Implement WAF, MFA, and secure coding practices

