# 🎯 Web Penetration Testing Roadmap 3: 12-Week Focused Curriculum

> **A completely free, 12-week learning path from beginner to web pentester**

[⬅ Back to Main README](../README.md) | [Roadmap 1 ←](roadmap-1-foundations.md) | [Roadmap 2 ←](roadmap-2-practical-labs.md)

---

This roadmap contains a **12‑week, completely free learning plan** to go from beginner to web penetration testing (ethical hacking of websites).

Web penetration testing means systematically finding and exploiting security flaws in web applications. It builds on:

- Web fundamentals: HTTP/HTTPS, HTML, browsers, cookies, sessions  
- Common vulnerabilities: injection flaws (e.g. SQLi), XSS, CSRF, authentication issues, etc.  
- Industry standards:  
  - **[OWASP Top Ten](https://owasp.org/www-project-top-ten/):** the most critical web risks  
  - **[OWASP Web Security Testing Guide (WSTG)](https://owasp.org/www-project-web-security-testing-guide/):** comprehensive testing framework

You'll learn step by step over **12 weeks**, using:

- Free tools: **Kali Linux**, **Burp Suite Community**, **OWASP ZAP**, **sqlmap**, etc.  
- Free vulnerable labs: **DVWA**, **OWASP Juice Shop**, **TryHackMe**, **HackTheBox**, **OverTheWire**, etc.  
- Free video tutorials and free certificates.

> Recommended pace: **10–15 hours per week**. The roadmap moves from basics → core web vulnerabilities → advanced attacks → CTFs & bug bounties.

---

## Week 1 – Setup & Web Fundamentals

Set up your **hacking lab** and learn how the web works.

**Goals**
- Install a lab environment: Kali Linux VM, DVWA or OWASP Juice Shop
- Understand: HTTP/HTTPS (methods, status codes, requests vs responses), DNS, web servers, browsers, cookies, and sessions
- Start using **intercepting proxies** (Burp Suite Community, OWASP ZAP)

**Practice**
- Intercept and modify simple form requests to DVWA/Juice Shop using your browser and Burp/ZAP.
- Inspect and understand cookies and basic session behavior.

**Suggested Resources**
- [PortSwigger Web Security Academy – "How the Web Works"](https://portswigger.net/web-security)
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
- Google Dorks, **Nmap**, **Gobuster**/**Dirb**, **Nikto**, **Burp Suite Proxy**, **sublist3r**, **Amass**

**Practice**
- Run Nmap against a VM target.
- Run Nikto, Gobuster/Dirb against DVWA/Juice Shop.
- Use Burp Proxy to map hidden inputs and pages.

**Suggested Resources**
- HackerSploit – HTTP Recon & Google Hacking (YouTube)
- The Cyber Mentor – Web Application Testing Part 1 (YouTube)
- [OverTheWire – Natas](https://overthewire.org/wargames/natas/) (web recon and server-side basics)

**Tasks**
- Run Nmap on a VM target.
- Use Gobuster to find hidden directories/files.
- Start OverTheWire Natas for web-based recon challenges.

---

## Week 3 – SQL Injection (SQLi)

One of the most famous and critical web vulnerabilities.

**Goals**
- Understand SQL Injection types: UNION-based, Boolean-based, Error-based
- Learn manual exploitation and automation with **sqlmap**

**Practice**
- Use DVWA's SQLi module and Juice Shop's SQLi challenges.
- Craft manual payloads: `' OR 1=1--`, `' || 1=1--`
- Use Burp to intercept and inject malicious SQL.
- Use **sqlmap** against a test URL for automated exploitation.

**Suggested Resources**
- [OWASP SQL Injection](https://owasp.org/www-community/attacks/SQL_Injection)
- [TryHackMe SQL Injection room](https://tryhackme.com/room/sqlinject)

**Tasks**
- Exploit SQLi on DVWA at low and medium levels, then increase difficulty.
- Run sqlmap on a vulnerable test URL/lab.

---

## Week 4 – Cross-Site Scripting (XSS)

Inject malicious scripts into web pages.

**Goals**
- Understand and exploit: Reflected XSS, Stored XSS, DOM-based XSS
- Learn how XSS can hijack sessions, steal cookies, and perform CSRF-like actions.

**Practice**
- DVWA: XSS (Reflected) and XSS (Stored) modules.
- Juice Shop: Find input fields and try payloads like `<script>alert(1)</script>`
- Use Burp to modify parameters and test multiple payloads.

**Suggested Resources**
- [OWASP Cross-Site Scripting (XSS)](https://owasp.org/www-community/attacks/xss/)
- PortSwigger XSS labs

**Tasks**
- Find and exploit several XSS vulnerabilities in your lab apps.
- Demonstrate how an XSS can access cookies or perform actions on behalf of a user.

---

## Week 5 – File Inclusion & Remote Code Execution (RCE)

Abusing insecure file handling and command execution.

**Goals**
- Understand: Local File Inclusion (LFI), Remote File Inclusion (RFI), Command Injection → RCE

**Practice**
- DVWA: File Inclusion challenge – try reading `/etc/passwd`, using wrappers like `php://input`
- DVWA: Command Injection module – inject `;  ls` or `&& whoami`

**Suggested Resources**
- HackerSploit – LFI & RFI Tutorials (YouTube)
- OWASP Testing Guide – File Inclusion / Command Injection
- TryHackMe lab on File Inclusion

**Tasks**
- Exploit DVWA LFI/RFI to show arbitrary file reads or code execution.
- Achieve basic RCE via command injection in the lab.

---

## Week 6 – CSRF, Authentication & Session Management

Abusing trust in the user's browser and weak session controls.

**Goals**
- Understand **Cross-Site Request Forgery (CSRF)**
- Learn **broken authentication** patterns: weak passwords, session hijacking/fixation, JWT flaws

**Practice**
- DVWA: CSRF demo – send forged requests without a valid CSRF token
- Build a CSRF PoC: a hidden HTML form that auto-submits to your lab app
- Explore Juice Shop session management: cookie manipulation, token analysis

**Suggested Resources**
- Rana Khalil – CSRF Explained (YouTube)
- OWASP CSRF Prevention Cheat Sheet
- OWASP Session Management Cheat Sheet

**Tasks**
- Implement a working CSRF PoC against your lab app.
- Analyze and document its session management and auth flows.

---

## Week 7 – Advanced Injection & Business Logic

Go beyond the basics into more advanced web vulnerabilities.

**Goals**
- Learn: XML External Entity (XXE) Injection, Server-Side Request Forgery (SSRF), Insecure Deserialization

**Practice**
- XXE: Try payloads like `<!DOCTYPE foo [<!ENTITY xxe SYSTEM "file:///etc/passwd">]>`
- SSRF: Point URL-fetch features at internal IPs (e.g. `http://127.0.0.1`) in a lab
- Explore CTFs with insecure deserialization challenges

**Suggested Resources**
- HackerOne – SSRF Introduction (YouTube)
- OWASP XXE Prevention Cheat Sheet
- OWASP SSRF cheat sheet

**Tasks**
- Trigger at least one XXE lab challenge.
- Attempt SSRF challenges in CTF environments.

---

## Week 8 – Mastering Tools (Burp Suite & OWASP ZAP)

Get fluent with your main web pentesting tools.

**Burp Suite Focus**: Repeater, Intruder, Decoder/Comparer, Spider/Crawler, Autorize extension

**ZAP Focus**: Automated scanning, spidering, manual request interception

**Practice**
- Work through PortSwigger's Burp Suite labs.
- Use Intruder to brute-force a simple short password or PIN.
- Run ZAP scans against lab applications and compare findings with Burp.

**Tasks**
- Complete basic Burp Suite training path on PortSwigger Academy.
- Automate at least one attack using Burp Intruder or ZAP.

---

## Week 9 – Business Logic & Insecure Design

Understand **application-specific** weaknesses.

**Goals**
- Learn about: workflow bypass, transaction limit manipulation, race conditions
- Explore: missing security headers (CSP, X-Frame-Options, HSTS), clickjacking

**Practice**
- Implement a basic clickjacking demo with `<iframe>` overlay
- Use `securityheaders.com` to scan for missing headers
- Examine OAuth/JWT flows — try modifying JWT payloads

**Tasks**
- Identify at least one logical flaw in a test application.
- Document missing security headers and their impact.

---

## Week 10 – Practice Projects & CTF

Put everything together in realistic scenarios.

**Practice**
- Choose 1–2 free targets: DVWA (all modules), Juice Shop (OWASP Top 10), Juice Shop CTF
- Write a **pentest report** including: Scope, Methodology, Findings, Remediation, PoC evidence

**Platforms**: [TryHackMe](https://tryhackme.com/), [HackTheBox](https://hackthebox.com/), [OverTheWire Natas](https://overthewire.org/wargames/natas/), [BugBountyHunter.com](https://bugbountyhunter.com/)

**Tasks**
- Complete at least one full end-to-end pentest (mapping → exploitation → reporting).
- Solve several CTF web challenges and document solutions.

---

## Week 11 – Bug Bounty & CTF Focus

Prepare for real-world bug bounties and organized competitions.

**Goals**
- Learn bug bounty workflow: scoping, program rules, clear report writing
- Study public bug reports on [HackerOne](https://hackerone.com/)
- Start low-risk, authorized hunting on HackerOne/Hacker101 lab targets

**Tasks**
- Read multiple public bug bounty reports and rewrite in your own words.
- Complete at least one Hacker101 or BugBountyHunter lab from start to finish.

---

## Week 12 – Review, Certification & Next Steps

Consolidate your knowledge and plan your long-term path.

**Capstone Ideas**
- Fix vulnerabilities in sample code or in your own small web app
- Build an intentionally vulnerable app and document its issues
- Perform a full pentest against your own app and write a full report

**Free Certifications & Training**
- **(ISC)² Certified in Cybersecurity (CC)** – Free self-study training and exam
- **TryHackMe Certificates** – Completing paths like "Web Fundamentals" yields verifiable certificates
- **EC-Council Free Courses** – ~24 free cybersecurity courses with certificates
- Other: **Fortinet NSE**, **Microsoft Learn**, **Cisco NetAcad**, Coursera/edX (audit for free)

**Career & Community**
- Update your **resume** and **GitHub** with labs, CTFs, and write-ups
- Join security communities: Reddit (/r/netsec, /r/bugbounty), Discord CTF servers
- Continue practicing on **authorized** platforms only

---

## Summary

By Week 12, with 10–15 hours/week, you should be ready to:
- Compete in beginner/intermediate **CTFs**
- Start **bug bounty** hunting on low-risk, authorized programs
- Apply for **entry-level security roles** with hands-on experience, public write-ups, and free certifications

---

## ⚖️ Legal Disclaimer

**Important**: Only perform penetration testing on systems you own or have explicit written permission to test. Unauthorized access to computer systems is illegal in most jurisdictions. Always follow responsible disclosure practices.

---

[⬅ Back to Main README](../README.md)
