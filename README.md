# Cybersecuritytask2
Network & Web Application Security — Lab Files

Short summary: Hands-on lab exercises for network scanning and web app vulnerabilities using Kali Linux, Metasploitable2, DVWA, Nmap, Wireshark, and OpenVAS.

What’s in this repo

nmap/ — scan outputs and short notes

openvas/ — vulnerability reports

wireshark/ — packet captures (.pcap) and short findings

firewall/ — example iptables rules used

dvwa/ — simple notes and example exploits (SQLi, XSS, CSRF)

Key steps (simple)

Recon: whois, nslookup, Google dork, Shodan.

Scan: nmap -sS -sV -O (TCP, version, OS).

Vulnerability scan: OpenVAS -> generate report.

Packet capture: analyze HTTP/FTP/DNS in Wireshark.

Web tests on DVWA: SQLi, XSS, CSRF (in lab only).

Firewall: block scans with iptables rules.

Deliverables

Nmap & OpenVAS reports

Wireshark captures + short analysis

Notes

All work was done in a contained lab environment (Kali, Metasploitable2, DVWA). Use these files for learning and reference only — do not use on systems you do not own or have permission to test.