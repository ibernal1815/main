<h1 align="center">⚔️ Isaiah Bernal – Purple Team Engineer in Progress ⚔️</h1>
<p align="center">💡 Adversary Emulation | Detection Engineering | Building Real Labs 💡</p>

---

## 👋 About Me
- 22 y/o cybersecurity + IT professional  
- Associate's in Programming & Cybersecurity  
- Bachelor's in Computer Information Technology (in progress)  
- Planning a Master's in Software Engineering  
- Seeking **remote** cybersecurity or IT roles  
- Focused on **Purple Teaming** — simulating real attacks and building custom detections

---

## 🧠 Current Focus Areas
- Detection Engineering: Suricata, Sigma, Wazuh, Sysmon  
- Adversary Emulation: Atomic Red Team, MITRE ATT&CK  
- Hands-on lab building using CPTS, TryHackMe, HackTheBox  
- Endpoint Hardening (macOS/iOS), Cloud Misconfig Detection  
- Helpdesk simulation and IT service environments

---

## 🛡️ Certifications 

### 🧩 CompTIA ITF+ — *Foundational IT Knowledge*
- Understand binary, hexadecimal, logic gates, and basic encoding
- Operating system structures (Windows/Linux/macOS basics)
- Software development lifecycle (SDLC) phases and flowcharts
- Network fundamentals (IP, DNS, ports, OSI/TCP models)
- Cybersecurity core concepts: CIA triad, threats, vulnerabilities, risk

---

### 🖥️ CompTIA A+ — *IT Support, Hardware, and Operating Systems*
- PC hardware diagnostics and component replacement (RAM, PSU, HDD)
- Windows deployment (Sysprep, PXE boot, disk imaging)
- Troubleshooting startup, login, connectivity, and boot issues
- CLI tools: `ipconfig`, `ping`, `netstat`, `chkdsk`, `tasklist`
- Mobile device and MDM configuration (VPNs, email, security profiles)
- Understanding virtualization basics: Hyper-V, VirtualBox

---

### 🌐 CompTIA Network+ — *Networking & Protocol Analysis*
- Network design: IP subnetting (CIDR, VLSM), VLANs, and NAT
- Routing and switching protocols: OSPF, RIP, STP
- Wireshark packet capture and protocol dissection (TCP, DNS, ICMP)
- Wireless standards, encryption (WPA3, WEP), and interference sources
- Troubleshooting Layer 1–4 issues across LAN/WAN/VPN setups

---

### 🔐 CompTIA Security+ — *Core Cybersecurity Principles*
- Authentication and access control: RBAC, ABAC, LDAP, SAML, MFA
- Cryptographic algorithms: AES, RSA, ECC, hashing (SHA, bcrypt)
- Secure protocols: SSH, HTTPS, SNMPv3, IPSec
- Social engineering and malware types (trojans, worms, spyware)
- Risk mitigation frameworks: NIST, ISO/IEC 27001
- Application security: input validation, fuzzing, patching

---

### 🧪 CompTIA CySA+ — *Threat Detection & Response*
- SIEM technologies: Splunk, Wazuh, ELK — log ingestion and correlation
- Host-based detection: Sysmon event monitoring, file integrity checking
- Network-based detection: IDS (Suricata/Snort), anomaly-based triggers
- Threat hunting methodologies using MITRE ATT&CK and IOC pivoting
- Incident response: detection, containment, eradication, recovery
- Vulnerability management and post-incident analysis

---

### ☁️ CompTIA Cloud Essentials+ — *Cloud Computing Basics*
- Cloud service models: IaaS, PaaS, SaaS + hybrid/multi-cloud environments
- Shared responsibility models across AWS, Azure, GCP
- IAM policies and privilege boundaries (role-based access)
- Data protection strategies (encryption, backups, availability zones)
- Cloud risks: misconfigured storage, cost overrun, compliance violations
- Logging and monitoring cloud-native services (CloudTrail, Azure Monitor)

---

## 🎓 Education
> *Note: Below are selected highlights — not a complete course list.*

### Associate's in Computer Programming  
- **CS 130:** x86 Assembly (MASM), memory/register manipulation  
- **CS 216:** C++ OOP, classes, inheritance, exception handling  
- **CS 112:** JavaScript, DOM scripting, async validation

### Associate's in Cybersecurity  
- **CIS 215:** Network security, packet analysis, firewall config  
- **CIS 219:** Secure SQL development, parameterized queries  
- **CIS 165:** CIA triad, NIST/ISO, risk assessment

### Bachelor's in Computer Information Technology (in progress)  
- **CIT 270/L:** Cloud scripting, integration (Python, VBScript, XML)  
- **COMP 529/L:** Distributed systems, client-server sockets, concurrency  
- **COMP 584:** Web security, OWASP Top 10, static/dynamic analysis

---

## 🔨 Lab Repositories (In Progress)

### 🔍 macOS Entitlement Audit (Apr 2025 – Present)
- Audited entitlements for 15+ macOS Sonoma applications using Terminal and codesign utilities.
- Extracted and reviewed sandbox permissions for sensitive access like camera, microphone, and file systems.
- Identified 8 apps with elevated privileges inconsistent with least-privilege best practices.
- Correlated permission risks to common macOS misconfigurations and platform security gaps.
- Developed a findings report with 3 mitigation strategies to minimize application attack surfaces.  
**Skills:** *Application Security · macOS Security · Sandboxing · Vulnerability Assessment · Permission Auditing · Risk Analysis · Static Analysis*

  - <span style="color:red">[macOS Entitlement Audit](https://github.com/iobsec/macos-entitlement-audit)</span>  

---

### 🌐 Network Detection Lab (Feb 2025 – Present)
- Deployed Suricata IDS in a Linux virtual machine to monitor and detect inbound network traffic.
- Simulated SYN scans, service enumeration, and reverse shell attacks from a Windows VM using Nmap and Netcat.
- Captured and analyzed 30+ security events to strengthen traffic inspection and alert interpretation.
- Tuned Suricata rule sets to improve detection rates and reduce false positives during simulations.
- Created a structured event report summarizing detected attack patterns and defense recommendations.  
**Skills:** *Suricata · Network Security · Intrusion Detection · Threat Detection · Traffic Analysis · Linux Security · Security Event Analysis*

  - <span style="color:red">[Network Detection Lab](https://github.com/iobsec/network-detection-lab)</span>  

---

### 🧰 Cybersecurity HomeLab Development (Jan 2024 – Apr 2024)
- Designed VirtualBox lab environment to simulate real-world cybersecurity scenarios and attacks.
- Integrated Security Onion to aggregate and analyze logs for network security monitoring.
- Deployed Ubuntu VM for in-depth log analysis and incident response investigations.
- Configured Kali Linux for testing security measures and conducting penetration testing exercises.
- Provisioned vulnerable machines including Windows Server 2016 and Linux MintOS for exploitation practice.
- Monitored network traffic and security logs, identifying and mitigating simulated vulnerabilities.  
**Skills:** *Network Security Management · Incident Response · Penetration Testing · Vulnerability Assessment · Log Analysis*

- <span style="color:red">[Cybersecurity HomeLab](https://github.com/iobsec/cybersecurity-homelab)</span>  

---

### 🦠 Malware Analysis Lab (Nov 2023 – Jan 2024)
- Conducted malware analysis in a controlled VirtualBox environment for isolation and safety.
- Utilized REMnux and FlareVM to analyze various malware samples and document IOCs.
- Assessed system-level impact of malware behavior on performance and persistence.
- Developed mitigation strategies based on findings to enhance organizational response posture.  
**Skills:** *Reverse Engineering · Incident Response · Malware Analysis · CTI · Static/Dynamic Analysis · System Performance Forensics*

- <span style="color:red">[Malware Analysis Lab](https://github.com/iobsec/malware-analysis-lab)</span>  

---

### 🧑‍💼 Help Desk Simulation (Apr 2022 – Aug 2022)
- Created multi-OS VM lab with Windows, macOS, and Linux environments for helpdesk scenarios.
- Configured Zendesk for ticket generation, resolution workflow, and performance reporting.
- Simulated software install issues, VPN errors, and network connectivity problems.
- Practiced customer support strategies, technical triage, and business process improvement.  
**Skills:** *Multi-OS Troubleshooting · VPN Support · Ticketing Systems · Customer Experience · IT Operations*

  - <span style="color:red">[Help Desk Simulation](https://github.com/iobsec/helpdesk-simulation)</span>  

---

### 🖥️ Windows Server 2016 System Administration (Mar 2021 – May 2021)
- Deployed Windows Server 2016 in VirtualBox to simulate domain network environments.
- Configured Active Directory Domain Services (AD DS) and created users, OUs, and GPOs.
- Linked DNS to internal network and implemented Windows Server Backup for recovery.
- Enforced security policies and structured domain with effective backup strategy.  
**Skills:** *OS Virtualization · Active Directory · Group Policy · DNS · Backup & Recovery · Windows Server*

- <span style="color:red">[Windows Server 2016 Admin](https://github.com/iobsec/windows-server-2016-admin)</span>

---

<p align="center"><strong>“Offense informs defense. Defense
