# Anonyrnous

**Penetration Tester · Security Researcher · Tool Developer**

[![TryHackMe](https://img.shields.io/badge/TryHackMe-TokuMei_Top_1%25-red?style=flat&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/TokuMei)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-tokumei-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/tokumei)
[![HackTheBox](https://img.shields.io/badge/HackTheBox_Academy-CPTS-9FEF00?style=flat&logo=hackthebox&logoColor=black)](https://academy.hackthebox.com)
[![PicoCTF](https://img.shields.io/badge/PicoCTF-93+_solved-blue?style=flat)](https://play.picoctf.org/users/tokurnei)

8 TryHackMe paths completed · Ruby league · 161-day streak

---

## About

Focused on web application security, network security, and offensive tool development. Built two Python security tools covering recon, web vulnerability scanning and reporting.

**TryHackMe Top 1%** (`TokuMei`) · **CRTA** · **CRT-COI** · **CNSP** · **SOC Level 1** · **Jr Penetration Tester** · **93+ PicoCTF challenges solved**

---

## Certifications

| Certification | Issuer | Issued | Credential |
|---|---|---|---|
| **Certified Red Team Analyst (CRTA)** | CyberWarFare Labs | Nov 2026 | `CRTA-6af2e6dc206a82a158444300` |
| **Certified Red Team — CredOps Infiltrator (CRT-COI)** | CyberWarFare Labs | Nov 2026 | `6aebf56cf88c7cc4d40c6435` |
| **Certified Network Security Practitioner (CNSP)** | The SecOps Group | Nov 2026 | `12141985` |
| **SOC Level 1** | TryHackMe | Nov 2026 | [THM-WNH8LKEEGM](https://tryhackme.com/certificate/THM-WNH8LKEEGM) |
| **Jr Penetration Tester** | TryHackMe | Oct 2026 | [THM-CNNJDIGA1V](https://tryhackme.com/certificate/THM-CNNJDIGA1V) |
| **NSE 3 — Network Security Associate** | Fortinet | Nov 2026 | `2794984766MU` |
| **Web Fundamentals** | TryHackMe | May 2026 | [THM-L3PUJJNMPI](https://tryhackme.com/certificate/THM-L3PUJJNMPI) |
| **Cyber Security 101** | TryHackMe | Apr 2026 | [THM-PZIXIUJ8NJ](https://tryhackme.com/certificate/THM-PZIXIUJ8NJ) |
| **Pre Security** | TryHackMe | Feb 2026 | [THM-LOC4FOG62B](https://tryhackme.com/certificate/THM-LOC4FOG62B) |

All credentials are also listed on [LinkedIn](https://linkedin.com/in/tokumei/details/certifications/).

## Training & Simulations

- 🎓 **HackTheBox Academy** — CPTS *(in progress)*
- ✅ **TryHackMe** — CompTIA Pentest+ path
- ✅ **CyLab Security Academy** — 93+ PicoCTF challenges
- ✅ **Forage job simulations** — Commonwealth Bank, Datacom, TCS, Deloitte, AIG, Mastercard

---

## Skills

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=flat&logo=kalilinux&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=flat&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat&logo=metasploit&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white)

**Web Application Security**  
SQLi · XSS · IDOR · SSRF · LFI/RFI · SSTI · JWT · OAuth · Race Conditions · OWASP API Top 10

**Network & Recon**  
Nmap · Wireshark · Gobuster · ffuf · Subfinder · Amass · Shodan · Google Dorks

**Exploitation**  
Metasploit · msfvenom · Meterpreter · reverse shells · manual CVE exploitation

**Privilege Escalation**  
Linux — sudo · SUID · cron · LinPEAS · GTFOBins  
Windows — token impersonation · AlwaysInstallElevated · WinPEAS

**Red Team & Blue Team**  
DPAPI & Credential Manager · LSASS memory analysis · SOC analysis

**Reverse & Binary**  
Ghidra · gdb · pwntools · heap overflow · format string

**Tools**  
Burp Suite · sqlmap · Hydra · John · Hashcat · CyberChef · binwalk · exiftool

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

### [PenTool v2.0](https://github.com/darkanonyrnous/pentool)
Web penetration testing and OSINT framework with a modular Python architecture.

- **OSINT:** DNS · WHOIS · subdomain enum · crt.sh · port scan · email harvest · tech fingerprint · SPF/DMARC audit
- **Web Scanner:** SQLi (Error/Union/Blind/Time-based) · XSS (context-aware) · LFI · SSRF · SSTI · IDOR · CORS · security headers · cookie flags
- **Report:** Dark-theme HTML + TXT · CVSS v3.1 · executive summary · risk matrix

```bash
python3 pentool.py full -d example.com -o report --client ACME --tester darkanonyrnous
```

### [PicoCTF Writeups — 93+ Challenges](https://github.com/darkanonyrnous/cylab-picoctf-writeups)
Step-by-step solutions across all CTF categories: Web Exploitation · Cryptography · Forensics · Reverse Engineering · Binary Exploitation · General Skills.

Topics: SQLi · XSS · JWT · heap overflow · format string · PIE bypass · RSA · steganography · git forensics · hash cracking

---

## Reference Notes

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

## Platforms & Contact

[![TryHackMe](https://img.shields.io/badge/TryHackMe-TokuMei_Top_1%25-red?style=flat&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/TokuMei)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-tokumei-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/tokumei)
[![HackTheBox](https://img.shields.io/badge/HackTheBox_Academy-CPTS-9FEF00?style=flat&logo=hackthebox&logoColor=black)](https://academy.hackthebox.com)
[![PicoCTF](https://img.shields.io/badge/PicoCTF-tokurnei-blue?style=flat)](https://play.picoctf.org/users/tokurnei)
