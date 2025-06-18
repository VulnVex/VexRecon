# VexRecon - Ethical Reconnaissance Framework

![VexRecon](https://img.shields.io/badge/Author-NullVex-red?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.6%2B-blue?style=flat-square)
![License](https://img.shields.io/badge/License-Custom-green?style=flat-square)

> VexRecon is a stealthy, powerful, and API-free information gathering tool built for ethical hacking, red teaming, and cybersecurity education. Designed with privacy in mind, it performs deep recon without relying on third-party APIs.

---

## ✨ Features

- 🔍 WHOIS Lookup (local-only)
- 🧠 DNS Enumeration
- 🌐 Subdomain Brute-Forcing (wordlist-based)
- 📥 HTTP Header Grabber
- 🛰️ Full Port Scanner (1–65535) with stealth features
- 🕷️ Web Crawler Preview
- 🔒 API-Free by design
- 🧅 Optional Tor/SOCKS5 support for anonymity

---

## 🚀 Installation

```bash
git clone https://github.com/rayan123321-sudo/VexRecon.git
cd VexRecon
pip install -r requirements.txt

## usage 
normally: python3 main

if you want to use tor routing then ensure you have tor runing:

sudo service tor start

then edit the script to set 

USE_TOR = True

you can also run using proxychains:

proxychains python3 main

## example input

[1] WHOIS Lookup
[2] DNS Enumeration
[3] Subdomain Brute-Forcer
[4] HTTP Header Grabber
[5] Full Port Scanner (Stealth)
[6] Web Crawler Preview
[7] Exit

## example output

[+] Performing WHOIS lookup...
    (whois results)

[+] Brute-forcing subdomains...
[FOUND] admin.example.com -> 192.168.1.1

[+] full port scanner
[OPEN] Port 22 -- SSH-2.0-OpenSSH_8.2p1
[OPEN] Port 80 -- HTTP/1.1 200 OK
[open] any port.

[+] DNS Enumeration
   "DNS Enumeration results"

[+] HTTP header grabber
    "grabbed http header"

[+] web crawler preview

   "crawled web results"


## SUPPORT US
tiktok: nullvex.ui
instagram: nullvex.ui OR nullvex.uio


## HELP
if you encounter any issue tell us immediatly!

gmail: haffqeer@gmail.com
