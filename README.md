# cyart-vapt-teams
cyart-vapt-team/
│
├── Week 3/
│   ├── Documentation/pdf
│   │   ├── vaptweek03_report.pdf
│   ├── Documentation/screenshoots

## 📌 Overview
This repository documents my end-to-end learning and hands-on practice in
Vulnerability Assessment and Penetration Testing (VAPT), covering theory,
practical exploitation, reporting, and stakeholder communication.

## 🧪 Labs Covered
- Advanced Vulnerability Exploitation
- Web Application Penetration Testing (DVWA)
- Exploit Chaining (XSS → Session Hijacking → RCE)
- SQL Injection (Manual & SQLMap)
- Burp Suite Testing
- Post-Exploitation & Evidence Collection
- Full VAPT Capstone Project

## 🛠 Tools Used
- Kali Linux
- Metasploit Framework
- Nmap
- SQLMap
- Burp Suite
- OWASP ZAP
- OpenVAS
- DVWA
- Wireshark

## 📊 Methodologies
- OWASP Top 10
- OWASP WSTG
- PTES
- CVSS v3.1

## ⚠️ Disclaimer
All testing was performed in a controlled lab environment for educational purposes only.
Copy code
## Advanced Vulnerability Exploitation

### Exploit Chains
Exploit chaining involves combining multiple vulnerabilities to achieve a
larger impact. For example, a reflected XSS vulnerability can be used to steal
session cookies, which are then leveraged to gain administrative access and
execute remote commands.

### Exploit Customization
Public exploits often require modification to work in specific environments.
This includes adjusting payloads, IP addresses, ports, and request headers.

### Obfuscation Techniques
Encoding, polymorphism, and payload transformation are used to bypass
basic security mechanisms such as WAFs and input filters.
markdown
Copy code
| Exploit ID | Description       | Target IP       | Status  | Payload       |
|-----------|-------------------|----------------|---------|---------------|
| 004       | XSS → RCE Chain   | 192.168.1.106  | Success | Meterpreter   |
markdown
Copy code
A web application security assessment was conducted on DVWA. Critical SQL
Injection and reflected XSS vulnerabilities were identified using manual
testing and automated tools. These vulnerabilities allow authentication
bypass, data extraction, and client-side script execution.
