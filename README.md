# penetration-testing
Penetration testing report on a simulated Metasploitable environment — Nmap, Gobuster, Hydra, John the Ripper — IE3022 Applied Information Assurance assignment.
# Penetration Testing Report – Simulated Mayo Industries Environment

**Course:** IE3022 – Applied Information Assurance  
**Assignment:** 02  
**Student:** Sathursha Ravichandran  
**Student ID:** IT23642300  
**Year 3, Semester 1**

## Overview
A simulated VAPT (Vulnerability Assessment and Penetration Testing) engagement 
performed in a controlled lab environment against a Metasploitable2 target. 
The exercise covered reconnaissance, scanning, enumeration, exploitation, and 
post-exploitation, alongside a Red Team / Blue Team / Purple Team analysis.

## Tools Used
- Nmap – reconnaissance & scanning
- Gobuster – directory enumeration
- Hydra – brute-force authentication testing
- John the Ripper – password hash cracking

## Key Findings
- Weak/default credentials (Telnet brute-forced with Hydra)
- Unencrypted services (FTP, Telnet) exposing sensitive data
- No intrusion detection or monitoring in place
- Multiple OWASP Top 10 vulnerabilities identified (broken auth, security 
  misconfiguration, outdated components, broken access control, etc.)

## Report
See `AIA_2_Assignment.pdf` for the full report.

## Disclaimer
All testing was performed in an isolated, controlled virtual lab environment 
(Metasploitable2 target) strictly for educational purposes as part of university 
coursework on ethical hacking and penetration testing methodology.
