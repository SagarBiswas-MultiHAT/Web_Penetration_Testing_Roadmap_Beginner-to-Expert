# 🛠️ Penetration Testing Tools Directory

[⬅ Back to Main README](../README.md)

> A curated collection of essential penetration testing tools, organized by category.

---

## ✅ Essential Tools Checklist (Master These First)

- [ ] **Nmap** - Network scanning and enumeration
- [ ] **Burp Suite** - Web application testing proxy
- [ ] **Metasploit** - Exploitation framework
- [ ] **Wireshark** - Network traffic analysis
- [ ] **Nikto** - Web vulnerability scanner
- [ ] **Dirb/Gobuster** - Directory brute-forcing
- [ ] **SQLMap** - SQL injection automation
- [ ] **John the Ripper** - Password cracking
- [ ] **Netcat** - Network Swiss Army knife

### Intermediate Tools
- [ ] **Cobalt Strike** - Advanced threat emulation
- [ ] **BloodHound** - Active Directory analysis
- [ ] **Responder** - Network credential capture
- [ ] **Empire** - PowerShell post-exploitation
- [ ] **BeEF** - Browser exploitation framework

### Programming Languages Priority
1. **Python** - Most versatile for security automation
2. **Bash** - Linux environment automation
3. **PowerShell** - Windows environment manipulation
4. **JavaScript** - Web application testing
5. **Go** - Modern tool development

---

A more complete list of tools can be found on [Kali Linux official website](https://tools.kali.org/tools-listing).

---

## 🕵️ Information Gathering

| Tool | Language | Support | Description |
|---|---|---|---|
| [theHarvester](https://github.com/laramies/theHarvester) | **Python** | `Linux/Windows/macOS` | E-mails, subdomains and names Harvester. |
| [CTFR](https://github.com/UnaPibaGeek/ctfr) | **Python** | `Linux/Windows/macOS` | Abusing Certificate Transparency logs for getting HTTPS websites subdomains. |
| [Sn1per](https://github.com/1N3/Sn1per) | **bash** | `Linux/macOS` | Automated Pentest Recon Scanner. |
| [RED Hawk](https://github.com/Tuhinshubhra/RED_HAWK) | **PHP** | `Linux/Windows/macOS` | All in one tool for Information Gathering, Vulnerability Scanning and Crawling. |
| [Infoga](https://github.com/m4ll0k/Infoga) | **Python** | `Linux/Windows/macOS` | Email Information Gathering. |
| [KnockMail](https://github.com/4w4k3/KnockMail) | **Python** | `Linux/Windows/macOS` | Check if email address exists. |
| [a2sv](https://github.com/hahwul/a2sv) | **Python** | `Linux/Windows/macOS` | Auto Scanning to SSL Vulnerability. |
| [Wfuzz](https://github.com/xmendez/wfuzz) | **Python** | `Linux/Windows/macOS` | Web application fuzzer. |
| [Nmap](https://github.com/nmap/nmap) | **C/C++** | `Linux/Windows/macOS` | Network host, vuln and port detector. |
| [PhoneInfoga](https://github.com/sundowndev/PhoneInfoga) | **Go** | `Linux/macOS` | An OSINT framework for phone numbers. |

---

## 🔒 Password Attacks

| Tool | Language | Support | Description |
|---|---|---|---|
| [John the Ripper](https://github.com/magnumripper/JohnTheRipper) | **C** | `Linux/Windows/macOS` | Fast password cracker. |
| [hashcat](https://github.com/hashcat/hashcat) | **C** | `Linux/Windows/macOS` | World's fastest password recovery utility. |
| [Hydra](https://github.com/vanhauser-thc/thc-hydra) | **C** | `Linux/Windows/macOS` | Parallelized login cracker for numerous protocols. |
| [ophcrack](https://gitlab.com/objectifsecurite/ophcrack) | **C++** | `Linux/Windows/macOS` | Windows password cracker based on rainbow tables. |
| [Ncrack](https://github.com/nmap/ncrack) | **C** | `Linux/Windows/macOS` | High-speed network authentication cracking tool. |
| [WGen](https://github.com/agusmakmun/Python-Wordlist-Generator) | **Python** | `Linux/Windows/macOS` | Create wordlists with Python. |
| [SSH Auditor](https://github.com/ncsa/ssh-auditor) | **Go** | `Linux/macOS` | Scan for weak ssh passwords. |

### 📝 Wordlists

| Tool | Description |
|---|---|
| [Probable Wordlist](https://github.com/berzerk0/Probable-Wordlists) | Wordlists sorted by probability for password generation and testing. |

---

## 📡 Wireless Testing

| Tool | Language | Support | Description |
|---|---|---|---|
| [Aircrack](https://github.com/aircrack-ng/aircrack-ng) | **C** | `Linux/Windows/macOS` | WiFi security auditing tools suite. |
| [bettercap](https://github.com/bettercap/bettercap) | **Go** | `Linux/Windows/macOS/Android` | Swiss army knife for network attacks and monitoring. |
| [WiFi Pumpkin](https://github.com/P0cL4bs/WiFi-Pumpkin) | **Python** | `Linux/Windows/macOS/Android` | Framework for Rogue Wi-Fi Access Point Attack. |
| [Airgeddon](https://github.com/v1s1t0r1sh3r3/airgeddon) | **Shell** | `Linux/Windows/macOS` | Multi-use bash script to audit wireless networks. |
| [Airbash](https://github.com/tehw0lf/airbash) | **C** | `Linux/Windows/macOS` | Fully automated WPA PSK handshake capture script. |

---

## 🔧 Exploitation Tools

| Tool | Language | Support | Description |
|---|---|---|---|
| [SQLmap](https://github.com/sqlmapproject/sqlmap) | **Python** | `Linux/Windows/macOS` | Automatic SQL injection and database takeover tool. |
| [XSStrike](https://github.com/UltimateHackers/XSStrike) | **Python** | `Linux/Windows/macOS` | Advanced XSS detection and exploitation suite. |
| [Commix](https://github.com/commixproject/commix) | **Python** | `Linux/Windows/macOS` | Automated OS command injection exploitation tool. |
| [Nuclei](https://github.com/projectdiscovery/nuclei) | **Go** | `Linux/Windows/macOS` | Fast vulnerability scanner based on YAML DSL. |

---

## 👥 Sniffing & Spoofing

| Tool | Language | Support | Description |
|---|---|---|---|
| [Wireshark](https://www.wireshark.org) | **C/C++** | `Linux/Windows/macOS` | Network protocol analyzer. |
| [WiFi Pumpkin](https://github.com/P0cL4bs/WiFi-Pumpkin) | **Python** | `Linux/Windows/macOS/Android` | Rogue Wi-Fi Access Point Attack framework. |
| [Zarp](https://github.com/hatRiot/zarp) | **Python** | `Linux/Windows/macOS` | Free network attack framework. |

---

## 🚀 Web Hacking

| Tool | Language | Support | Description |
|---|---|---|---|
| [WPScan](https://github.com/wpscanteam/wpscan) | **Ruby** | `Linux/Windows/macOS` | WordPress vulnerability scanner. |
| [Droopescan](https://github.com/droope/droopescan) | **Python** | `Linux/Windows/macOS` | CMS scanner for Drupal & Silverstripe. |
| [Joomscan](https://github.com/rezasp/joomscan) | **Perl** | `Linux/Windows/macOS` | Joomla Vulnerability Scanner. |
| [Drupwn](https://github.com/immunIT/drupwn) | **Python** | `Linux/Windows/macOS` | Drupal Security Scanner. |
| [CMSeek](https://github.com/Tuhinshubhra/CMSeek) | **Python** | `Linux/Windows/macOS` | CMS Detection and Exploitation suite — 130+ CMSs. |

---

## 🎉 Post Exploitation

| Tool | Language | Support | Description |
|---|---|---|---|
| [TheFatRat](https://github.com/Screetsec/TheFatRat) | **C** | `Linux/Windows/macOS` | Backdoor generation and post exploitation attacks. |

---

## 📦 Frameworks

| Tool | Language | Support | Description |
|---|---|---|---|
| [Metasploit](https://github.com/rapid7/metasploit-framework) | **Ruby** | `Linux/Windows/macOS` | The penetration testing framework. |
| [Operative Framework](https://github.com/graniet/operative-framework) | **Python** | `Linux/Windows/macOS` | Fingerprint-based information gathering framework. |
| [cSploit](https://github.com/cSploit/android) | **Java** | `Android` | IT security professional toolkit on Android. |
| [radare2](https://github.com/radare/radare2) | **C** | `Linux/Windows/macOS/Android` | Reverse engineering framework. |
| [Wifiphisher](https://github.com/wifiphisher/wifiphisher) | **Python** | `Linux` | Rogue Access Point Framework. |
| [Beef](https://github.com/beefproject/beef) | **Javascript** | `Linux/Windows/macOS` | Browser Exploitation Framework. |
| [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) | **Python** | `Linux/Windows/macOS` | Mobile application pen-testing & security assessment. |
| [Burp Suite](https://portswigger.net/burp) | **Java** | `Linux/Windows/macOS` | Leading web security testing tool. **Not free/open source.** |

---

## 🥽 Practice Platforms

### Beginner-Friendly
- **[TryHackMe](https://tryhackme.com/)** - Guided learning paths — see our [500+ Free Rooms List](tryhackme-rooms.md)
- **[OverTheWire](https://overthewire.org/)** - War games for different skill levels
- **[DVWA](https://github.com/digininja/DVWA)** - Deliberately vulnerable web application
- **[Itsecgames](http://www.itsecgames.com/)** - bWAPP deliberately insecure web application
- **[Hackthissite](https://www.hackthissite.org/)** - Challenges, CTFs, and more
- **[Defend the Web](https://defendtheweb.net/)** - Interactive security challenges
- **[PicoCTF](https://picoctf.org/)** - CTF challenges of varying difficulty

### Intermediate
- **[HackTheBox](https://www.hackthebox.eu/)** - Real-world penetration testing labs
- **[PortSwigger Web Security Academy](https://portswigger.net/web-security)** - Free web security training
- **[VulnHub](https://www.vulnhub.com/)** - Vulnerable virtual machines
- **[Root-me](https://www.root-me.org/)** - Challenges to test your hacking skills

### Advanced
- **[Offensive Security Labs](https://www.offensive-security.com/)** - Professional-grade labs
- **[SANS NetWars](https://www.sans.org/netwars/)** - Competitive exercises
- **[Cybrary](https://www.cybrary.it/)** - Professional training
- **[Ctftime](https://ctftime.org/)** - The de facto website for everything CTF related

---

[⬅ Back to Main README](../README.md)
