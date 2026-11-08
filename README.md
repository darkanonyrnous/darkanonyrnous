# Anonyrnous

> Penetration Tester · Security Researcher · Tool Developer

---

## About

Focused on web application security, network security, and offensive tool development. Built two Python security tools covering recon, web vulnerability scanning and reporting. TryHackMe Top 2% · 93+ PicoCTF challenges solved.

---

## Skills

**Web Application Security**
SQLi · XSS · IDOR · LFI/RFI · SSRF · SSTI · RCE · Command Injection · XXE · CORS · JWT attacks · OAuth · Upload Bypass · Race Conditions · DOM-Based · OWASP API Top 10 · Business Logic

**Network Security**
Nmap · passive/active recon · port scanning · protocol attacks (FTP · SMTP · POP3 · IMAP) · VHost enumeration · DNS brute force · Wireshark · tcpdump

**Exploitation**
Metasploit · msfvenom · Meterpreter · searchsploit · manual CVE exploitation · web shells · reverse/bind shells · shell stabilization

**Privilege Escalation**
Linux — sudo · SUID · cron · PATH hijack · kernel exploits · LinPEAS · GTFOBins
Windows — token impersonation · AlwaysInstallElevated · DLL hijack · WinPEAS · PrintSpoofer · JuicyPotato

**Reconnaissance & OSINT**
Gobuster · ffuf · Subfinder · Amass · Shodan · Google Dorks · crt.sh · WHOIS · dig · Dirb · enum4linux · smbclient

**Binary & Reverse Engineering**
Ghidra · gdb · pwntools · heap overflow · format string · PIE/ASLR bypass · XOR · hash cracking · steganography · file carving

**Tools**
Burp Suite (Proxy · Repeater · Intruder · Turbo Intruder · JWT Editor · Autorize) · Hydra · Nikto · sqlmap · john · hashcat · CyberChef · binwalk · exiftool

---

## Projects

### [RedReaper](https://github.com/darkanonyrnous/redreaper)
Automated recon and web vulnerability scanner in a single Python file, with an HTML report.

- **Recon:** port scan · subdomain enumeration · sensitive path / URL discovery
- **Vulnerability checks:** SQLi · XSS · LFI · SSRF · Command Injection · Open Redirect · known-CVE paths
- **Report:** CVSS v3.1 · CWE mapping · HTML output

```bash
python3 redreaper.py -u https://target.com --full -o results
```

---

### [PenTool v2.0](https://github.com/darkanonyrnous/pentool)
Web penetration testing and OSINT framework with a modular Python architecture.

- **OSINT:** DNS · WHOIS · subdomain enum · crt.sh · port scan · email harvest · tech fingerprint · SPF/DMARC audit
- **Web Scanner:** SQLi (Error/Union/Blind/Time-based) · XSS (context-aware) · LFI · SSRF · SSTI · IDOR · CORS · security headers · cookie flags
- **Report:** Dark-theme HTML + TXT · CVSS v3.1 · executive summary · risk matrix

```bash
python3 pentool.py full -d example.com -o report --client ACME --tester darkanonyrnous
```

---

### [PicoCTF Writeups — 93+ Challenges](https://github.com/darkanonyrnous/cylab-picoctf-writeups)
Step-by-step solutions across all CTF categories.

Web Exploitation · Cryptography · Forensics · Reverse Engineering · Binary Exploitation · General Skills

Topics: SQLi · XSS · JWT · heap overflow · format string · PIE bypass · RSA · steganography · git forensics · hash cracking

---

### Reference Notes

| Repo | Content |
|---|---|
| [Web Hacking Notes](https://github.com/darkanonyrnous/web-hacking-notes) | IDOR · LFI · SSRF · XSS · SQLi · Race Conditions · DOM-Based |
| [Web Fundamentals Notes](https://github.com/darkanonyrnous/web-fundamentals-notes) | DNS · HTTP · OWASP API Top 10 · Upload Vulns · CVE-2025-29927 |
| [Burp Suite Notes](https://github.com/darkanonyrnous/burp-suite-notes) | Proxy · Repeater · Intruder · Turbo Intruder · JWT Editor · Autorize |
| [Network Security Notes](https://github.com/darkanonyrnous/network-security-notes) | Nmap · FTP · SMTP · POP3 · IMAP · Hydra · tcpdump |
| [Privilege Escalation Notes](https://github.com/darkanonyrnous/privilege-escalation-notes) | Linux/Windows PrivEsc — full methodology |
| [Metasploit Notes](https://github.com/darkanonyrnous/metasploit-notes) | msfconsole · exploitation · Meterpreter · post-exploitation |
| [Vulnerability Research Notes](https://github.com/darkanonyrnous/vulnerability-research-notes) | CVE · CVSS · NVD · Exploit-DB · manual exploits |

---

## Certifications & Training

| | |
|---|---|
| TryHackMe — Jr Penetration Tester | In Progress |
| HackTheBox Academy — CPTS | In Progress |
| TryHackMe — Cyber Security 101 | ✅ |
| TryHackMe — Pre Security | ✅ |
| CyLab Security Academy — 93+ challenges | ✅ |
| Commonwealth Bank · Datacom · TCS · Deloitte · AIG · Mastercard | ✅ Forage simulations |

---

## Platforms

[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top_2%25-red?style=flat&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/anonyrnous)
[![HackTheBox](https://img.shields.io/badge/HackTheBox_Academy-CPTS-9FEF00?style=flat&logo=hackthebox&logoColor=black)](https://academy.hackthebox.com)
[![PicoCTF](https://img.shields.io/badge/PicoCTF-93+_solved-blue?style=flat)](https://play.picoctf.org/users/anonyrnous)
