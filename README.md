[🎯 Penetration Testing Learning Roadmap - 2 (YT Videos/Practical labs) Collected](#web-penetration-testing-learning-roadmap-2)

[🎯 Web Penetration Testing Roadmap - 3 (Goals, Practice, Suggested Resources, Tasks) Free](#web-penetration-testing-learning-roadmap-3)

[📂 My More Work](#My_More_Work)


<a id="web-penetration-testing-learning-roadmap-1"></a>


# 🎯 Penetration Testing Learning Roadmap - 1 

> **A structured guide to help you navigate the overwhelming world of penetration testing**

## 📖 Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Phase 1: Foundation Building (4-6 weeks)](#phase-1-foundation-building-4-6-weeks)
- [Phase 2: Core Skills Development (8-12 weeks)](#phase-2-core-skills-development-8-12-weeks)
- [Phase 3: Specialization (12+ weeks)](#phase-3-specialization-12-weeks)
- [Phase 4: Professional Development](#phase-4-professional-development)
- [Practical Labs & Platforms](#practical-labs--platforms)
- [Certification Roadmap](#certification-roadmap)
- [Tools Checklist](#tools-checklist)
- [Resources](#resources)
- [Community](#community)

<a id="introduction"></a>
## 🎭 Introduction

**Feeling overwhelmed is normal!** Penetration testing is a vast field that combines networking, programming, system administration, and security expertise. This roadmap will help you build skills systematically rather than jumping around topics randomly.

### 🎯 Goals of This Roadmap
- **Structure**: Clear learning phases with defined objectives
- **Focus**: One skill at a time to avoid overwhelm
- **Practical**: Hands-on labs and real-world scenarios
- **Progressive**: Each phase builds on the previous one

---

<a id="prerequisites"></a>
## 🔧 Prerequisites

Before diving into pentesting, ensure you have:

### Essential Knowledge
- [ ] **Networking fundamentals** (TCP/IP, DNS, HTTP/HTTPS)
- [ ] **Basic Linux command line** (navigation, file manipulation, permissions)
- [ ] **Understanding of web technologies** (HTML, CSS, basic JavaScript)
- [ ] **Basic scripting** (Python or Bash - Python recommended)

### Recommended Setup
- [ ] **Virtual Machine Environment** (VMware/VirtualBox)
- [ ] **Kali Linux** installed in VM
- [ ] **Windows 10/11** for testing cross-platform tools
- [ ] **Note-taking system** (Obsidian, Notion, or simple markdown files)

---

<a id="phase-1-foundation-building-4-6-weeks"></a>
## 🏗️ Phase 1: Foundation Building (4-6 weeks)

**Goal**: Establish strong fundamentals and get comfortable with essential tools.

### Week 1-2: Networking & Systems
- [ ] **Study OSI Model** and how protocols interact
- [ ] **Learn TCP/IP in depth** - understand ports, protocols, packet flow
- [ ] **Master basic Linux commands** - file system, processes, networking commands
- [ ] **Understand Windows fundamentals** - registry, services, file system

**Practical Lab**: Set up a basic home lab with 2-3 VMs communicating with each other.

### Week 3-4: Reconnaissance Fundamentals
- [ ] **Learn information gathering techniques**
  - Google dorking
  - WHOIS lookups
  - DNS enumeration
  - Social media intelligence (OSINT)

**Tools to Master**:
- `nmap` - Network scanning
- `dig` / `nslookup` - DNS queries
- `whois` - Domain information
- `theHarvester` - Email/domain gathering

**Practical Lab**: 
- Perform reconnaissance on a target from TryHackMe or HackTheBox
- Document your findings in a structured report

### Week 5-6: Web Application Basics
- [ ] **Understand web application architecture**
- [ ] **Learn about common web vulnerabilities** (OWASP Top 10 overview)
- [ ] **Get comfortable with Burp Suite** basics
- [ ] **Practice with browser developer tools**

**Practical Lab**: 
- Complete DVWA (Damn Vulnerable Web Application) basic exercises
- Practice intercepting and modifying HTTP requests

---

<a id="phase-2-core-skills-development-8-12-weeks"></a>
## 🎯 Phase 2: Core Skills Development (8-12 weeks)

**Goal**: Develop proficiency in major penetration testing domains.

### Weeks 7-10: Web Application Security
**Focus on the most common attack vectors in modern environments.**

#### Week 7: Input Validation Attacks
- [ ] **SQL Injection**
  - Understanding different types (Union, Boolean, Time-based)
  - Manual exploitation techniques
  - Automated tools (SQLMap)
- [ ] **Cross-Site Scripting (XSS)**
  - Reflected, Stored, DOM-based XSS
  - Payload crafting and bypass techniques

**Practice Labs**:
- PortSwigger Web Security Academy (SQL Injection & XSS labs)
- DVWA intermediate level

#### Week 8: Authentication & Session Management
- [ ] **Authentication bypass techniques**
- [ ] **Session hijacking and fixation**
- [ ] **Password attacks** (brute force, dictionary attacks)
- [ ] **Multi-factor authentication bypasses**

**Tools**: Hydra, John the Ripper, Hashcat

#### Week 9: Advanced Web Attacks
- [ ] **Server-Side Request Forgery (SSRF)**
- [ ] **XML External Entity (XXE) attacks**
- [ ] **Insecure Direct Object References (IDOR)**
- [ ] **File upload vulnerabilities**

#### Week 10: Web Application Assessment Methodology
- [ ] **Structured testing approach**
- [ ] **Report writing for web application findings**
- [ ] **Risk assessment and CVSS scoring**

### Weeks 11-14: Network Penetration Testing

#### Week 11: Network Scanning & Enumeration
- [ ] **Advanced Nmap techniques**
  - Scripting engine (NSE)
  - Stealth scanning techniques
  - Firewall/IDS evasion
- [ ] **Service enumeration**
  - SMB, FTP, SSH, HTTP, DNS
  - Banner grabbing and version detection

**Practice**: TryHackMe Network Security modules

#### Week 12-13: Exploitation Techniques
- [ ] **Metasploit Framework mastery**
  - Exploit modules, payloads, encoders
  - Post-exploitation modules
  - Meterpreter usage
- [ ] **Manual exploitation techniques**
- [ ] **Buffer overflow basics** (optional but valuable)

#### Week 14: Post-Exploitation
- [ ] **Privilege escalation** (Linux and Windows)
- [ ] **Lateral movement techniques**
- [ ] **Persistence mechanisms**
- [ ] **Data exfiltration methods**

### Weeks 15-18: Scripting & Automation

#### Week 15-16: Python for Pentesters
- [ ] **Network programming** (sockets, HTTP requests)
- [ ] **Automation scripts** for common tasks
- [ ] **Custom exploit development** basics
- [ ] **API testing automation**

**Projects**:
- Build a port scanner
- Create a web directory brute-forcer
- Automate SQLi detection

#### Week 17-18: Advanced Scripting
- [ ] **Bash scripting** for Linux environments
- [ ] **PowerShell** for Windows environments
- [ ] **Tool integration** and workflow automation

---

<a id="phase-3-specialization-12-weeks"></a>
## 🚀 Phase 3: Specialization (12+ weeks)

**Goal**: Choose 1-2 specialization areas based on your interests and career goals.

### Option A: Advanced Web Application Security
- **Advanced exploitation techniques**
- **Code review and static analysis**
- **API security testing**
- **Modern framework vulnerabilities**

### Option B: Infrastructure & Network Security
- **Active Directory exploitation**
- **Cloud security (AWS, Azure, GCP)**
- **Wireless security testing**
- **IoT and embedded device testing**

### Option C: Mobile Application Security
- **Android application testing**
- **iOS application testing**
- **Mobile device management bypass**
- **API security for mobile apps**

### Option D: Red Team Operations
- **Social engineering techniques**
- **Physical security testing**
- **Advanced persistent threat simulation**
- **Command and control (C2) frameworks**

---

<a id="phase-4-professional-development"></a>
## 🏆 Phase 4: Professional Development

### Capture the Flag (CTF) Participation
- [ ] Join weekly CTF competitions
- [ ] Participate in major CTFs (DefCon, PlaidCTF, etc.)
- [ ] Create write-ups for solved challenges

### Bug Bounty Programs
- [ ] Start with beginner-friendly programs
- [ ] Develop a systematic testing methodology
- [ ] Build relationships in the security community

### Continuous Learning
- [ ] Follow security researchers and publications
- [ ] Attend security conferences (BSides, DefCon, Black Hat)
- [ ] Contribute to open-source security tools

---

<a id="practical-labs--platforms"></a>
## 🥽 Practical Labs & Platforms

### Beginner-Friendly
- **[TryHackMe](https://tryhackme.com/)** - Guided learning paths

#### Welcome, Hackers! 👾

Here’s a curated list of **500+ Free TryHackMe rooms** to help you dive into cybersecurity and hacking. These rooms are organized by topic so you can learn and practice systematically. Best part? **They’re all free!** 🧑‍💻🔓  

_**Start hacking now, and happy hunting!** 🏹_  

#### 📜 **Table of Contents**

<div align="center">

| 🔐 **Category**                                  | 🔢 **Rooms** | 🔒 **Rooms Completed by Me** |
| ------------------------------------------------ |:------------:|:---------------------------:|
| **[Introductory Rooms](#intro-rooms)**           |     21       |            9                |
| **[Linux Fundamentals](#linux-fundamentals)**    |      4       |            3                |
| **[Windows Fundamentals](#windows-fundamentals)**|      3       |                             |
| **[Basic Rooms](#basics-rooms)**                 |     14       |            1                |
| **[Reconnaissance](#recon)**                     |     10       |            2                |
| **[Scripting](#scripting)**                      |      7       |                             |
| **[Networking](#networking)**                    |      7       |            5                |
| **[Tooling](#tooling)**                          |     18       |            3                |
| **[Container Security](#container-security)**    |     3        |                              |
| **[Cryptography & Hashes](#cryptography--hashes)**|      7       |            2                |
| **[Steganography](#steganography)**              |      6       |                             |
| **[Web](#web)**                                  |     33       |            5                |
| **[Android](#android)**                          |      1       |                             |
| **[Forensics](#forensics)**                      |     17       |                             |
| **[Wifi Hacking](#wi-fi-hacking)**               |      1       |            1                |
| **[Reverse Engineering](#reverse-engineering)**  |     9       |                             |
| **[Malware Analysis](#malware-analysis)**        |      8       |                             |
| **[Privilege Escalation](#privesc)**             |     13       |            1               |
| **[Windows](#windows)**                          |      9       |            1                |
| **[Active Directory](#active-directory)**        |      8       |                             |
| **[PCAP Analysis](#pcap-analysis)**              |      4       |                             |
| **[Buffer Overflow](#bufferoverflow)**           |      4       |                             |
| **[Easy CTF](#easy-ctf)**                        |     98       |            11               |
| **[Medium CTF](#medium-ctf)**                    |     99       |             4               |
| **[Hard CTF](#hard-ctf)**                        |     42       |                             |
| **[Insane CTF](#insane-ctf)**                    |      1       |             1               |
| **[Misc](#misc)**                                |     43       |                             |
| **[Special Events](#special-events)**            |     12       |             1               |
| **Total Rooms:**                                 |    **= 502** |          **= 50**           |

</div>

#### 🌟 Additional Suggestions for Labs

Here are a few other labs you could consider adding:

1. **Introductory Rooms** 🧑‍💻: Perfect for beginners just starting out on TryHackMe.
2. **Linux Fundamentals** 🐧: Learn Linux, a critical skill for hacking.
3. **Privilege Escalation** 📈: Explore how to elevate permissions for better control in systems.
4. **Malware Analysis** 🦠: Investigate and reverse-engineer malicious code.
5. **Web Hacking** 🌐: Master web vulnerabilities and exploit them like a pro.
6. **OSINT (Open Source Intelligence)** 🕵️‍♂️: Dive into gathering intelligence from publicly available sources.
7. **Social Engineering** 🧠: Practice rooms focusing on human-based hacking techniques like phishing.
8. **Exploit Development** 💻: Learn how to create and modify exploits.
9. **Cloud Security** ☁️: Add rooms related to AWS, Azure, or GCP security.

##### Intro Rooms

- [ ] [🕵️ TryHackMe | Hosted Hypervisors](https://tryhackme.com/room/hostedhypervisors)
  
- [x] [🕵️ TryHackMe | Enumeration & Brute Force](https://tryhackme.com/room/enumerationbruteforce)
  
- [ ] [🕵️ TryHackMe | Introduction to CryptOps](https://tryhackme.com/room/introductiontocryptops)
  
- [ ] [🕵️ TryHackMe | Linux File System Analysis](https://tryhackme.com/room/linuxfilesystemanalysis)
  
- [ ] [🕵️ TryHackMe | Threat Hunting: Foothold](https://tryhackme.com/room/threathuntingfoothold)
  
- [x] [🕵️ TryHackMe | Threat Hunting: Introduction](https://tryhackme.com/room/introductiontothreathunting)
  
- [ ] [🕵️ TryHackMe | Preparation](https://tryhackme.com/room/preparation)

- [ ] [🕵️ TryHackMe | Intro to Logs](https://tryhackme.com/room/introtologs)

- [ ] [🕵️ TryHackMe | Intro to Threat Emulation](https://tryhackme.com/room/threatemulationintro)

- [x] [🕵️ TryHackMe | Security Engineer Intro](https://tryhackme.com/room/securityengineerintro)
  
- [ ] [🕵️ TryHackMe | Intro to Docker](https://tryhackme.com/room/introtodockerk8pdqk)

- [x] [🕵️ TryHackMe | SDLC](https://tryhackme.com/room/sdlc)

- [ ] [🕵️ TryHackMe | Welcome](https://tryhackme.com/room/hello)

- [ ] [🕵️ TryHackMe | How to use TryHackMe](https://tryhackme.com/room/howtousetryhackme)

- [x] [🕵️ TryHackMe | Tutorial](https://tryhackme.com/room/tutorial)

- [x] [🕵️ TryHackMe | OpenVPN](https://tryhackme.com/room/openvpn)

- [x] [🕵️ TryHackMe | Learning Cyber Security](https://tryhackme.com/room/beginnerpathintro)

- [x] [🕵️ TryHackMe | Starting Out In Cyber Sec](https://tryhackme.com/room/startingoutincybersec)

- [ ] [🕵️ TryHackMe | Introductory Researching](https://tryhackme.com/room/introtoresearch)

- [ ] [🕵️ TryHackMe | Regular expressions](https://tryhackme.com/room/catregex)

- [x] [🕵️ TryHackMe | Careers in Cyber](https://tryhackme.com/room/careersincyber)

- [ ] [🕵️ TryHackMe | Junior Security Analyst Intro](https://tryhackme.com/room/jrsecanalystintrouxo)




##### Linux Fundamentals

- [ ] [🕵️ TryHackMe | Linux Modules](https://tryhackme.com/room/linuxmodules)
  
- [x] [🕵️ TryHackMe | Linux Fundamentals Part 1](https://tryhackme.com/room/linuxfundamentalspart1)
  
- [x] [🕵️ TryHackMe | Linux Fundamentals Part 2](https://tryhackme.com/room/linuxfundamentalspart2)  **🚨 Attention!** Multiple users have reported that this room is **no longer free.**
 
- [x] [🕵️ TryHackMe | Linux Fundamentals Part 3](https://tryhackme.com/room/linuxfundamentalspart3)  **🚨 Attention!** Multiple users have reported that this room is **no longer free.**

##### Windows Fundamentals

- [ ] [🕵️ TryHackMe | Windows Fundamentals 1](https://tryhackme.com/room/windowsfundamentals1xbx)
  
- [ ] [🕵️ TryHackMe | Windows Fundamentals 2](https://tryhackme.com/room/windowsfundamentals2x0x)
  
- [ ] [🕵️ TryHackMe | Windows Fundamentals 3](https://tryhackme.com/room/windowsfundamentals3xzx)

##### Basics Rooms

- [ ] [🕵️ TryHackMe | Hypervisor Internals](https://tryhackme.com/room/hypervisorinternals)
  
- [ ] [🕵️ TryHackMe | Splunk: Exploring SPL](https://tryhackme.com/room/splunkexploringspl)

- [ ] [🕵️ TryHackMe | ParrotPost: Phishing Analysis](https://tryhackme.com/room/parrotpost)

- [ ] [🕵️ TryHackMe | x86 Architecture Overview](https://tryhackme.com/room/x8664arch)

- [ ] [🕵️ TryHackMe | Threat Intelligence for SOC](https://tryhackme.com/room/threatintelligenceforsoc)

- [ ] [🕵️ TryHackMe | Basic Pentesting](https://tryhackme.com/room/basicpentestingjt)

- [x] [🕵️ TryHackMe | Pentesting Fundamentals](https://tryhackme.com/room/pentestingfundamentals)

- [ ] [🕵️ TryHackMe | Principles of Security](https://tryhackme.com/room/principlesofsecurity)

- [ ] [🕵️ TryHackMe | The Hacker Methodology](https://tryhackme.com/room/hackermethodology)

- [ ] [🕵️ TryHackMe | Physical Security Intro](https://tryhackme.com/room/physicalsecurityintro)

- [ ] [🕵️ TryHackMe | Linux Strength Training](https://tryhackme.com/room/linuxstrengthtraining)

- [ ] [🕵️ TryHackMe | OpenVAS](https://tryhackme.com/room/openvas)

- [ ] [🕵️ TryHackMe | ISO27001](https://tryhackme.com/room/iso27001)

- [ ] [🕵️ TryHackMe | UltraTech](https://tryhackme.com/room/ultratech1)

##### Recon

- [ ] [🕵️ TryHackMe | Passive Reconnaissance](https://tryhackme.com/room/passiverecon)

- [ ] [🕵️ TryHackMe | Active Reconnaissance](https://tryhackme.com/room/activerecon)

- [ ] [🕵️ TryHackMe | Content Discovery](https://tryhackme.com/room/contentdiscovery)

- [x] [🕵️ TryHackMe | OhSINT](https://tryhackme.com/room/ohsint)

- [ ] [🕵️ TryHackMe | Shodan.io](https://tryhackme.com/room/shodan)

- [x] [🕵️ TryHackMe | Google Dorking](https://tryhackme.com/room/googledorking)

- [ ] [🕵️ TryHackMe | WebOSINT](https://tryhackme.com/room/webosint)

- [ ] [🕵️ TryHackMe | Sakura Room](https://tryhackme.com/room/sakura)

- [ ] [🕵️ TryHackMe | Red Team Recon](https://tryhackme.com/room/redteamrecon)

- [ ] [🕵️ TryHackMe | Searchlight - IMINT](https://tryhackme.com/room/searchlightosint)

##### Scripting

- [ ] [🕵️ TryHackMe | Python Basics](https://tryhackme.com/room/pythonbasics)

- [ ] [🕵️ TryHackMe | Python Playground](https://tryhackme.com/room/pythonplayground)

- [ ] [🕵️ TryHackMe | Intro PoC Scripting](https://tryhackme.com/room/intropocscripting)

- [ ] [🕵️ TryHackMe | Peak Hill](https://tryhackme.com/room/peakhill)

- [ ] [🕵️ TryHackMe | JavaScript Basics](https://tryhackme.com/room/javascriptbasics)

- [ ] [🕵️ TryHackMe | Bash Scripting](https://tryhackme.com/room/bashscripting)

- [ ] [🕵️ TryHackMe | Learn Rust](https://tryhackme.com/room/rust)

##### Networking

- [x] [🕵️ TryHackMe | Introductory Networking](https://tryhackme.com/room/introtonetworking)

- [x] [🕵️ TryHackMe | What is Networking?](https://tryhackme.com/room/whatisnetworking)

- [ ] [🕵️ TryHackMe | Networking](https://tryhackme.com/room/bpnetworking)

- [x] [🕵️ TryHackMe | Intro to LAN](https://tryhackme.com/room/introtolan) **🚨 Attention!** Multiple users have reported that this room is **no longer free.**

- [x] [🕵️ TryHackMe | HTTP in detail](https://tryhackme.com/room/httpindetail)

- [x] [🕵️ TryHackMe | DNS in detail](https://tryhackme.com/room/dnsindetail)

- [ ] [🕵️ TryHackMe | Dumping Router Firmware](https://tryhackme.com/room/rfirmware)

##### Tooling

- [ ] [🕵️ TryHackMe | Snyk Open Source](https://tryhackme.com/room/snykopensource)
  
- [ ] [🕵️ TryHackMe | Snyk Code](https://tryhackme.com/room/snykcode)
  
- [ ] [🕵️ TryHackMe | Intro to IaC](https://tryhackme.com/room/introtoiac)

- [x] [🕵️ TryHackMe | Metasploit: Introduction](https://tryhackme.com/room/metasploitintro)

- [ ] [🕵️ TryHackMe | tmux](https://tryhackme.com/room/rptmux)

- [ ] [🕵️ TryHackMe | REmux The Tmux](https://tryhackme.com/room/tmuxremux)

- [ ] [🕵️ TryHackMe | Hydra](https://tryhackme.com/room/hydra)

- [ ] [🕵️ TryHackMe | Toolbox: Vim](https://tryhackme.com/room/toolboxvim)

- [ ] [🕵️ TryHackMe | Introduction to OWASP ZAP](https://tryhackme.com/room/learnowaspzap)

- [ ] [🕵️ TryHackMe | Phishing: HiddenEye](https://tryhackme.com/room/phishinghiddeneye)

- [ ] [🕵️ TryHackMe | RustScan](https://tryhackme.com/room/rustscan)

- [x] [🕵️ TryHackMe | Nessus](https://tryhackme.com/room/rpnessusredux)

- [ ] [🕵️ TryHackMe | Nmap Live Host Discovery](https://tryhackme.com/room/nmap01)

- [x] [🕵️ TryHackMe | Nmap](https://tryhackme.com/room/furthernmap)

- [ ] [🕵️ TryHackMe | TShark](https://tryhackme.com/room/tshark)

- [ ] [🕵️ TryHackMe | ffuf](https://tryhackme.com/room/ffuf)

- [ ] [🕵️ TryHackMe | Burp Suite: The Basics](https://tryhackme.com/room/burpsuitebasics)

- [ ] [🕵️ TryHackMe | Burp Suite: Repeater](https://tryhackme.com/room/burpsuiterepeater)

##### Container Security

- [ ] [🕵️ TryHackMe | K8s Runtime Security](https://tryhackme.com/room/k8sruntimesecurity)
  
- [ ] [🕵️ TryHackMe | K8s Best Security Practices](https://tryhackme.com/room/k8sbestsecuritypractices)
  
- [ ] [🕵️ TryHackMe | Cluster Hardening](https://tryhackme.com/room/clusterhardening)

##### Cryptography & Hashes

- [ ] [🕵️ TryHackMe | Breaking RSA](https://tryhackme.com/room/breakrsa)

- [ ] [🕵️ TryHackMe | Cryptography for Dummies](https://tryhackme.com/room/cryptographyfordummies)

- [x] [🕵️ TryHackMe | Crack the hash](https://tryhackme.com/room/crackthehash)

- [ ] [🕵️ TryHackMe | Crack The Hash Level 2](https://tryhackme.com/room/crackthehashlevel2)

- [ ] [🕵️ TryHackMe | Agent Sudo](https://tryhackme.com/room/agentsudoctf)

- [ ] [🕵️ TryHackMe | Brute It](https://tryhackme.com/room/bruteit)

- [x] [🕵️ TryHackMe | Introduction to Cryptography](https://tryhackme.com/room/cryptographyintro)

##### Steganography

- [ ] [🕵️ TryHackMe | CC: Steganography](https://tryhackme.com/room/ccstego)

- [ ] [🕵️ TryHackMe | Cicada-3301 Vol:1](https://tryhackme.com/room/cicada3301vol1)

- [ ] [🕵️ TryHackMe | Musical Stego](https://tryhackme.com/room/musicalstego)

- [ ] [🕵️ TryHackMe | Madness](https://tryhackme.com/room/madness)

- [ ] [🕵️ TryHackMe | Psycho Break](https://tryhackme.com/room/psychobreak)

- [ ] [🕵️ TryHackMe | Unstable Twin](https://tryhackme.com/room/unstabletwin)

##### Web

- [x] [🕵️ TryHackMe | Microservices Architectures](https://tryhackme.com/room/microservicearchitectures)
  
- [x] [🕵️ TryHackMe | NoSQL Injection](https://tryhackme.com/room/nosqlinjectiontutorial)
  
- [ ] [🕵️ TryHackMe | Advanced SQL Injection](https://tryhackme.com/room/advancedsqlinjection)
  
- [x] [🕵️ TryHackMe | XSS](https://tryhackme.com/room/axss)
  
- [ ] [🕵️ TryHackMe | CSRF](https://tryhackme.com/room/csrfV2)
  
- [ ] [🕵️ TryHackMe | File Inclusion, Path Traversal](https://tryhackme.com/room/filepathtraversal)
  
- [ ] [🕵️ TryHackMe | HTTP Request Smuggling](https://tryhackme.com/room/httprequestsmuggling)
  
- [ ] [🕵️ TryHackMe | HTTP/2 Request Smuggling](https://tryhackme.com/room/http2requestsmuggling)

- [ ] [🕵️ TryHackMe | SSRF](https://tryhackme.com/room/ssrfhr)

- [x] [🕵️ TryHackMe | OWASP Broken Access Control](https://tryhackme.com/room/owaspbrokenaccesscontrol)

- [ ] [🕵️ TryHackMe | HTTP in detail](https://tryhackme.com/room/webfundamentals)

- [ ] [🕵️ TryHackMe | Vulnerabilities 101](https://tryhackme.com/room/vulnerabilities101)

- [ ] [🕵️ TryHackMe | Walking An Application](https://tryhackme.com/room/walkinganapplication)

- [ ] [🕵️ TryHackMe | OWASP Top 10 - 2021](https://tryhackme.com/room/owasptop102021)

- [ ] [🕵️ TryHackMe | OWASP Top 10](https://tryhackme.com/room/owasptop10)

- [ ] [🕵️ TryHackMe | OWASP Juice Shop](https://tryhackme.com/room/owaspjuiceshop)

- [ ] [🕵️ TryHackMe | OWASP Mutillidae II](https://tryhackme.com/room/owaspmutillidae)

- [ ] [🕵️ TryHackMe | WebGOAT](https://tryhackme.com/room/webgoat)

- [x] [🕵️ TryHackMe | Web Application Security](https://tryhackme.com/room/introwebapplicationsecurity)

- [ ] [🕵️ TryHackMe | DVWA](https://tryhackme.com/room/dvwa)

- [ ] [🕵️ TryHackMe | VulnNet](https://tryhackme.com/room/vulnnet1)

- [ ] [🕵️ TryHackMe | Juicy Details](https://tryhackme.com/room/juicydetails)

- [ ] [🕵️ TryHackMe | Vulnversity](https://tryhackme.com/room/vulnversity)

- [ ] [🕵️ TryHackMe | SQL Injection Lab](https://tryhackme.com/room/sqlilab)

- [ ] [🕵️ TryHackMe | SSTI](https://tryhackme.com/room/learnssti)

- [ ] [🕵️ TryHackMe | SQL Injection](https://tryhackme.com/room/sqlinjectionlm)

- [ ] [🕵️ TryHackMe | Basic Pentesting](https://tryhackme.com/room/basicpentestingjt)

- [ ] [🕵️ TryHackMe | Ignite](https://tryhackme.com/room/ignite)

- [ ] [🕵️ TryHackMe | Overpass](https://tryhackme.com/room/overpass)

- [ ] [🕵️ TryHackMe | Year of the Rabbit](https://tryhackme.com/room/yearoftherabbit)

- [ ] [🕵️ TryHackMe | Develpy](https://tryhackme.com/room/bsidesgtdevelpy)

- [ ] [🕵️ TryHackMe | Jack-of-All-Trades](https://tryhackme.com/room/jackofalltrades)

- [ ] [🕵️ TryHackMe | Bolt](https://tryhackme.com/room/bolt)

##### Android

- [ ] [🕵️ TryHackMe | Android Hacking 101](https://tryhackme.com/room/androidhacking101)

##### Forensics

- [ ] [🕵️ TryHackMe | Linux Incident Surface](https://tryhackme.com/room/linuxincidentsurface)
  
- [ ] [🕵️ TryHackMe | IR Playbooks](https://tryhackme.com/room/irplaybooks)
  
- [ ] [🕵️ TryHackMe | Intro to Cold System Forensics](https://tryhackme.com/room/introtocoldsystemforensics)

- [ ] [🕵️ TryHackMe | Unified Kill Chain](https://tryhackme.com/room/unifiedkillchain)

- [ ] [🕵️ TryHackMe | Forensic Imaging](https://tryhackme.com/room/forensicimaging)
  
- [ ] [🕵️ TryHackMe | IR Philosophy and Ethics](https://tryhackme.com/room/irphilosophyethics)
  
- [ ] [🕵️ TryHackMe | Windows Applications Forensics](https://tryhackme.com/room/windowsapplications)

- [ ] [🕵️ TryHackMe | Legal Considerations in DFIR](https://tryhackme.com/room/dfirprocesslegalconsiderations)

- [ ] [🕵️ TryHackMe | Servidae: Log Analysis in ELK](https://tryhackme.com/room/servidae)

- [ ] [🕵️ TryHackMe | Cyber Kill Chain](https://tryhackme.com/room/cyberkillchainzmt)

- [ ] [🕵️ TryHackMe | Identification & Scoping](https://tryhackme.com/room/identificationandscoping)

- [ ] [🕵️ TryHackMe | Digital Forensics Case B4DM755](https://tryhackme.com/room/caseb4dm755)

- [ ] [🕵️ TryHackMe | Linux Server Forensics](https://tryhackme.com/room/linuxserverforensics)

- [ ] [🕵️ TryHackMe | Forensics](https://tryhackme.com/room/forensics)

- [ ] [🕵️ TryHackMe | Memory Forensics](https://tryhackme.com/room/memoryforensics)

- [ ] [🕵️ TryHackMe | Volatility](https://tryhackme.com/room/bpvolatility)

- [ ] [🕵️ TryHackMe | Disk Analysis &amp; Autopsy](https://tryhackme.com/room/autopsy2ze0)

##### Wi-Fi Hacking

- [ ] [🕵️ TryHackMe | Wifi Hacking 101](https://tryhackme.com/room/wifihacking101)

##### Reverse Engineering

- [ ] [🕵️ TryHackMe | Windows x64 Assembly](https://tryhackme.com/room/win64assembly)

- [ ] [🕵️ TryHackMe | Reversing ELF](https://tryhackme.com/room/reverselfiles)

- [ ] [🕵️ TryHackMe | Windows Reversing Intro](https://tryhackme.com/room/windowsreversingintro) 

- [ ] [🕵️ TryHackMe | JVM Reverse Engineering](https://tryhackme.com/room/jvmreverseengineering)

- [ ] [🕵️ TryHackMe | CC: Radare2](https://tryhackme.com/room/ccradare2)

- [ ] [🕵️ TryHackMe | CC: Ghidra](https://tryhackme.com/room/ccghidra)

- [ ] [🕵️ TryHackMe | Aster](https://tryhackme.com/room/aster)

- [ ] [🕵️ TryHackMe | Classic Passwd](https://tryhackme.com/room/classicpasswd)

- [ ] [🕵️ TryHackMe | REloaded](https://tryhackme.com/room/reloaded)

##### Malware Analysis

- [ ] [🕵️ TryHackMe | Intro to Detection Engineering](https://tryhackme.com/room/introtodetectionengineering)

- [ ] [🕵️ TryHackMe | History of Malware](https://tryhackme.com/room/historyofmalware)

- [ ] [🕵️ TryHackMe | MAL: Malware Introductory](https://tryhackme.com/room/malmalintroductory)

- [ ] [🕵️ TryHackMe | Basic Malware RE](https://tryhackme.com/room/basicmalwarere)

- [ ] [🕵️ TryHackMe | MAL: Researching](https://tryhackme.com/room/malresearching)

- [ ] [🕵️ TryHackMe | Mobile Malware Analysis](https://tryhackme.com/room/mma)

- [ ] [🕵️ TryHackMe | Carnage](https://tryhackme.com/room/c2carnage)

- [ ] [🕵️ TryHackMe | Dunkle Materie](https://tryhackme.com/room/dunklematerieptxc9)

##### PrivEsc

- [ ] [🕵️ TryHackMe | Linux Privilege Escalation](https://tryhackme.com/room/linprivesc)
  
- [x] [🕵️ TryHackMe | Linux PrivEsc](https://tryhackme.com/room/linuxprivesc)
  
- [ ] [🕵️ TryHackMe | Linux PrivEsc Arena](https://tryhackme.com/room/linuxprivescarena)
  
- [ ] [🕵️ TryHackMe | Windows PrivEsc](https://tryhackme.com/room/windows10privesc)
  
- [ ] [🕵️ TryHackMe | Windows PrivEsc Arena](https://tryhackme.com/room/windowsprivescarena)
  
- [ ] [🕵️ TryHackMe | Linux Agency](https://tryhackme.com/room/linuxagency)
  
- [ ] [🕵️ TryHackMe | Sudo Security Bypass](https://tryhackme.com/room/sudovulnsbypass)
  
- [ ] [🕵️ TryHackMe | Sudo Buffer Overflow](https://tryhackme.com/room/sudovulnsbof)
  
- [ ] [🕵️ TryHackMe | Blaster](https://tryhackme.com/room/blaster)
  
- [ ] [🕵️ TryHackMe | Ignite](https://tryhackme.com/room/ignite)
  
- [ ] [🕵️ TryHackMe | Kenobi](https://tryhackme.com/room/kenobi)
  
- [ ] [🕵️ TryHackMe | c4ptur3-th3-fl4g](https://tryhackme.com/room/c4ptur3th3fl4g)
  
- [ ] [🕵️ TryHackMe | Pickle Rick](https://tryhackme.com/room/picklerick)

##### Windows

- [ ] [🕵️ TryHackMe | Windows Incident Surface](https://tryhackme.com/room/winincidentsurface)
  
- [ ] [🕵️ TryHackMe | Registry Persistence Detection](https://tryhackme.com/room/registrypersistencedetection)
  
- [ ] [🕵️ TryHackMe | Investigating Windows](https://tryhackme.com/room/investigatingwindows)
  
- [ ] [🕵️ TryHackMe | Investigating Windows 2.0](https://tryhackme.com/room/investigatingwindows2)
  
- [ ] [🕵️ TryHackMe | Investigating Windows 3.x](https://tryhackme.com/room/investigatingwindows3)
  
- [ ] [🕵️ TryHackMe | Blueprint](https://tryhackme.com/room/blueprint)
  
- [ ] [🕵️ TryHackMe | VulnNet: Active](https://tryhackme.com/room/vulnnetactive)
  
- [ ] [🕵️ TryHackMe | Anthem](https://tryhackme.com/room/anthem)
  
- [x] [🕵️ TryHackMe | Blue](https://tryhackme.com/room/blue)

##### Active Directory

- [ ] [🕵️ TryHackMe | Active Directory Hardening](https://tryhackme.com/room/activedirectoryening)

- [ ] [[🕵️ TryHackMe | Active Directory Basics](https://tryhackme.com/room/winadbasics)

- [ ] [[🕵️ TryHackMe | Breaching Active Directory](https://tryhackme.com/room/breachingad)
  
- [ ] [🕵️ TryHackMe | Attacktive Directory](https://tryhackme.com/room/attacktivedirectory)
  
- [ ] [🕵️ TryHackMe | Post-Exploitation Basics](https://tryhackme.com/room/postexploit)
  
- [ ] [🕵️ TryHackMe | USTOUN](https://tryhackme.com/room/ustoun)
  
- [ ] [🕵️ TryHackMe | Enterprise](https://tryhackme.com/room/enterprise)
  
- [ ] [🕵️ TryHackMe | RazorBlack](https://tryhackme.com/room/raz0rblack)

##### PCAP Analysis

- [ ] [🕵️ TryHackMe | h4cked](https://tryhackme.com/room/h4cked)
  
- [ ] [🕵️ TryHackMe | Carnage](https://tryhackme.com/room/c2carnage)
  
- [ ] [🕵️ TryHackMe | CCT2019](https://tryhackme.com/room/cct2019)
  
- [ ] [🕵️ TryHackMe | Overpass 2 - Hacked](https://tryhackme.com/room/overpass2hacked)

##### BufferOverflow

- [ ] [🕵️ TryHackMe | Buffer Overflow Prep](https://tryhackme.com/room/bufferoverflowprep)
  
- [ ] [🕵️ TryHackMe | Gatekeeper](https://tryhackme.com/room/gatekeeper)
  
- [ ] [🕵️ TryHackMe | Chronicle](https://tryhackme.com/room/chronicle)
  
- [ ] [🕵️ TryHackMe | Intro To Pwntools](https://tryhackme.com/room/introtopwntools)

##### Easy CTF

- [x] [🕵️ TryHackMe | Offensive Security Intro](https://tryhackme.com/room/offensivesecurityintro)

- [x] [🕵️ TryHackMe | Defensive Security Intro](https://tryhackme.com/room/defensivesecurityintro)
      
- [ ] [🕵️ TryHackMe | Pyrat](https://tryhackme.com/room/pyrat)
  
- [ ] [🕵️ TryHackMe | Cheese CTF](https://tryhackme.com/room/cheesectfv10)
  
- [ ] [🕵️ TryHackMe | U.A. High School](https://tryhackme.com/room/yueiua)
  
- [ ] [🕵️ TryHackMe | Joomify](https://tryhackme.com/room/joomify)
  
- [ ] [🕵️ TryHackMe | Critical](https://tryhackme.com/room/critical)
  
- [ ] [🕵️ TryHackMe | Publisher](https://tryhackme.com/room/publisher)

- [ ] [🕵️ TryHackMe | Eviction](https://tryhackme.com/room/eviction)

- [x] [🕵️ TryHackMe | Become a Hacker](https://tryhackme.com/room/becomeahackeroa)

- [x] [🕵️ TryHackMe | W1seGuy](https://tryhackme.com/room/w1seguy)
  
- [ ] [🕵️ TryHackMe | mKingdom](https://tryhackme.com/room/mkingdom)

- [x] [🕵️ TryHackMe | How Websites Work](https://tryhackme.com/room/howwebsiteswork)
  
- [ ] [🕵️ TryHackMe | Linux Process Analysis](https://tryhackme.com/room/linuxprocessanalysis)
  
- [x] [🕵️ TryHackMe | CyberLens](https://tryhackme.com/room/cyberlensp6)

- [ ] [🕵️ TryHackMe | Security Principles](https://tryhackme.com/room/securityprinciples)
  
- [ ] [🕵️ TryHackMe | TryHack3M: Bricks Heist](https://tryhackme.com/room/tryhack3mbricksheist)
  
- [ ] [🕵️ TryHackMe | Creative](https://tryhackme.com/room/creative)
  
- [ ] [🕵️ TryHackMe | Eviction](https://tryhackme.com/room/eviction)

- [x] [🕵️ TryHackMe | Putting it all together](https://tryhackme.com/room/puttingitalltogether)
  
- [ ] [🕵️ TryHackMe | Probe](https://tryhackme.com/room/probe)
  
- [ ] [🕵️ TryHackMe | Dreaming](https://tryhackme.com/room/dreaming)

- [ ] [🕵️ TryHackMe | Pyramid Of Pain](https://tryhackme.com/room/pyramidofpainax)
  
- [ ] [🕵️ TryHackMe | The Witch's Cauldron](https://tryhackme.com/room/cauldron)
  
- [ ] [🕵️ TryHackMe | Bulletproof Penguin ](https://tryhackme.com/room/bppenguin)
  
- [ ] [🕵️ TryHackMe | Hijack ](https://tryhackme.com/room/hijack)
  
- [ ] [🕵️ TryHackMe | Compiled ](https://tryhackme.com/room/compiled)
  
- [ ] [🕵️ TryHackMe | Super Secret TIp](https://tryhackme.com/room/supersecrettip)
  
- [x] [🕵️ TryHackMe | Lesson Learned?](https://tryhackme.com/room/lessonlearned)
  
- [ ] [🕵️ TryHackMe | Grep](https://tryhackme.com/room/greprtp)
  
- [ ] [🕵️ TryHackMe | Red](https://tryhackme.com/room/redisl33t)
  
- [ ] [🕵️ TryHackMe | Snapped "Phish"-ing Line](https://tryhackme.com/room/snappedphishingline)
  
- [ ] [🕵️ TryHackMe | Cat Pictures 2](https://tryhackme.com/room/catpictures2)
  
- [ ] [🕵️ TryHackMe | Flip](https://tryhackme.com/room/flip)
  
- [ ] [🕵️ TryHackMe | Valley!](https://tryhackme.com/room/valleype)
  
- [ ] [🕵️ TryHackMe | Capture!](https://tryhackme.com/room/capture)
  
- [x] [🕵️ TryHackMe | Opacity](https://tryhackme.com/room/opacity)
  
- [ ] [🕵️ TryHackMe | LookBack](https://tryhackme.com/room/lookback)
  
- [ ] [🕵️ TryHackMe | Bugged](https://tryhackme.com/room/bugged)
  
- [ ] [🕵️ TryHackMe | GamingServer](https://tryhackme.com/room/gamingserver)
  
- [ ] [🕵️ TryHackMe | Confidential](https://tryhackme.com/room/confidential)
  
- [ ] [🕵️ TryHackMe | OverlayFS - CVE-2021-3493](https://tryhackme.com/room/overlayfs)
  
- [ ] [🕵️ TryHackMe | Psycho Break](https://tryhackme.com/room/psychobreak)
  
- [ ] [🕵️ TryHackMe | Bounty Hacker](https://tryhackme.com/room/cowboyhacker)
  
- [ ] [🕵️ TryHackMe | Fowsniff CTF](https://tryhackme.com/room/ctf)

- [x] [🕵️ TryHackMe | RootMe](https://tryhackme.com/room/rrootme)

- [ ] [🕵️ TryHackMe | AttackerKB](https://tryhackme.com/room/attackerkb)

- [ ] [🕵️ TryHackMe | Pickle Rick](https://tryhackme.com/room/picklerick)

- [ ] [🕵️ TryHackMe | c4ptur3-th3-fl4g](https://tryhackme.com/room/c4ptur3th3fl4g)

- [ ] [🕵️ TryHackMe | Library](https://tryhackme.com/room/bsidesgtlibrary)

- [ ] [🕵️ TryHackMe | Thompson](https://tryhackme.com/room/bsidesgtthompson)

- [ ] [🕵️ TryHackMe | Simple CTF](https://tryhackme.com/room/easyctf)

- [ ] [🕵️ TryHackMe | LazyAdmin](https://tryhackme.com/room/lazyadmin)

- [ ] [🕵️ TryHackMe | Anonforce](https://tryhackme.com/room/bsidesgtanonforce)

- [ ] [🕵️ TryHackMe | Ignite](https://tryhackme.com/room/ignite)

- [ ] [🕵️ TryHackMe | Wgel CTF](https://tryhackme.com/room/wgelctf)

- [ ] [🕵️ TryHackMe | Kenobi](https://tryhackme.com/room/kenobi)

- [ ] [🕵️ TryHackMe | Dav](https://tryhackme.com/room/bsidesgtdav)

- [ ] [🕵️ TryHackMe | Ninja Skills](https://tryhackme.com/room/ninjaskills)

- [x] [🕵️ TryHackMe | Ice](https://tryhackme.com/room/ice)

- [ ] [🕵️ TryHackMe | Lian_Yu](https://tryhackme.com/room/lianyu)

- [ ] [🕵️ TryHackMe | The Cod Caper](https://tryhackme.com/room/thecodcaper)

- [ ] [🕵️ TryHackMe | Blaster](https://tryhackme.com/room/blaster)

- [ ] [🕵️ TryHackMe | Encryption - Crypto 101](https://tryhackme.com/room/encryptioncrypto101)

- [ ] [🕵️ TryHackMe | Brooklyn Nine Nine](https://tryhackme.com/room/brooklynninenine)

- [ ] [🕵️ TryHackMe | Year of the Rabbit](https://tryhackme.com/room/yearoftherabbit)

- [ ] [🕵️ TryHackMe | Jack-of-All-Trades](https://tryhackme.com/room/jackofalltrades)

- [ ] [🕵️ TryHackMe | Madness](https://tryhackme.com/room/madness)

- [ ] [🕵️ TryHackMe | KoTH Food CTF](https://tryhackme.com/room/kothfoodctf)

- [ ] [🕵️ TryHackMe | Easy Peasy](https://tryhackme.com/room/easypeasyctf)

- [ ] [🕵️ TryHackMe | Tony the Tiger](https://tryhackme.com/room/tonythetiger)

- [ ] [🕵️ TryHackMe | CTF collection Vol.1](https://tryhackme.com/room/ctfcollectionvol1)

- [ ] [🕵️ TryHackMe | Smag Grotto](https://tryhackme.com/room/smaggrotto)

- [ ] [🕵️ TryHackMe | Couch](https://tryhackme.com/room/couch)

- [ ] [🕵️ TryHackMe | Source](https://tryhackme.com/room/source)

- [ ] [🕵️ TryHackMe | Overpass](https://tryhackme.com/room/overpass)

- [ ] [🕵️ TryHackMe | Gotta Catch&#39;em All!](https://tryhackme.com/room/pokemon)

- [ ] [🕵️ TryHackMe | Bolt](https://tryhackme.com/room/bolt)

- [ ] [🕵️ TryHackMe | Overpass 2 - Hacked](https://tryhackme.com/room/overpass2hacked)

- [ ] [🕵️ TryHackMe | kiba](https://tryhackme.com/room/kiba)

- [ ] [🕵️ TryHackMe | Poster](https://tryhackme.com/room/poster)

- [ ] [🕵️ TryHackMe | Chocolate Factory](https://tryhackme.com/room/chocolatefactory)

- [ ] [🕵️ TryHackMe | Startup](https://tryhackme.com/room/startup)

- [ ] [🕵️ TryHackMe | Chill Hack](https://tryhackme.com/room/chillhack)

- [ ] [🕵️ TryHackMe | ColddBox: Easy](https://tryhackme.com/room/colddboxeasy)

- [ ] [🕵️ TryHackMe | GLITCH](https://tryhackme.com/room/glitch)

- [ ] [🕵️ TryHackMe | All in One](https://tryhackme.com/room/allinonemj)

- [ ] [🕵️ TryHackMe | Archangel](https://tryhackme.com/room/archangel)

- [ ] [🕵️ TryHackMe | Cyborg](https://tryhackme.com/room/cyborgt8)

- [ ] [🕵️ TryHackMe | Lunizz CTF](https://tryhackme.com/room/lunizzctfnd)

- [ ] [🕵️ TryHackMe | Badbyte](https://tryhackme.com/room/badbyte)

- [ ] [🕵️ TryHackMe | Team](https://tryhackme.com/room/teamcw)

- [ ] [🕵️ TryHackMe | VulnNet: Node](https://tryhackme.com/room/vulnnetnode)

- [ ] [🕵️ TryHackMe | VulnNet: Internal](https://tryhackme.com/room/vulnnetinternal)

- [ ] [🕵️ TryHackMe | Atlas](https://tryhackme.com/room/atlas)

- [ ] [🕵️ TryHackMe | VulnNet: Roasted](https://tryhackme.com/room/vulnnetroasted)

- [ ] [🕵️ TryHackMe | Cat Pictures](https://tryhackme.com/room/catpictures)

- [ ] [🕵️ TryHackMe | Mustacchio](https://tryhackme.com/room/mustacchio)

##### Medium CTF

- [ ] [🕵️ TryHackMe | Backtrack](https://tryhackme.com/room/backtrack)
  
- [ ] [🕵️ TryHackMe | Extracted](https://tryhackme.com/room/extractedroom)
  
- [ ] [🕵️ TryHackMe | The London Bridge](https://tryhackme.com/room/thelondonbridge)
  
- [ ] [🕵️ TryHackMe | Breakme](https://tryhackme.com/room/breakmenu)
  
- [x] [🕵️ TryHackMe | Block](https://tryhackme.com/room/blockroom)
  
- [ ] [🕵️ TryHackMe | APIWizards Breach](https://tryhackme.com/room/apiwizardsbreach)
  
- [ ] [🕵️ TryHackMe | New York Flankees](https://tryhackme.com/room/thenewyorkflankees)
  
- [ ] [🕵️ TryHackMe | Airplane](https://tryhackme.com/room/airplane)
  
- [ ] [🕵️ TryHackMe | Profiles](https://tryhackme.com/room/profilesroom)
  
- [ ] [🕵️ TryHackMe | Clocky](https://tryhackme.com/room/clocky)
  
- [ ] [🕵️ TryHackMe | Hack Smarter Security](https://tryhackme.com/room/hacksmartersecurity)
  
- [ ] [🕵️ TryHackMe | Kitty](https://tryhackme.com/room/kitty)
  
- [ ] [🕵️ TryHackMe | Umbrella](https://tryhackme.com/room/umbrella)
  
- [ ] [🕵️ TryHackMe | AVenger](https://tryhackme.com/room/avenger)
  
- [ ] [🕵️ TryHackMe | WhyHackMe](https://tryhackme.com/room/whyhackme)
  
- [ ] [🕵️ TryHackMe | Stealth](https://tryhackme.com/room/stealth)
  
- [ ] [🕵️ TryHackMe | Hunt Me I: Payment Collectors](https://tryhackme.com/room/paymentcollectors)

- [ ] [🕵️ TryHackMe | Hunt Me II: Typo Squatters](https://tryhackme.com/room/typosquatters)

- [ ] [🕵️ TryHackMe | Athena](https://tryhackme.com/room/4th3n4)

- [ ] [🕵️ TryHackMe | Crylo](https://tryhackme.com/room/crylo4a)

- [ ] [🕵️ TryHackMe | Forgotten Implant](https://tryhackme.com/room/forgottenimplant)

- [ ] [🕵️ TryHackMe | Race Conditions](https://tryhackme.com/room/raceconditions)

- [ ] [🕵️ TryHackMe | Weasel](https://tryhackme.com/room/weasel)

- [ ] [🕵️ TryHackMe | Prioritise](https://tryhackme.com/room/prioritise)

- [ ] [🕵️ TryHackMe | Boogeyman 1](https://tryhackme.com/room/boogeyman1)

- [x] [🕵️ TryHackMe | Mr Robot CTF](https://tryhackme.com/room/mrrobot)

- [ ] [🕵️ TryHackMe | Unattended](https://tryhackme.com/room/unattended)

- [ ] [🕵️ TryHackMe | GoldenEye](https://tryhackme.com/room/goldeneye)

- [ ] [🕵️ TryHackMe | StuxCTF](https://tryhackme.com/room/stuxctf)

- [ ] [🕵️ TryHackMe | Boiler CTF](https://tryhackme.com/room/boilerctf2)

- [ ] [🕵️ TryHackMe | HA Joker CTF](https://tryhackme.com/room/jokerctf)

- [ ] [🕵️ TryHackMe | Biohazard](https://tryhackme.com/room/biohazard)

- [ ] [🕵️ TryHackMe | Break it](https://tryhackme.com/room/breakit)

- [ ] [🕵️ TryHackMe | Willow](https://tryhackme.com/room/willow)

- [ ] [🕵️ TryHackMe | The Marketplace](https://tryhackme.com/room/marketplace)

- [x] [🕵️ TryHackMe | Nax](https://tryhackme.com/room/nax)

- [ ] [🕵️ TryHackMe | Mindgames](https://tryhackme.com/room/mindgames)

- [ ] [🕵️ TryHackMe | Anonymous](https://tryhackme.com/room/anonymous)

- [ ] [🕵️ TryHackMe | Blog](https://tryhackme.com/room/blog)

- [ ] [🕵️ TryHackMe | Wonderland](https://tryhackme.com/room/wonderland)

- [ ] [🕵️ TryHackMe | 0day](https://tryhackme.com/room/0day)

- [ ] [🕵️ TryHackMe | Develpy](https://tryhackme.com/room/bsidesgtdevelpy)

- [ ] [🕵️ TryHackMe | CTF collection Vol.2](https://tryhackme.com/room/ctfcollectionvol2)

- [ ] [🕵️ TryHackMe | CMesS](https://tryhackme.com/room/cmess)

- [ ] [🕵️ TryHackMe | Deja Vu](https://tryhackme.com/room/dejavu)

- [ ] [🕵️ TryHackMe | hackerNote](https://tryhackme.com/room/hackernote)

- [x] [🕵️ TryHackMe | dogcat](https://tryhackme.com/room/dogcat)

- [ ] [🕵️ TryHackMe | ConvertMyVideo](https://tryhackme.com/room/convertmyvideo)

- [ ] [🕵️ TryHackMe | KoTH Hackers](https://tryhackme.com/room/kothhackers)

- [ ] [🕵️ TryHackMe | Revenge](https://tryhackme.com/room/revenge)

- [ ] [🕵️ TryHackMe | harder](https://tryhackme.com/room/harder)

- [ ] [🕵️ TryHackMe | HaskHell](https://tryhackme.com/room/haskhell)

- [ ] [🕵️ TryHackMe | Undiscovered](https://tryhackme.com/room/undiscoveredup)

- [ ] [🕵️ TryHackMe | Break Out The Cage](https://tryhackme.com/room/breakoutthecage1)

- [ ] [🕵️ TryHackMe | The Impossible Challenge](https://tryhackme.com/room/theimpossiblechallenge)

- [ ] [🕵️ TryHackMe | Looking Glass](https://tryhackme.com/room/lookingglass)

- [ ] [🕵️ TryHackMe | Recovery](https://tryhackme.com/room/recovery)

- [ ] [🕵️ TryHackMe | Relevant](https://tryhackme.com/room/relevant)

- [ ] [🕵️ TryHackMe | Ghizer](https://tryhackme.com/room/ghizerctf)

- [ ] [🕵️ TryHackMe | Mnemonic](https://tryhackme.com/room/mnemonic)

- [ ] [🕵️ TryHackMe | WWBuddy](https://tryhackme.com/room/wwbuddy)

- [ ] [🕵️ TryHackMe | The Blob Blog](https://tryhackme.com/room/theblobblog)

- [ ] [🕵️ TryHackMe | Cooctus Stories](https://tryhackme.com/room/cooctusadventures)

- [ ] [🕵️ TryHackMe | One Piece](https://tryhackme.com/room/ctfonepiece65)

- [ ] [🕵️ TryHackMe | toc2](https://tryhackme.com/room/toc2)

- [ ] [🕵️ TryHackMe | NerdHerd](https://tryhackme.com/room/nerdherd)

- [ ] [🕵️ TryHackMe | Kubernetes Chall TDI 2020](https://tryhackme.com/room/kuberneteschalltdi2020)

- [ ] [🕵️ TryHackMe | The Server From Hell](https://tryhackme.com/room/theserverfromhell)

- [ ] [🕵️ TryHackMe | Jacob the Boss](https://tryhackme.com/room/jacobtheboss)

- [ ] [🕵️ TryHackMe | Unbaked Pie](https://tryhackme.com/room/unbakedpie)

- [ ] [🕵️ TryHackMe | Bookstore](https://tryhackme.com/room/bookstoreoc)

- [ ] [🕵️ TryHackMe | Overpass 3 - Hosting](https://tryhackme.com/room/overpass3hosting)

- [ ] [🕵️ TryHackMe | battery](https://tryhackme.com/room/battery)

- [ ] [🕵️ TryHackMe | Madeye&#39;s Castle](https://tryhackme.com/room/madeyescastle)

- [ ] [🕵️ TryHackMe | En-pass](https://tryhackme.com/room/enpass)

- [ ] [🕵️ TryHackMe | Sustah](https://tryhackme.com/room/sustah)

- [ ] [🕵️ TryHackMe | KaffeeSec - SoMeSINT](https://tryhackme.com/room/somesint)

- [ ] [🕵️ TryHackMe | Tokyo Ghoul](https://tryhackme.com/room/tokyoghoul666)

- [ ] [🕵️ TryHackMe | Watcher](https://tryhackme.com/room/watcher)

- [ ] [🕵️ TryHackMe | broker](https://tryhackme.com/room/broker)

- [ ] [🕵️ TryHackMe | Inferno](https://tryhackme.com/room/inferno)

- [ ] [🕵️ TryHackMe | VulnNet: dotpy](https://tryhackme.com/room/vulnnetdotpy)

- [ ] [🕵️ TryHackMe | Wekor](https://tryhackme.com/room/wekorra)

- [ ] [🕵️ TryHackMe | pyLon](https://tryhackme.com/room/pylonzf)

- [ ] [🕵️ TryHackMe | The Great Escape](https://tryhackme.com/room/thegreatescape)

- [ ] [🕵️ TryHackMe | SafeZone](https://tryhackme.com/room/safezone)

- [ ] [🕵️ TryHackMe | NahamStore](https://tryhackme.com/room/nahamstore)

- [ ] [🕵️ TryHackMe | Sweettooth Inc.](https://tryhackme.com/room/sweettoothinc)

- [ ] [🕵️ TryHackMe | Red Team OPSEC](https://tryhackme.com/room/opsec)

- [ ] [🕵️ TryHackMe | CMSpit](https://tryhackme.com/room/cmspit)

- [ ] [🕵️ TryHackMe | Super-Spam](https://tryhackme.com/room/superspamr)

- [ ] [🕵️ TryHackMe | That&#39;s The Ticket](https://tryhackme.com/room/thatstheticket)

- [ ] [🕵️ TryHackMe | Debug](https://tryhackme.com/room/debug)

- [ ] [🕵️ TryHackMe | Red Stone One Carat](https://tryhackme.com/room/redstoneonecarat)

- [ ] [🕵️ TryHackMe | Cold VVars](https://tryhackme.com/room/coldvvars)

- [ ] [🕵️ TryHackMe | Metamorphosis](https://tryhackme.com/room/metamorphosis)

- [ ] [🕵️ TryHackMe | SQHell](https://tryhackme.com/room/sqhell)

- [ ] [🕵️ TryHackMe | Fortress](https://tryhackme.com/room/fortress)

- [ ] [🕵️ TryHackMe | CyberCrafted](https://tryhackme.com/room/cybercrafted)

- [ ] [🕵️ TryHackMe | Road](https://tryhackme.com/room/road)

##### Hard CTF

- [ ] [🕵️ TryHackMe | CERTain Doom](https://tryhackme.com/room/certaindoom)
  
- [ ] [🕵️ TryHackMe | Capture Returns](https://tryhackme.com/room/capturereturns)
  
- [ ] [🕵️ TryHackMe | Chrome](https://tryhackme.com/room/chrome)
  
- [ ] [🕵️ TryHackMe | Reset](https://tryhackme.com/room/resetui)

- [ ] [🕵️ TryHackMe | Motunui](https://tryhackme.com/room/motunui)

- [ ] [🕵️ TryHackMe | Spring](https://tryhackme.com/room/spring)

- [ ] [🕵️ TryHackMe | Brainpan 1](https://tryhackme.com/room/brainpan)

- [ ] [🕵️ TryHackMe | Borderlands](https://tryhackme.com/room/borderlands)

- [ ] [🕵️ TryHackMe | hc0n Christmas CTF](https://tryhackme.com/room/hc0nchristmasctf)

- [ ] [🕵️ TryHackMe | Daily Bugle](https://tryhackme.com/room/dailybugle)

- [ ] [🕵️ TryHackMe | Retro](https://tryhackme.com/room/retro)

- [ ] [🕵️ TryHackMe | Jeff](https://tryhackme.com/room/jeff)

- [ ] [🕵️ TryHackMe | Racetrack Bank](https://tryhackme.com/room/racetrackbank)

- [ ] [🕵️ TryHackMe | Dave&#39;s Blog](https://tryhackme.com/room/davesblog)

- [ ] [🕵️ TryHackMe | CherryBlossom](https://tryhackme.com/room/cherryblossom)

- [ ] [🕵️ TryHackMe | CCT2019](https://tryhackme.com/room/cct2019)

- [ ] [🕵️ TryHackMe | Iron Corp](https://tryhackme.com/room/ironcorp)

- [ ] [🕵️ TryHackMe | Carpe Diem 1](https://tryhackme.com/room/carpediem1)

- [ ] [🕵️ TryHackMe | Ra](https://tryhackme.com/room/ra)

- [ ] [🕵️ TryHackMe | Year of the Fox](https://tryhackme.com/room/yotf)

- [ ] [🕵️ TryHackMe | For Business Reasons](https://tryhackme.com/room/forbusinessreasons)

- [ ] [🕵️ TryHackMe | Anonymous Playground](https://tryhackme.com/room/anonymousplayground)

- [ ] [🕵️ TryHackMe | Misguided Ghosts](https://tryhackme.com/room/misguidedghosts)

- [ ] [🕵️ TryHackMe | Theseus](https://tryhackme.com/room/theseus)

- [ ] [🕵️ TryHackMe | Internal](https://tryhackme.com/room/internal)

- [ ] [🕵️ TryHackMe | Year of the Dog](https://tryhackme.com/room/yearofthedog)

- [ ] [🕵️ TryHackMe | You&#39;re in a cave](https://tryhackme.com/room/inacave)

- [ ] [🕵️ TryHackMe | Year of the Owl](https://tryhackme.com/room/yearoftheowl)

- [ ] [🕵️ TryHackMe | Year of the Pig](https://tryhackme.com/room/yearofthepig)

- [ ] [🕵️ TryHackMe | envizon](https://tryhackme.com/room/envizon)

- [ ] [🕵️ TryHackMe | GameBuzz](https://tryhackme.com/room/gamebuzz)

- [ ] [🕵️ TryHackMe | Fusion Corp](https://tryhackme.com/room/fusioncorp)

- [ ] [🕵️ TryHackMe | Crocc Crew](https://tryhackme.com/room/crocccrew)

- [ ] [🕵️ TryHackMe | Uranium CTF](https://tryhackme.com/room/uranium)

- [ ] [🕵️ TryHackMe | Year of the Jellyfish](https://tryhackme.com/room/yearofthejellyfish)

- [ ] [🕵️ TryHackMe | Rocket](https://tryhackme.com/room/rocket)

- [ ] [🕵️ TryHackMe | Squid Game](https://tryhackme.com/room/squidgameroom)

- [ ] [🕵️ TryHackMe | EnterPrize](https://tryhackme.com/room/enterprize)

- [ ] [🕵️ TryHackMe | Different CTF](https://tryhackme.com/room/adana)

- [ ] [🕵️ TryHackMe | VulnNet: dotjar](https://tryhackme.com/room/vulnnetdotjar)

- [ ] [🕵️ TryHackMe | M4tr1x: Exit Denied](https://tryhackme.com/room/m4tr1xexitdenied)

- [ ] [🕵️ TryHackMe | Shaker](https://tryhackme.com/room/shaker)

##### Insane CTF

- [x] [🕵️ TryHackMe | Frosteau Busy with Vim](https://tryhackme.com/room/busyvimfrosteau)

##### Misc

- [ ] [🕵️ TryHackMe | PaperCut: CVE-2023-27350](https://tryhackme.com/room/papercut)
  
- [ ] [🕵️ TryHackMe | Moniker Link (CVE-2024-21413)](https://tryhackme.com/room/monikerlink)
  
- [ ] [🕵️ TryHackMe | Confluence CVE-2023-22515](https://tryhackme.com/room/confluence202322515)

- [ ] [🕵️ TryHackMe | GitLab CVE-2023-7028](https://tryhackme.com/room/gitlabcve20237028)

- [ ] [🕵️ TryHackMe | Cactus](https://tryhackme.com/room/cactus)

- [ ] [🕵️ TryHackMe | Looney Tunables ](https://tryhackme.com/room/looneytunes)

- [ ] [🕵️ TryHackMe | Threat Intel & Containment](https://tryhackme.com/room/intelcreationandcontainment)
      
- [ ] [🕵️ TryHackMe | CVE-2023-38408](https://tryhackme.com/room/cve202338408)

- [ ] [🕵️ TryHackMe | Introduction to Django](https://tryhackme.com/room/django)

- [ ] [🕵️ TryHackMe | Git Happens](https://tryhackme.com/room/githappens)

- [ ] [🕵️ TryHackMe | Meltdown Explained](https://tryhackme.com/room/meltdownexplained)

- [ ] [🕵️ TryHackMe | Splunk](https://tryhackme.com/room/bpsplunk)

- [ ] [🕵️ TryHackMe | Linux Backdoors](https://tryhackme.com/room/linuxbackdoors)

- [ ] [🕵️ TryHackMe | Jupyter 101](https://tryhackme.com/room/jupyter101)

- [ ] [🕵️ TryHackMe | Geolocating Images](https://tryhackme.com/room/geolocatingimages)

- [ ] [🕵️ TryHackMe | Tor](https://tryhackme.com/room/torforbeginners)

- [ ] [🕵️ TryHackMe | tomghost](https://tryhackme.com/room/tomghost)

- [ ] [🕵️ TryHackMe | DLL HIJACKING](https://tryhackme.com/room/dllhijacking)

- [ ] [🕵️ TryHackMe | Intro to IoT Pentesting](https://tryhackme.com/room/iotintro)

- [ ] [🕵️ TryHackMe | Attacking ICS Plant #1](https://tryhackme.com/room/attackingics1)

- [ ] [🕵️ TryHackMe | Attacking ICS Plant #2](https://tryhackme.com/room/attackingics2)

- [ ] [🕵️ TryHackMe | Printer Hacking 101](https://tryhackme.com/room/printerhacking101)

- [ ] [🕵️ TryHackMe | DNS Manipulation](https://tryhackme.com/room/dnsmanipulation)

- [ ] [🕵️ TryHackMe | Introduction to Flask](https://tryhackme.com/room/flask)

- [ ] [🕵️ TryHackMe | MITRE](https://tryhackme.com/room/mitre)

- [ ] [🕵️ TryHackMe | magician](https://tryhackme.com/room/magician)

- [ ] [🕵️ TryHackMe | JPGChat](https://tryhackme.com/room/jpgchat)

- [ ] [🕵️ TryHackMe | Baron Samedit](https://tryhackme.com/room/sudovulnssamedit)

- [ ] [🕵️ TryHackMe | CVE-2021-41773/42013](https://tryhackme.com/room/cve202141773)

- [ ] [🕵️ TryHackMe | Binary Heaven](https://tryhackme.com/room/binaryheaven)

- [ ] [🕵️ TryHackMe | Git and Crumpets](https://tryhackme.com/room/gitandcrumpets)

- [ ] [🕵️ TryHackMe | Polkit: CVE-2021-3560](https://tryhackme.com/room/polkit)

- [ ] [🕵️ TryHackMe | Hip Flask](https://tryhackme.com/room/hipflask)

- [ ] [🕵️ TryHackMe | Bypass Disable Functions](https://tryhackme.com/room/bypassdisablefunctions)

- [ ] [🕵️ TryHackMe | Wordpress: CVE-2021-29447](https://tryhackme.com/room/wordpresscve202129447)

- [ ] [🕵️ TryHackMe | Linux Function Hooking](https://tryhackme.com/room/linuxfunctionhooking)

- [ ] [🕵️ TryHackMe | REvil Corp](https://tryhackme.com/room/revilcorp)

- [ ] [🕵️ TryHackMe | Sudo Buffer Overflow](https://tryhackme.com/room/sudovulnsbof)

- [ ] [🕵️ TryHackMe | Sudo Security Bypass](https://tryhackme.com/room/sudovulnsbypass)

- [ ] [🕵️ TryHackMe | Solar, exploiting log4j](https://tryhackme.com/room/solar)

- [ ] [🕵️ TryHackMe | Conti](https://tryhackme.com/room/contiransomwarehgh)

- [ ] [🕵️ TryHackMe | Dirty Pipe: CVE-2022-0847](https://tryhackme.com/room/dirtypipe)

- [ ] [🕵️ TryHackMe | The find command](https://tryhackme.com/room/thefindcommand)

##### Special Events

- [ ] [🕵️ TryHackMe | 25 Days of Cyber Security](https://tryhackme.com/room/learncyberin25days)

- [ ] [🕵️ TryHackMe | Advent of Cyber 1 [2019]](https://tryhackme.com/room/25daysofchristmas)

- [ ] [🕵️ TryHackMe | Advent of Cyber 2 [2020]](https://tryhackme.com/room/adventofcyber2)

- [ ] [🕵️ TryHackMe | Advent of Cyber 3 (2021)](https://tryhackme.com/room/adventofcyber3)

- [ ] [🕵️ TryHackMe | Advent of Cyber 2022](https://tryhackme.com/room/adventofcyber4)

- [x] [🕵️ TryHackMe | Advent of Cyber 2023](https://tryhackme.com/room/adventofcyber2023)

- [ ] [🕵️ TryHackMe | Advent of Cyber 2024](https://tryhackme.com/room/adventofcyber2024)

- [ ] [🕵️ TryHackMe | Advent of Cyber '23 Side Quest](https://tryhackme.com/room/adventofcyber23sidequest)

- [ ] [🕵️ TryHackMe | Cyber Scotland 2021](https://tryhackme.com/room/cyberweek2021)

- [ ] [🕵️ TryHackMe | Hacker of the Hill #1](https://tryhackme.com/room/hackerofthehill)

- [ ] [🕵️ TryHackMe | Learn and win prizes](https://tryhackme.com/room/tickets1)

- [ ] [🕵️ TryHackMe | Learn and win prizes #2](https://tryhackme.com/room/tickets2)


- [x] [🕵️ TryHackMe | Microservices Architectures](https://tryhackme.com/room/microservicearchitectures)
  
- [x] [🕵️ TryHackMe | NoSQL Injection](https://tryhackme.com/room/nosqlinjectiontutorial)
  
- [ ] [🕵️ TryHackMe | Advanced SQL Injection](https://tryhackme.com/room/advancedsqlinjection)
  
- [x] [🕵️ TryHackMe | XSS](https://tryhackme.com/room/axss)
  
- [ ] [🕵️ TryHackMe | CSRF](https://tryhackme.com/room/csrfV2)
  
- [ ] [🕵️ TryHackMe | File Inclusion, Path Traversal](https://tryhackme.com/room/filepathtraversal)
  
- [ ] [🕵️ TryHackMe | HTTP Request Smuggling](https://tryhackme.com/room/httprequestsmuggling)
  
- [ ] [🕵️ TryHackMe | HTTP/2 Request Smuggling](https://tryhackme.com/room/http2requestsmuggling)

- [ ] [🕵️ TryHackMe | SSRF](https://tryhackme.com/room/ssrfhr)

- [x] [🕵️ TryHackMe | OWASP Broken Access Control](https://tryhackme.com/room/owaspbrokenaccesscontrol)

- [ ] [🕵️ TryHackMe | HTTP in detail](https://tryhackme.com/room/webfundamentals)

- [ ] [🕵️ TryHackMe | Vulnerabilities 101](https://tryhackme.com/room/vulnerabilities101)

- [ ] [🕵️ TryHackMe | Walking An Application](https://tryhackme.com/room/walkinganapplication)

- [ ] [🕵️ TryHackMe | OWASP Top 10 - 2021](https://tryhackme.com/room/owasptop102021)

- [ ] [🕵️ TryHackMe | OWASP Top 10](https://tryhackme.com/room/owasptop10)

- [ ] [🕵️ TryHackMe | OWASP Juice Shop](https://tryhackme.com/room/owaspjuiceshop)

- [ ] [🕵️ TryHackMe | OWASP Mutillidae II](https://tryhackme.com/room/owaspmutillidae)

- [ ] [🕵️ TryHackMe | WebGOAT](https://tryhackme.com/room/webgoat)

- [x] [🕵️ TryHackMe | Web Application Security](https://tryhackme.com/room/introwebapplicationsecurity)

- [ ] [🕵️ TryHackMe | DVWA](https://tryhackme.com/room/dvwa)

- [ ] [🕵️ TryHackMe | VulnNet](https://tryhackme.com/room/vulnnet1)

- [ ] [🕵️ TryHackMe | Juicy Details](https://tryhackme.com/room/juicydetails)

- [ ] [🕵️ TryHackMe | Vulnversity](https://tryhackme.com/room/vulnversity)

- [ ] [🕵️ TryHackMe | SQL Injection Lab](https://tryhackme.com/room/sqlilab)

- [ ] [🕵️ TryHackMe | SSTI](https://tryhackme.com/room/learnssti)

- [ ] [🕵️ TryHackMe | SQL Injection](https://tryhackme.com/room/sqlinjectionlm)

- [ ] [🕵️ TryHackMe | Basic Pentesting](https://tryhackme.com/room/basicpentestingjt)

- [ ] [🕵️ TryHackMe | Ignite](https://tryhackme.com/room/ignite)

- [ ] [🕵️ TryHackMe | Overpass](https://tryhackme.com/room/overpass)

- [ ] [🕵️ TryHackMe | Year of the Rabbit](https://tryhackme.com/room/yearoftherabbit)

- [ ] [🕵️ TryHackMe | Develpy](https://tryhackme.com/room/bsidesgtdevelpy)

- [ ] [🕵️ TryHackMe | Jack-of-All-Trades](https://tryhackme.com/room/jackofalltrades)

- [ ] [🕵️ TryHackMe | Bolt](https://tryhackme.com/room/bolt)

- **[OverTheWire](https://overthewire.org/)** - War games for different skill levels
- **[DVWA](https://github.com/digininja/DVWA)** - Deliberately vulnerable web application

MORE:

- **[Itsecgames](http://www.itsecgames.com/)** - bWAPP or buggy web app is a deliberately insecure web application.
- **[Hackthissite](https://www.hackthissite.org/)** - A site which provides challenges, CTFs, and more to improve your hacking skills.
- **[Defend the Web](https://defendtheweb.net/)** - Defend the Web is an interactive security platform where you can learn and challenge your skills.
- **[PicoCTF](https://picoctf.org/)** - Provides you with fun CTF challenges of varying levels of difficulty to practice on.

### Intermediate
- **[HackTheBox](https://www.hackthebox.eu/)** - Real-world penetration testing labs
- **[PortSwigger Web Security Academy](https://portswigger.net/web-security)** - Free web application security training
- **[VulnHub](https://www.vulnhub.com/)** - Vulnerable virtual machines

MORE:

- **[Vulnhub](https://www.vulnhub.com/)** - Has a lot of VMs to play with. Some are beginner friendly, some aren't.
- **[Root-me](https://www.root-me.org/)** - Another website which hosts challenges to test your hacking skills.

### Advanced
- **[Offensive Security Labs](https://www.offensive-security.com/)** - Professional-grade labs
- **[SANS NetWars](https://www.sans.org/netwars/)** - Competitive cyber security exercises
- **[Cybrary](https://www.cybrary.it/)** - Professional cybersecurity training

MORE:

- **[Ctftime](https://ctftime.org/)** - The de facto website for everything CTF related.

---

<a id="certification-roadmap"></a>
## 📜 Certification Roadmap

### Entry Level
1. **CompTIA Security+** - General security foundation
2. **CompTIA PenTest+** - Entry-level penetration testing

### Professional Level
1. **OSCP (Offensive Security Certified Professional)** - Industry standard
2. **CEH (Certified Ethical Hacker)** - Vendor-neutral certification
3. **GCIH (GIAC Certified Incident Handler)** - Incident response focus

### Expert Level
1. **OSEP (Offensive Security Experienced Penetrator)** - Advanced penetration testing
2. **GPEN (GIAC Penetration Tester)** - Advanced network penetration testing
3. **OSCE (Offensive Security Certified Expert)** - Expert-level exploitation

---

<a id="tools-checklist"></a>
## 🛠️ Tools Checklist

### Essential Tools (Master These First)
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


### Tools by category

A more complete list of tools can be found on [Kali Linux official website](https://tools.kali.org/tools-listing).

#### :male_detective: Information Gathering

Information Gathering tools allows you to collect host metadata about services and users. Check informations about a domain, IP address, phone number or an email address.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [theHarvester](https://github.com/laramies/theHarvester)      | **Python** | `Linux/Windows/macOS` | E-mails, subdomains and names Harvester. |
| [CTFR](https://github.com/UnaPibaGeek/ctfr)      | **Python** | `Linux/Windows/macOS` | Abusing Certificate Transparency logs for getting HTTPS websites subdomains. |
| [Sn1per](https://github.com/1N3/Sn1per)      | **bash** | `Linux/macOS` | Automated Pentest Recon Scanner. |
| [RED Hawk](https://github.com/Tuhinshubhra/RED_HAWK)      | **PHP** | `Linux/Windows/macOS` | All in one tool for Information Gathering, Vulnerability Scanning and Crawling. A must have tool for all penetration testers. |
| [Infoga](https://github.com/m4ll0k/Infoga)      | **Python** | `Linux/Windows/macOS` | Email Information Gathering. |
| [KnockMail](https://github.com/4w4k3/KnockMail)      | **Python** | `Linux/Windows/macOS` | Check if email address exists. |
| [a2sv](https://github.com/hahwul/a2sv)      | **Python** | `Linux/Windows/macOS` | Auto Scanning to SSL Vulnerability. |
| [Wfuzz](https://github.com/xmendez/wfuzz)      | **Python** | `Linux/Windows/macOS` | Web application fuzzer. |
| [Nmap](https://github.com/nmap/nmap)      | **C/C++** | `Linux/Windows/macOS` | A very common tool. Network host, vuln and port detector. |
| [PhoneInfoga](https://github.com/sundowndev/PhoneInfoga)      | **Go** | `Linux/macOS` | An OSINT framework for phone numbers. |

#### :lock: Password Attacks

Crack passwords and create wordlists.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [John the Ripper](https://github.com/magnumripper/JohnTheRipper)      | **C** | `Linux/Windows/macOS` | John the Ripper is a fast password cracker. |
| [hashcat](https://github.com/hashcat/hashcat)      | **C** | `Linux/Windows/macOS` | World's fastest and most advanced password recovery utility. |
| [Hydra](https://github.com/vanhauser-thc/thc-hydra)      | **C** | `Linux/Windows/macOS` | Parallelized login cracker which supports numerous protocols to attack. |
| [ophcrack](https://gitlab.com/objectifsecurite/ophcrack)      | **C++** | `Linux/Windows/macOS` | Windows password cracker based on rainbow tables. |
| [Ncrack](https://github.com/nmap/ncrack)      | **C** | `Linux/Windows/macOS` | High-speed network authentication cracking tool. |
| [WGen](https://github.com/agusmakmun/Python-Wordlist-Generator)      | **Python** | `Linux/Windows/macOS` | Create awesome wordlists with Python. |
| [SSH Auditor](https://github.com/ncsa/ssh-auditor)      | **Go** | `Linux/macOS` | The best way to scan for weak ssh passwords on your network. |

###### :memo: Wordlists

| Tool        | Description    |
| ----------- |----------------|
| [Probable Wordlist](https://github.com/berzerk0/Probable-Wordlists)      | Wordlists sorted by probability originally created for password generation and testing. |

#### :globe_with_meridians: Wireless Testing

Used for intrusion detection and wifi attacks.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [Aircrack](https://github.com/aircrack-ng/aircrack-ng)      | **C** | `Linux/Windows/macOS` | WiFi security auditing tools suite. |
| [bettercap](https://github.com/bettercap/bettercap)      | **Go** | `Linux/Windows/macOS/Android` | bettercap is the Swiss army knife for network attacks and monitoring. |
| [WiFi Pumpkin](https://github.com/P0cL4bs/WiFi-Pumpkin)      | **Python** | `Linux/Windows/macOS/Android` | Framework for Rogue Wi-Fi Access Point Attack. |
| [Airgeddon](https://github.com/v1s1t0r1sh3r3/airgeddon)      | **Shell** | `Linux/Windows/macOS` | This is a multi-use bash script for Linux systems to audit wireless networks. |
| [Airbash](https://github.com/tehw0lf/airbash)      | **C** | `Linux/Windows/macOS` | A POSIX-compliant, fully automated WPA PSK handshake capture script aimed at penetration testing. |

#### :wrench: Exploitation Tools

Acesss systems and data with service-oriented exploits.

| Tool                                                    | Language   | Support               | Description                                                  |
| ------------------------------------------------------- | ---------- | --------------------- | ------------------------------------------------------------ |
| [SQLmap](https://github.com/sqlmapproject/sqlmap)       | **Python** | `Linux/Windows/macOS` | Automatic SQL injection and database takeover tool.          |
| [XSStrike](https://github.com/UltimateHackers/XSStrike) | **Python** | `Linux/Windows/macOS` | Advanced XSS detection and exploitation suite.               |
| [Commix](https://github.com/commixproject/commix)       | **Python** | `Linux/Windows/macOS` | Automated All-in-One OS command injection and exploitation tool.￼ |
| [Nuclei](https://github.com/projectdiscovery/nuclei)    | **Go**     | `Linux/Windows/macOS` | Fast and customisable vulnerability scanner based on simple YAML based DSL. |

#### :busts_in_silhouette: Sniffing & Spoofing

Listen to network traffic or fake a network entity.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [Wireshark](https://www.wireshark.org)      | **C/C++** | `Linux/Windows/macOS` | Wireshark is a network protocol analyzer. |
| [WiFi Pumpkin](https://github.com/P0cL4bs/WiFi-Pumpkin)      | **Python** | `Linux/Windows/macOS/Android` | Framework for Rogue Wi-Fi Access Point Attack. |
| [Zarp](https://github.com/hatRiot/zarp)      | **Python** | `Linux/Windows/macOS` | A free network attack framework. |

#### :rocket: Web Hacking

Exploit popular CMSs that are hosted online.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [WPScan](https://github.com/wpscanteam/wpscan)      | **Ruby** | `Linux/Windows/macOS` | WPScan is a black box WordPress vulnerability scanner. |
| [Droopescan](https://github.com/droope/droopescan)      | **Python** | `Linux/Windows/macOS` | A plugin-based scanner to identify issues with several CMSs, mainly Drupal & Silverstripe. |
| [Joomscan](https://github.com/rezasp/joomscan)      | **Perl** | `Linux/Windows/macOS` | Joomla Vulnerability Scanner. |
| [Drupwn](https://github.com/immunIT/drupwn)      | **Python** | `Linux/Windows/macOS` | Drupal Security Scanner to perform enumerations on Drupal-based web applications. |
| [CMSeek](https://github.com/Tuhinshubhra/CMSeek)      | **Python** | `Linux/Windows/macOS` | CMS Detection and Exploitation suite - Scan WordPress, Joomla, Drupal and 130 other CMSs. |

#### :tada: Post Exploitation

Exploits for after you have already gained access.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [TheFatRat](https://github.com/Screetsec/TheFatRat)      | **C** | `Linux/Windows/macOS` | Easy tool to generate backdoor and easy tool to post exploitation attack like browser attack, dll. |

#### :package: Frameworks

Frameworks are packs of pen testing tools with custom shell navigation and documentation.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [Operative Framework](https://github.com/graniet/operative-framework)      | **Python** | `Linux/Windows/macOS` | Framework based on fingerprint action, this tool is used for get information on a website or a enterprise target with multiple modules. |
| [Metasploit](https://github.com/rapid7/metasploit-framework)      | **Ruby** | `Linux/Windows/macOS` | A penetration testing framework for ethical hackers. |
| [cSploit](https://github.com/cSploit/android)      | **Java** | `Android` | The most complete and advanced IT security professional toolkit on Android. |
| [radare2](https://github.com/radare/radare2)      | **C** | `Linux/Windows/macOS/Android` | Unix-like reverse engineering framework and commandline tools. |
| [Wifiphisher](https://github.com/wifiphisher/wifiphisher)      | **Python** | `Linux` | The Rogue Access Point Framework. |
| [Beef](https://github.com/beefproject/beef)      | **Javascript** | `Linux/Windows/macOS` | The Browser Exploitation Framework. It is a penetration testing tool that focuses on the web browser. |
| [Mobile Security Framework (MobSF)](https://github.com/MobSF/Mobile-Security-Framework-MobSF)      | **Python** | `Linux/Windows/macOS` | Mobile Security Framework (MobSF) is an automated, all-in-one mobile application (Android/iOS/Windows) pen-testing, malware analysis and security assessment framework capable of performing static and dynamic analysis. |
| [Burp Suite](https://portswigger.net/burp)      | **Java** | `Linux/Windows/macOS` | Burp Suite is a leading range of cybersecurity tools, brought to you by PortSwigger. We believe in giving our users a competitive advantage through superior research. **This tool is not free and open source** |


---

<a id="resources"></a>
## 📚 Resources

### Books (Essential Reading)
- **"The Web Application Hacker's Handbook"** by Dafydd Stuttard
- **"The Hacker Playbook 3"** by Peter Kim
- **"Penetration Testing: A Hands-On Introduction to Hacking"** by Georgia Weidman
- **"Black Hat Python"** by Justin Seitz
- **"The Shellcoder's Handbook"** by Chris Anley

### Blogs & Websites
- [OWASP](https://owasp.org/) - Web application security
- [Null Byte](https://null-byte.wonderhowto.com/) - Hacking tutorials
- [Pentester Academy](https://www.pentesteracademy.com/) - Advanced courses
- [IppSec YouTube Channel](https://www.youtube.com/channel/UCa6eh7gCkpPo5XXUDfygQQA) - HackTheBox walkthroughs

### Podcasts
- **Darknet Diaries** - Security stories and case studies
- **Risky Business** - Weekly security news
- **The Secure Developer** - Application security focus

---

<a id="community"></a>
## 👥 Community

### Discord Servers
- **TryHackMe Official**
- **HackTheBox Official**
- **The Many Hats Club**
- [0Day.rocks on discord](https://discord.gg/WmYzJfD) Discord server about the 0day.rocks blog for technical and general InfoSec/Cyber discussions & latest news.

### Reddit Communities
- r/NetSecStudents - Learning and career advice
- r/AskNetsec - Professional questions
- r/HowToHack - Technical discussions
- [Reddit/hacking](https://www.reddit.com/r/hacking) Discuss about hacking and web security.

### Local Groups
- **OWASP Local Chapters**
- **2600 Meetings**
- **BSides Conferences**

---

## 📈 Progress Tracking

### Monthly Goals Checklist
- [ ] **Month 1**: Complete Phase 1 fundamentals
- [ ] **Month 2**: Web application security basics
- [ ] **Month 3**: Network penetration testing basics
- [ ] **Month 4**: Scripting and automation
- [ ] **Month 5**: Specialization choice and deep dive
- [ ] **Month 6**: First certification attempt (PenTest+ or OSCP)

### Weekly Time Commitment
- **Minimum**: 10-15 hours per week
- **Recommended**: 20-25 hours per week
- **Intensive**: 30+ hours per week

### Success Metrics
- [ ] Can perform end-to-end penetration test on beginner lab
- [ ] Written first professional penetration testing report
- [ ] Solved 50+ CTF challenges
- [ ] Earned first penetration testing certification
- [ ] Contributed to security community (blog, tool, etc.)

---

## 🎯 Focus Strategy: Combat Overwhelm

### The "One Thing" Rule
**Each week, focus on mastering ONE primary skill.** Don't try to learn everything at once.

### Daily Structure (Recommended)
- **1 hour**: Reading/theory (books, articles, documentation)
- **2-3 hours**: Hands-on practice (labs, CTFs, tool practice)
- **30 minutes**: Note-taking and documentation

### Weekly Review Questions
1. What specific skill did I master this week?
2. What practical lab/exercise did I complete?
3. What would I do differently next week?
4. Am I ready to move to the next topic?

---

## 📞 Get Help

Feeling stuck? Here are ways to get help:
1. **Join the community Discord servers** listed above
2. **Ask specific questions** on Reddit communities
3. **Find a mentor** through local security groups
4. **Study group** with other learners

Remember: **Everyone started as a beginner.** The key is consistent, focused practice over time.

---

*Happy hacking! 🔒* 


<br>
<br>

[🎯 Penetration Testing Learning Roadmap - 1](#web-penetration-testing-learning-roadmap-1)

[🎯 Web Penetration Testing Roadmap - 3 (Goals, Practice, Suggested Resources, Tasks) Free Certifications](#web-penetration-testing-learning-roadmap-3)

<a id="web-penetration-testing-learning-roadmap-2"></a>

# 🎯 Penetration Testing Learning Roadmap - 2 (YT Videos/Practical labs) [Collected]

## Roadmap’s Goals

**Track**: Penetration Testing

**Study Time**: 20 Hours / Week

### Skills and Knowledge Gained:

All Skills and Knowledge to be an Intermediate Web Application Penetration Tester

For details: See the *Topics* under every stage below ↓ 

### Initial Background of the Learner

- Has an overview of Cyber Security Fields and He is interested in Penetration Testing
- Resources to get the required knowledge before starting.
    - YT Video — [Cybersecurity from zero to hero | Mohammad Khreesha.](https://www.youtube.com/watch?v=onunKXIfF4E)
    - YT Playlist — [How to start in Information Security Field | Nakerah Network](https://www.youtube.com/playlist?list=PL_yseowcuqYI9cE8Qonbr0SGN1XQFEEPg)
    - FB Post — [How to start in Information Security Field | Ebrahem Hegazy](https://www.facebook.com/Zigoo.eg/posts/pfbid02a73Di1R89XMhUsTWvHBv9yRNca89DzTLuGYLRnrSNWubFxh6xg1aixnLT5Rvxh9Ul)
    - YT Video — [Penetration testing in corporates and high secured | Muhammad Gamal](https://www.youtube.com/watch?v=nadJDhww0Ac)
- [The Secret step-by-step Guide to learn Hacking](https://www.youtube.com/watch?v=2TofunAI6fU)

### Learner’s Level at the End of the Roadmap

a Professional Web Application Penetration Tester

## Before Starting

### Prerequisites

- **Good English ( Reading and Listening )**
- **Researching Skills ( Use Google when you face any problem )**
- **Some Notes to Keep in Mind.**
    - You should study continuously if you are a beginner or even an expert, every day there are new updates in many technologies and new techniques are discovered.
    - All links provided are my recommendation which may not be the best for everyone, so you could change any of them if you found a better resource.

### Important Q&A

1. What do we learn in the first stage(Pre-Security)?
    
    We will learn the core skills that are needed to be a Penetration Tester, those skills are also the core skills for many IT Jobs.
    
2. Is this the best roadmap for a Penetration Tester?
    - You should know that the Cyber Security path is not easy and it takes time and there is no clear path for it that makes you an expert.
    - Keep in mind that the difficulty you face while learning is the same as others so all of us will struggle with being better in this field(we are equal).

---

# Pre-Security

In this stage, we will learn about three core topics and gain some knowledge about the technologies we will face most of the time.

- [**Topics**](Subpages/Topics%20Pre-Security.md)
- [Week 1](Subpages/Week%201.md)
- [Week 2](Subpages/Week%202.md)
- [Week 3](Subpages/Week%203.md)
- [Week 4](Subpages/Week%204.md)
- [Week 5](Subpages/Week%205.md)
- [Week 6](Subpages/Week%206.md)

# Beginner

Here, We will get into simple tasks of the Penetration Tester that will help us know if the track suits us.

- [**Topics**](Subpages/Topics%20Beginner.md)
- [Week 07](Subpages/Week%2007.md)
- [Week 08](Subpages/Week%2008.md)
- [Week 09](Subpages/Week%2009.md)
- [Week 10](Subpages/Week%2010.md)
- [Week 11](Subpages/Week%2011.md)
- [Week 12](Subpages/Week%2012.md)
- [Week 13](Subpages/Week%2013.md)
- [Week 14](Subpages/Week%2014.md)

# Intermediate

In this stage, we will learn new vulnerabilities, deep dive into the OWASP Top 10, and get more hands-on experience.

- [**Topics**](Subpages/Topics%20Intermediate.md)
- [Week 15](Subpages/Week%2015.md)
- [Week 16](Subpages/Week%2016.md)
- [Week 17-28](Subpages/Week%2017-28.md)
- [Week 29-38](Subpages/Week%2029-38.md)
- [Week 39-45](Subpages/Week%2039-45.md)

# Advanced

- [**Topics**](Subpages/Topics%20Advanced.md)
- [Week 46](Subpages/Week%2046.md)
- [Week 47](Subpages/Week%2047.md)
- [Week 48-57](Subpages/Week%2048-57.md)
- [Week 58-60](Subpages/Week%2058-60.md)

---


<br>
<br>

[🎯 Web Penetration Testing Learning Roadmap - 1](#web-penetration-testing-learning-roadmap-1)

[🎯 Web Penetration Testing Learning Roadmap - 2 (YT Videos/Practical labs) Collected](#web-penetration-testing-learning-roadmap-2)

<a id="web-penetration-testing-learning-roadmap-3"></id>

# 🎯 Web Penetration Testing Roadmap - 3 (Goals, Practice, Suggested Resources, Tasks) Free Certifications 

This repository contains a **12‑week, completely free learning roadmap** to go from beginner to web penetration testing (ethical hacking of websites).

Web penetration testing means systematically finding and exploiting security flaws in web applications. It builds on:

- Web fundamentals: HTTP/HTTPS, HTML, browsers, cookies, sessions  
- Common vulnerabilities: injection flaws (e.g. SQLi), XSS, CSRF, authentication issues, etc.  
- Industry standards:  
  - **[OWASP Top Ten](https://owasp.org/www-project-top-ten/):** the most critical web risks  
  - **[OWASP Web Security Testing Guide (WSTG)](https://owasp.org/www-project-web-security-testing-guide/):** comprehensive testing framework

You’ll learn step by step over **12 weeks**, using:

- Free tools: **Kali Linux**, **Burp Suite Community**, **OWASP ZAP**, **sqlmap**, etc.  
- Free vulnerable labs: **DVWA**, **OWASP Juice Shop**, **TryHackMe**, **HackTheBox**, **OverTheWire**, etc.  
- Free video tutorials and free certificates.

> Recommended pace: **10–15 hours per week**. The roadmap moves from basics → core web vulnerabilities → advanced attacks → CTFs & bug bounties.

---

## Week 1 – Setup & Web Fundamentals

Set up your **hacking lab** and learn how the web works.

**Goals**

- Install a lab environment:
  - Kali Linux VM
  - A vulnerable web app (e.g. **DVWA** or **OWASP Juice Shop**)
- Understand:
  - HTTP/HTTPS (methods, status codes, requests vs responses)
  - DNS, web servers, browsers, cookies, and sessions
- Start using **intercepting proxies** (Burp Suite Community, OWASP ZAP)

**What to Study**

- HTTP basics, including:
  - GET, POST and other methods
  - Status codes (2xx, 3xx, 4xx, 5xx)
  - Difference between HTTP and HTTPS
- Client–server model and why HTTP is the “backbone” of web data exchange.

**Practice**

- Intercept and modify simple form requests to DVWA/Juice Shop using your browser and Burp/ZAP.
- Inspect and understand cookies and basic session behavior.

**Suggested Resources**

- YouTube:
  - “HTTP Methods Explained”
  - “OWASP Juice Shop Walkthrough”
- Web:
  - [PortSwigger Web Security Academy – “How the Web Works”](https://portswigger.net/web-security)
  - OWASP HTTP definitions  
  - HTTP protocol tutorials (e.g. TutorialsPoint HTTP Basics)

**Tasks**

- Set up Kali VM and install DVWA or Juice Shop.
- Learn HTTP protocols (HTTP vs HTTPS).
- Use Burp/ZAP to intercept and modify requests.

---

## Week 2 – Reconnaissance & Scanning

Learn how to **find web targets and hidden endpoints**.

**Goals**

- Use search and OSINT for target discovery.
- Learn network and web scanning.
- Enumerate directories, files, and parameters.

**Tools & Techniques**

- Google Dorks for discovery.
- **Nmap** for port and service scanning.
- **Gobuster**/**Dirb** for directory and file brute-forcing.
- **Nikto** for basic web scanning.
- **Burp Suite Proxy** to discover parameters, hidden fields, and pages.
- Subdomain/OSINT tools: **sublist3r**, **Amass**.

**Practice**

- Run Nmap against a VM target.
- Run Nikto, Gobuster/Dirb against DVWA/Juice Shop.
- Use Burp Proxy to map hidden inputs and pages.

**Suggested Resources**

- YouTube:
  - HackerSploit – HTTP Recon & Google Hacking
  - The Cyber Mentor – Web Application Testing Part 1
- Web:
  - OWASP Testing Guide – Information Gathering
  - PortSwigger labs on Content Discovery
  - [OverTheWire – Natas](https://overthewire.org/wargames/natas/) (web recon and server-side basics)

**Tasks**

- Run Nmap on a VM target.
- Use Gobuster to find hidden directories/files.
- Start OverTheWire Natas for web-based recon challenges.

---

## Week 3 – SQL Injection (SQLi)

One of the most famous and critical web vulnerabilities.

**Goals**

- Understand SQL Injection types:
  - UNION-based
  - Boolean-based (and error-based)
- Learn manual exploitation and automation with **sqlmap**.

**Practice**

- Use DVWA’s SQLi module and Juice Shop’s SQLi challenges.
- Craft manual payloads like:
  - `' OR 1=1--`
  - `' || 1=1--`
- Use Burp to intercept login/parameterized requests and inject malicious SQL.
- Use **sqlmap** against a test URL for automated exploitation.

**Suggested Resources**

- YouTube:
  - HackerSploit – OWASP Juice Shop SQL Injection
  - The Cyber Mentor – SQL Injection Explained
- Web:
  - [OWASP SQL Injection](https://owasp.org/www-community/attacks/SQL_Injection)
  - TryHackMe:
    - [SQL Injection room](https://tryhackme.com/room/sqlinject)
    - “Web Fundamentals” labs

**Tasks**

- Exploit SQLi on DVWA at low and medium levels, then increase difficulty.
- Run sqlmap on a vulnerable test URL/lab.

---

## Week 4 – Cross-Site Scripting (XSS)

Inject malicious scripts into web pages.

**Goals**

- Understand and exploit:
  - Reflected XSS
  - Stored XSS
  - DOM-based XSS
- Learn how XSS can hijack sessions, steal cookies, and perform CSRF-like actions.

**Practice**

- DVWA:
  - XSS (Reflected) and XSS (Stored) modules.
- Juice Shop:
  - Find search, greeting, or input fields and try payloads like:
    ```html
    <script>alert(1)</script>
    ```
- Use Burp to modify parameters and test multiple payloads.
- Experiment in the browser console with different payloads and encodings.

**Suggested Resources**

- YouTube:
  - HackerSploit – Web App Pentesting XSS (Reflected/Stored/DOM)
  - Traversy Media – XSS Tutorial
- Web:
  - [OWASP Cross-Site Scripting (XSS)](https://owasp.org/www-community/attacks/xss/)
  - PortSwigger XSS labs

**Tasks**

- Find and exploit several XSS vulnerabilities in your lab apps.
- Demonstrate how an XSS can access cookies or perform actions on behalf of a user (in a safe lab).

---

## Week 5 – File Inclusion & Remote Code Execution (RCE)

Abusing insecure file handling and command execution.

**Goals**

- Understand:
  - Local File Inclusion (LFI)
  - Remote File Inclusion (RFI)
  - Command Injection → Remote Code Execution

**Practice**

- DVWA:
  - File Inclusion challenge – try:
    - Reading files like `/etc/passwd`
    - Using wrappers like `php://input` if available
  - Command Injection module – inject commands such as:
    ```bash
    ; ls
    && whoami
    ```
- See how unsanitized input leads to file reads or code execution.

**Suggested Resources**

- YouTube:
  - HackerSploit – LFI & RFI Tutorials
- Web:
  - OWASP Testing Guide – File Inclusion
  - OWASP Testing Guide – Command Injection
  - TryHackMe lab on File Inclusion

**Tasks**

- Exploit DVWA LFI/RFI to show arbitrary file reads or code execution.
- Achieve basic RCE via command injection in the lab.

---

## Week 6 – CSRF, Authentication & Session Management

Abusing trust in the user’s browser and weak session controls.

**Goals**

- Understand **Cross-Site Request Forgery (CSRF)**.
- Learn **broken authentication** patterns:
  - Weak passwords & poor password policies
  - Session hijacking and fixation
  - Common JWT-related flaws

**Practice**

- DVWA:
  - CSRF demo – send forged requests that change user data without a valid CSRF token.
- Build a CSRF Proof of Concept:
  - A hidden HTML form that auto-submits to your lab app.
- Explore how Juice Shop manages sessions:
  - See how cookies and tokens are set and used.
  - Experiment with cookie manipulation in a controlled environment.

**Suggested Resources**

- YouTube:
  - Rana Khalil – CSRF Explained
- Web:
  - OWASP CSRF Prevention Cheat Sheet
  - OWASP Session Management Cheat Sheet

**Tasks**

- Implement a working CSRF PoC against your lab app.
- Analyze and document its session management and auth flows.

---

## Week 7 – Advanced Injection & Business Logic

Go beyond the basics into more advanced web vulnerabilities.

**Goals**

- Learn:
  - XML External Entity (XXE) Injection
  - Server-Side Request Forgery (SSRF)
  - (Optional/extra) Insecure Deserialization and Object Injection

**Practice**

- XXE:
  - If your lab has XML upload/parse features, try payloads such as:
    ```xml
    <!DOCTYPE foo [<!ENTITY xxe SYSTEM "file:///etc/passwd">]>
    <foo>&xxe;</foo>
    ```
- SSRF:
  - Look for any feature that fetches a URL (e.g. image fetch, webhook tester).
  - Try pointing it at internal IPs (e.g. `http://127.0.0.1`) in a **lab**.
- Additional:
  - Explore CTFs that provide insecure deserialization or object injection challenges.

**Suggested Resources**

- YouTube:
  - HackerOne – SSRF Introduction
- Web:
  - OWASP XXE Prevention Cheat Sheet
  - OWASP SSRF cheat sheet/wiki

**Tasks**

- Trigger at least one XXE lab challenge (e.g. Juice Shop has XML-based challenges).
- Attempt SSRF challenges in CTF environments if available.

---

## Week 8 – Mastering Tools (Burp Suite & OWASP ZAP)

Get fluent with your main web pentesting tools.

**Goals**

- Become comfortable with:
  - **Burp Suite Community**
  - **OWASP ZAP**

**Burp Suite Focus**

- Repeater: modify and resend requests.
- Intruder: brute-force or fuzz parameters.
- Decoder/Comparer: encode/decode and compare responses.
- Spider/Crawler: map out a target application.
- Explore useful Burp extensions, e.g. **Autorize** for access control testing.

**ZAP Focus**

- Automated scanning and spidering.
- Manual request modification and interception.

**Practice**

- Work through PortSwigger’s Burp Suite labs.
- Use Intruder to brute-force a simple short password or PIN.
- Run ZAP scans against your lab applications and compare findings with Burp.

**Suggested Resources**

- YouTube:
  - PortSwigger – Burp Suite Beginner Tutorial
- Web:
  - OWASP ZAP User Guide
  - PortSwigger Web Security Academy – “Burp Suite: The Basics”
  - TryHackMe rooms covering Burp/ZAP basics

**Tasks**

- Complete basic Burp Suite training path on PortSwigger Academy.
- Use Burp Intruder or ZAP to automate at least one attack (e.g. simple credential brute-force) in a lab.

---

## Week 9 – Web Application Attacks: Business Logic & Insecure Design

Understand **application-specific** weaknesses.

**Goals**

- Learn about **Business Logic Flaws**, such as:
  - Bypassing workflow steps
  - Manipulating transaction limits
  - Race conditions
- Explore insecure design issues:
  - Missing or weak security headers (CSP, X-Frame-Options, HSTS)
  - Clickjacking

**Practice**

- Implement a basic clickjacking demo:
  - Frame a vulnerable page using an `<iframe>` and overlay UI.
- Use tools like `securityheaders.com` to scan for missing security headers.
- Examine OAuth/JWT flows (if available in your labs):
  - Try modifying JWT payloads (e.g. role claims) to see whether proper verification is enforced.

**Suggested Resources**

- YouTube:
  - The Cyber Mentor – Business Logic Flaws
- Web:
  - OWASP Insecure Design
  - OWASP Clickjacking Defense Cheat Sheet

**Tasks**

- Identify at least one logical flaw or weak design decision in a test application.
- Verify how security headers are configured and document missing controls.

---

## Week 10 – Practice Projects & CTF

Put everything together in realistic scenarios.

**Goals**

- Conduct an end-to-end **web app pentest**.
- Get exposure to **CTF-style** web challenges.

**Practice**

- Choose 1–2 free targets:
  - DVWA (all modules, higher security levels)
  - Juice Shop (try to find most of the OWASP Top 10 issues)
  - Juice Shop CTF challenges
- Attempt:
  - [TryHackMe – OWASP Juice Shop room](https://tryhackme.com/)
  - HackTheBox web machines such as “Fortune” (when available as a free box)
- Write a **pentest report** (even if just for yourself), including:
  - Scope
  - Methodology
  - Findings with impact and remediation
  - Proof of Concept screenshots or request/response samples

**Suggested Resources**

- TryHackMe:
  - Web Penetration Testing rooms and paths
- OverTheWire:
  - Natas (web wargame)
- [BugBountyHunter.com](https://bugbountyhunter.com/):
  - Free bug bounty challenge labs

**Tasks**

- Complete at least one full end-to-end pentest on a lab app (mapping → exploitation → reporting).
- Solve several CTF web challenges and document your solutions.

---

## Week 11 – Bug Bounty & CTF Focus

Prepare for real-world bug bounties and organized competitions.

**Goals**

- Learn bug bounty workflow:
  - Scoping targets and staying legal
  - Reading and following program rules
  - Writing clear reports
- Improve CTF & hunting skills through practice platforms.

**Practice**

- Study public bug reports on:
  - [HackerOne](https://hackerone.com/)
- Learn how to use Burp’s active scanner on **demo** or lab apps.
- Start low-risk, authorized hunting:
  - HackerOne/Hacker101 lab targets
  - Beginner-friendly programs and CTFs

**Suggested Resources**

- Web:
  - HackerOne – Hacker101 courses and labs
  - BugBountyHunter.com – training challenges
  - OWASP Bug Bounty guidelines
- YouTube:
  - LiveOverflow – Bug Bounty tutorials

**Tasks**

- Read multiple public bug bounty reports and rewrite them in your own words.
- Complete at least one Hacker101 or BugBountyHunter lab from start to finish.

---

## Week 12 – Review, Certification & Next Steps

Consolidate your knowledge and plan your long-term path.

**Goals**

- Review and fill in knowledge gaps from previous weeks.
- Complete a **capstone project**.
- Explore **free certifications and badges** to showcase your skills.

**Capstone Ideas**

- Fix vulnerabilities in sample code or in your own small web app.
- Build a very simple intentionally vulnerable app and document its issues.
- Perform a full pentest against your own app and write a full report.

**Free Certifications & Training**

- **(ISC)² Certified in Cybersecurity (CC)**
  - Free self-study training and exam options for entry-level cybersecurity  
  - Shows understanding of security fundamentals
- **TryHackMe Certificates**
  - Completing paths like “Web Fundamentals” yields verifiable certificates
- **EC-Council Free Courses**
  - ~24 free cybersecurity courses with certificates (topics from SQLi to cloud)
- Other Vendors:
  - **Fortinet NSE**, **Microsoft Learn**, **Cisco NetAcad**, etc.
  - Coursera/edX allow auditing pentesting courses for free (certs usually paid).

**Career & Community**

- Update your **resume** and **GitHub**:
  - List labs, CTFs, and paths completed
  - Add write-ups and code samples from your capstone projects
- Join security communities:
  - Reddit (e.g. /r/netsec, /r/AskNetsec, /r/bugbounty)
  - Discord CTF/bounty servers
- Continue practicing strictly on **authorized** platforms:
  - Never test real sites without explicit permission.

---

## Summary

This 12‑week plan takes you from:

- **Web basics** → HTTP, HTTPS, DNS, sessions  
- Through **core web vulnerabilities**:
  - SQLi, XSS, CSRF
  - File inclusion, RCE, auth & session flaws
  - XXE, SSRF, business logic issues
- To **advanced practice**:
  - Burp Suite & ZAP mastery
  - CTFs and bug bounty workflows
  - Full pentest projects and reporting

By Week 12, with 10–15 hours/week, you should be ready to:

- Compete in beginner/intermediate **CTFs**
- Start **bug bounty** hunting on low-risk, authorized programs
- Apply for **entry-level security roles** with:
  - Hands-on lab experience
  - Public write-ups or GitHub projects
  - Free certifications (e.g. ISC2 CC, TryHackMe path certificates, EC-Council free course certs)

---

## Sources & Recommended Reading

Authoritative guides and learning platforms that support and expand on this roadmap:

- [OWASP](https://owasp.org/)
  - OWASP Top Ten
  - OWASP Web Security Testing Guide
  - OWASP Cheat Sheets (XSS, CSRF, Session Management, XXE, etc.)
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
  - Free, up-to-date web security labs and Burp Suite training
- Tutorials and references:
  - TutorialsPoint HTTP Basics
- Practice platforms:
  - [TryHackMe](https://tryhackme.com/)
  - [HackTheBox](https://hackthebox.com/)
  - [BugBountyHunter.com](https://bugbountyhunter.com/)
  - [OverTheWire](https://overthewire.org/)
- Certifications & courses:
  - [ISC2 – Certified in Cybersecurity (CC)](https://www.isc2.org/)
  - [EC-Council free courses](https://www.eccouncil.org/)

These sources confirm the scope of modern web vulnerabilities and the availability of **free, high-quality training and certifications**.

---

## 🤝 Contributing

This roadmap is a living document! Please contribute by:
- Adding new resources you've found helpful
- Sharing your learning experience and timeline
- Suggesting improvements to the learning path
- Adding practice labs and exercises

---

## ⚖️ Legal Disclaimer

**Important**: Only perform penetration testing on systems you own or have explicit written permission to test. Unauthorized access to computer systems is illegal in most jurisdictions.

Always follow responsible disclosure practices when finding vulnerabilities.

---

<details><summary><h2>📂 My More Work</h2></summary>

<div align="center"><h2>📔NoteBooks AND Facebook Community Group</h2></div>

<p align="center">
  <a href="https://github.com/SagarBiswas-MultiHAT/Google_Dorks_Notebook">
    <img width="328" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Google_Dorks_Notebook&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Google_Dorks_Notebook"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/noteBooks-maintainingBYme">
    <img width="328" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=noteBooks-maintainingBYme&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Google_Dorks_Notebook"></a>

<br>

    NOTE: To find more notebooks, projects, tips and tricks like this, join my Facebook community group and check the featured section for notebooks and explore the Posts to discover real-world projects.

<div align="center">
  <a href="https://www.facebook.com/groups/aiubcybersecurityandprogrammingsociety">
    AIUB CyberSecurity & Programming Society
  </a>
</div>
</p>

<div align="center"><h2>Useful Repositories</h2></div>

<p align="center">

  <a href="https://github.com/SagarBiswas-MultiHAT/Web_Penetration_Testing_Roadmap">
    <img width="328" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Web_Penetration_Testing_Roadmap&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Web_Penetration_Testing_Roadmap"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/infosec-vocabulary">
    <img width="328" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=infosec-vocabulary&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="infosec-vocabulary"></a>
  
  <a href="https://github.com/SagarBiswas-MultiHAT/Cybersecurity-Library">
    <img width="328" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Cybersecurity-Library&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Cybersecurity-Library"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/WSL-Installation_Guide/">
    <img width="328" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=WSL-Installation_Guide&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="WSL-Installation_Guide"></a>
</p>

<div align="center"><h2>🤖AI Based Projects</h2></div>
<p align="center">

  <a href="https://github.com/SagarBiswas-MultiHAT/Web_Vulnerability_Scanner-AI">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Web_Vulnerability_Scanner-AI&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Web_Vulnerability_Scanner-AI"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/Speech2Speech-AIAssistant">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Speech2Speech-AIAssistant&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Speech2Speech-AIAssistant"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/PythonicHackathon-CLI">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=PythonicHackathon-CLI&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="PythonicHackathon-CLI"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/Ai-Resume-Analyzer">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Ai-Resume-Analyzer&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Ai-Resume-Analyzer"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/Ai-Phishy-Playground">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Ai-Phishy-Playground&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Ai-Phishy-Playground"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/Chat-Automation-Bot_Ai-Assistant">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Chat-Automation-Bot_Ai-Assistant&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Chat-Automation-Bot_Ai-Assistant"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/Cyber-Command_AI-Assistant.exe">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Cyber-Command_AI-Assistant.exe&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Cyber-Command_AI-Assistant.exe"></a>
</p>

<div align="center"><h2>🤖 Tools/Automation</h2></div>

<p align="center">
  <a href="https://github.com/SagarBiswas-MultiHAT/MacChanger-V1-MAX">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=MacChanger-V1-MAX&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="MacChanger-V1-MAX"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/Phoneint-OSINT-Toolkit">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Phoneint-OSINT-Toolkit&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Phoneint-OSINT-Toolkit"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/WebSource-Harvester">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=WebSource-Harvester&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="WebSource-Harvester"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/HashAttackDemos">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=HashAttackDemos&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="HashAttackDemos"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/A_Pythonic-Keylogger">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=A_Pythonic-Keylogger&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="A_Pythonic-Keylogger"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/BruteforceLab1">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=BruteforceLab1&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="BruteforceLab1"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/BruteforceLab2">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=BruteforceLab2&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="BruteforceLab2"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/EmailBomber">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=EmailBomber&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="EmailBomber"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/NmapScanningTool-V1-MAX">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=NmapScanningTool-V1-MAX&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="NmapScanningTool-V1-MAX"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/WinTempCleaner">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=WinTempCleaner&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="WinTempCleaner"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/WiFi-Dictionary-Attack">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=WiFi-Dictionary-Attack&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="WiFi-Dictionary-Attack"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/SeleniumFirefoxGoogleSearchAutomation">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=SeleniumFirefoxGoogleSearchAutomation&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="SeleniumFirefoxGoogleSearchAutomation"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/TextBombing-Toolkit">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=TextBombing-Toolkit&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="TextBombing-Toolkit"></a>

</p>

<div align="center"><h2>🛜 Networking</h2></div>

<p align="center">

  <a href="https://github.com/SagarBiswas-MultiHAT/TCP-Playground">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=TCP-Playground&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="TCP-Playground"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/Saved-WiFi-Restore">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Saved-WiFi-Restore&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Saved-WiFi-Restore"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/WiFi-Dictionary-Attack">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=WiFi-Dictionary-Attack&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="WiFi-Dictionary-Attack"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/WiFi-QR-Generator">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=WiFi-QR-Generator&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="WiFi-QR-Generator"></a>
    
  <a href="https://github.com/SagarBiswas-MultiHAT/domain2ip">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=domain2ip&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="domain2ip"></a>
</p>


<div align="center"><h2>🧑‍💻 Development</h2></div>

<p align="center">

  <a href="https://github.com/SagarBiswas-MultiHAT/SharpLink-URL-Allies/">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=SharpLink-URL-Allies&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="SharpLink-URL-Allies"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/Photo-PDF-Bidirectional-Converter/">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Photo-PDF-Bidirectional-Converter&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Photo-PDF-Bidirectional-Converter"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/AirportDesk-Assistant/">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=AirportDesk-Assistant&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="AirportDesk-Assistant"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/Library-Management-System">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Library-Management-System&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Library-Management-System"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/Multi-FA-Auth/">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Multi-FA-Auth&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Multi-FA-Auth"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/PyTextEditor/">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=PyTextEditor&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="PyTextEditor"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/SafeTodoManager">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=SafeTodoManager&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="SafeTodoManager"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/SecurePay_E-Wallet-V1">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=SecurePay_E-Wallet-V1&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="SecurePay_E-Wallet-V1"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/Student-Management-MVC-Learning-Project">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Student-Management-MVC-Learning-Project&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Student-Management-MVC-Learning-Project"></a>
  
  <a href="https://github.com/SagarBiswas-MultiHAT/TicTacToe-Game">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=TicTacToe-Game&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="TicTacToe-Game"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/SecureBank-CLI">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=SecureBank-CLI&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="SecureBank-CLI"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/SecureBankingSystem">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=SecureBankingSystem&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="SecureBankingSystem"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/CustomerSlip-CLI">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=CustomerSlip-CLI&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="CustomerSlip-CLI"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/PyCalculator">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=PyCalculator&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="PyCalculator"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/Contact-Management-System">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Contact-Management-System&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Contact-Management-System"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/SnakeWaterGun-Game">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=SnakeWaterGun-Game&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="SnakeWaterGun-Game"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/SnakeWaterGun-Game">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=PyAlarmClock&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="PyAlarmClock"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/AirportDesk-Assistant">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=AirportDesk-Assistant&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="AirportDesk-Assistant"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/Fake_FACEBOOK_Login_Page">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Fake_FACEBOOK_Login_Page&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Fake_FACEBOOK_Login_Page"></a>

</p>

<div align="center"><h2>🤖 Small Projects</h2></div>

<p align="center">

  <a href="https://github.com/SagarBiswas-MultiHAT/Password-Strength-Checker">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Password-Strength-Checker&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Password-Strength-Checker"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/XSS-WebGuard">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=XSS-WebGuard&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="XSS-WebGuard"></a>


  <a href="https://github.com/SagarBiswas-MultiHAT/Port_Scanner-Python">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Port_Scanner-Python&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Port_Scanner-Python"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/RandomPasswordGeneratorCpp">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=RandomPasswordGeneratorCpp&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="RandomPasswordGeneratorCpp"></a>

  <a href="https://github.com/SagarBiswas-MultiHAT/virusNewFolder">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=virusNewFolder&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="virusNewFolder"></a>

</p>

<div align="center"><h2>Collected Projects</h2></div>

<p align="center">

  <a href="https://github.com/SagarBiswas-MultiHAT/Impress-Crush-CPP-ASCII">
    <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=SagarBiswas-MultiHAT&repo=Impress-Crush-CPP-ASCII&theme=github_dark&border_color=02D892&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&show_icons=false" alt="Impress-Crush-CPP-ASCII"></a>
</p>

</details>
