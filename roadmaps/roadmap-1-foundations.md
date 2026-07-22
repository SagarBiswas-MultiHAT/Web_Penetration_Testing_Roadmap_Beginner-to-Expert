# 🎯 Penetration Testing Learning Roadmap 1: Foundations to Professional

> **A structured guide to help you navigate the overwhelming world of penetration testing**

[⬅ Back to Main README](../README.md) | [Roadmap 2 →](roadmap-2-practical-labs.md) | [Roadmap 3 →](roadmap-3-goals-tasks.md)

---

## 📖 Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Phase 1: Foundation Building (4-6 weeks)](#phase-1-foundation-building-4-6-weeks)
- [Phase 2: Core Skills Development (8-12 weeks)](#phase-2-core-skills-development-8-12-weeks)
- [Phase 3: Specialization (12+ weeks)](#phase-3-specialization-12-weeks)
- [Phase 4: Professional Development](#phase-4-professional-development)
- [Certification Roadmap](#certification-roadmap)
- [Progress Tracking](#progress-tracking)
- [Focus Strategy: Combat Overwhelm](#focus-strategy-combat-overwhelm)

---

## 🎭 Introduction

**Feeling overwhelmed is normal!** Penetration testing is a vast field that combines networking, programming, system administration, and security expertise. This roadmap will help you build skills systematically rather than jumping around topics randomly.

### 🎯 Goals of This Roadmap
- **Structure**: Clear learning phases with defined objectives
- **Focus**: One skill at a time to avoid overwhelm
- **Practical**: Hands-on labs and real-world scenarios
- **Progressive**: Each phase builds on the previous one

---

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
1. **Join the community Discord servers** listed in [Community Channels](community-channels.md)
2. **Ask specific questions** on Reddit communities
3. **Find a mentor** through local security groups
4. **Study group** with other learners

Remember: **Everyone started as a beginner.** The key is consistent, focused practice over time.

---

*Happy hacking! 🔒*
