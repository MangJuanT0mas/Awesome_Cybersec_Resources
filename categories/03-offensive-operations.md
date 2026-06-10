# Offensive Operations (Red Team) 🔴

Comprehensive guide to offensive security tools, frameworks, techniques, and resources for red team operations and penetration testing.

---

## Table of Contents

- [Offensive Frameworks & Methodologies](#offensive-frameworks--methodologies)
- [Exploitation Platforms & Tools](#exploitation-platforms--tools)
- [Reconnaissance & Enumeration](#reconnaissance--enumeration)
- [Exploitation & Weaponization](#exploitation--weaponization)
- [Post-Exploitation & Privilege Escalation](#post-exploitation--privilege-escalation)
- [Social Engineering](#social-engineering)
- [Evasion Techniques](#evasion-techniques)
- [Red Team Infrastructure](#red-team-infrastructure)
- [Learning Resources](#learning-resources)

---

## 🎯 Offensive Frameworks & Methodologies

### **RedTeamGarage**
- **URL**: https://www.redteamgarage.com/
- **Description**: Educational resource covering red team operations, threat methodologies, attack techniques, and operational security
- **Type**: Blog / Educational Resource
- **Level**: 🔴 Advanced
- **Cost**: Free
- **Topics Cover**:
  - Red team planning and execution
  - Threat simulation
  - TTPs (Tactics, Techniques, Procedures)
  - Adversary emulation
  - Defensive bypass techniques
- **Best For**: Understanding red team perspective and operations

### **MITRE ATT&CK Framework**
- **URL**: https://attack.mitre.org/
- **Description**: Comprehensive database of adversary tactics, techniques, and procedures based on real-world observations
- **Type**: Framework / Knowledge Base
- **Level**: 🟡 Intermediate - 🔴 Advanced
- **Cost**: Free
- **Coverage**:
  - Enterprise tactics (15 categories)
  - Mobile tactics
  - ICS (Industrial Control Systems)
  - Data sources and detection
  - Mitigations
- **Use**: Foundation for red team operations planning
- **Best For**: Understanding attack techniques and TTPs

### **Cyber Kill Chain**
- **URL**: https://www.eccouncil.org/cybersecurity-exchange/threat-intelligence/cyber-kill-chain-seven-steps-cyberattack/
- **Description**: Seven-stage attack framework for planning and executing coordinated attacks
- **Type**: Framework / Methodology
- **Level**: 🟡 Intermediate
- **Cost**: Free
- **Stages**:
  1. Reconnaissance
  2. Weaponization
  3. Delivery
  4. Exploitation
  5. Installation
  6. Command & Control
  7. Actions on Objectives
- **Best For**: Understanding complete attack lifecycle

### **NIST Cybersecurity Framework**
- **URL**: https://csrc.nist.gov/
- **Description**: National framework for managing cybersecurity risk (useful for understanding defensive measures to bypass)
- **Type**: Framework / Guidelines
- **Level**: 🟡 Intermediate
- **Cost**: Free
- **Functions**:
  - Identify
  - Protect
  - Detect
  - Respond
  - Recover
- **Best For**: Understanding defensive strategies to counter

---

## 🛠️ Exploitation Platforms & Tools

### **Metasploit Framework**
- **URL**: https://www.metasploit.com/
- **Description**: Open-source penetration testing framework with 3000+ exploits, payloads, and auxiliary modules
- **Type**: Framework / Tool
- **Level**: 🟡 Intermediate - 🔴 Advanced
- **Cost**: Free (Pro version available)
- **Features**:
  - Exploit development
  - Payload creation
  - Post-exploitation modules
  - Evasion techniques
  - Msfconsole interface
  - Database integration
  - Community modules
- **Learning**: Official documentation, YouTube tutorials, courses
- **Best For**: Structured exploitation and payload delivery

### **Burp Suite**
- **URL**: https://portswigger.net/burp
- **Description**: Web application security testing platform with proxy, scanner, and exploitation tools
- **Type**: Web Testing Tool
- **Level**: 🟡 Intermediate - 🔴 Advanced
- **Cost**: Freemium (Community edition free)
- **Modules**:
  - Proxy
  - Scanner
  - Intruder
  - Repeater
  - Decoder
  - Comparer
  - Extender
- **Use Cases**: Web app testing, API testing, manual exploitation
- **Best For**: Comprehensive web security testing

### **Nikto**
- **URL**: https://github.com/sullo/nikto
- **Description**: Web server scanner for detecting outdated software, security misconfigurations, and default credentials
- **Type**: Scanner / Tool
- **Level**: 🟢 Beginner - 🟡 Intermediate
- **Cost**: Free / Open Source
- **Capabilities**:
  - Server detection
  - Plugin-based scanning
  - Certificate analysis
  - Subdomain enumeration
  - CGI scanning
- **Use**: Quick web server assessment
- **Best For**: Initial web server reconnaissance

### **SQLMap**
- **URL**: https://sqlmap.org/
- **Description**: Automated SQL injection testing tool for detecting and exploiting SQL injection vulnerabilities
- **Type**: Exploitation Tool
- **Level**: 🟡 Intermediate
- **Cost**: Free / Open Source
- **Features**:
  - Automatic SQL injection detection
  - Database enumeration
  - Table dumping
  - User privilege checking
  - File system access
  - OS command execution
- **Best For**: SQL injection exploitation

### **XCel-Rat & Empire**
- **Description**: Command and control (C2) frameworks for post-exploitation
- **Empire**: PowerShell-based C2 agent
- **Level**: 🔴 Advanced
- **Cost**: Free / Open Source
- **Use**: Post-exploitation control and data exfiltration

---

## 🔍 Reconnaissance & Enumeration

### **Nmap & NSE Scripts**
- **URL**: https://nmap.org/
- **Description**: Network mapper and security scanner with powerful scripting capabilities
- **Type**: Scanner / Tool
- **Level**: 🟡 Intermediate - 🔴 Advanced
- **Cost**: Free / Open Source
- **Capabilities**:
  - Port scanning
  - Service detection
  - OS fingerprinting
  - Vulnerability scanning (with NSE scripts)
  - Network enumeration
- **NSE Scripts**: https://nmap.org/nsedoc/scripts/
- **Use Cases**: Network reconnaissance, service enumeration
- **Best For**: Network discovery and enumeration

### **OSINT Framework**
- **URL**: https://osintframework.com/
- **Description**: Comprehensive OSINT framework linking to tools for intelligence gathering from public sources
- **Type**: Framework / Resource Collection
- **Level**: 🟡 Intermediate
- **Cost**: Free
- **Categories**:
  - Username searches
  - Email searches
  - Domain research
  - IP information
  - Phone number lookup
  - Document metadata
  - Image analysis
  - Social media investigation
- **Best For**: Open-source intelligence gathering

### **Sploitus**
- **URL**: https://sploitus.com/
- **Description**: Search engine for finding exploits, tools, and POC code for known vulnerabilities
- **Type**: Search Engine / Tool Aggregator
- **Level**: 🟡 Intermediate
- **Cost**: Free
- **Searches**: Exploits, tools, POCs for CVEs
- **Best For**: Finding working exploit POCs

### **Shodan**
- **URL**: https://www.shodan.io/
- **Description**: Search engine for internet-connected devices and services
- **Type**: Search Engine
- **Level**: 🟡 Intermediate - 🔴 Advanced
- **Cost**: Freemium
- **Features**:
  - Device discovery
  - Vulnerability identification
  - Exposed services
  - Infrastructure mapping
  - Alerts for changes
- **Use Cases**: Target reconnaissance, vulnerability discovery
- **Best For**: Finding exposed vulnerable infrastructure

### **TheHarvester**
- **URL**: https://github.com/laramies/theHarvester
- **Description**: Email and subdomain enumeration tool for gathering information about targets
- **Type**: OSINT Tool
- **Level**: 🟡 Intermediate
- **Cost**: Free / Open Source
- **Features**:
  - Email harvesting
  - Subdomain enumeration
  - Virtual host detection
  - Employee name identification
- **Best For**: Passive information gathering

---

## ⚔️ Exploitation & Weaponization

### **HackTricks - Pentest Guides**
- **URL**: https://book.hacktricks.xyz/
- **Description**: Comprehensive guide for penetration testing techniques, payloads, and exploitation methods
- **Type**: Guide / Reference
- **Level**: 🟡 Intermediate - 🔴 Advanced
- **Cost**: Free
- **Topics**:
  - Initial access techniques
  - Privilege escalation
  - Persistence mechanisms
  - Evasion techniques
  - Post-exploitation
  - C2 frameworks
- **Best For**: Quick reference during engagements

### **Mimikatz**
- **URL**: https://github.com/gentilkiwi/mimikatz
- **Description**: Tool for extracting credentials from Windows memory
- **Type**: Post-Exploitation Tool
- **Level**: 🔴 Advanced
- **Cost**: Free / Open Source
- **Capabilities**:
  - Credential dumping
  - LSASS process manipulation
  - Token elevation
  - Kerberos ticket manipulation
- **Use**: Windows credential extraction and privilege escalation

### **Cobalt Strike**
- **URL**: https://www.cobaltstrike.com/
- **Description**: Commercial adversary simulation platform for red team operations (used in real attacks)
- **Type**: C2 / Red Team Platform
- **Level**: 🔴 Advanced
- **Cost**: Paid (~$3,500/year)
- **Features**:
  - Advanced C2 capabilities
  - Payload generation
  - Post-exploitation modules
  - Evasion techniques
  - Team server architecture
- **Best For**: Professional red team operations

### **PowerShell Empire**
- **URL**: https://github.com/BC-SECURITY/Empire
- **Description**: PowerShell-based command and control framework for post-exploitation
- **Type**: C2 Framework
- **Level**: 🔴 Advanced
- **Cost**: Free / Open Source
- **Features**:
  - Agent-based architecture
  - Task scheduling
  - Credentials management
  - Lateral movement
  - Data exfiltration
- **Best For**: Windows post-exploitation

---

## 📈 Post-Exploitation & Privilege Escalation

### **Privilege Escalation Guides**

**Windows Privilege Escalation**
- Kernel exploits
- Weak ACLs
- Service misconfigurations
- Registry manipulation
- Token impersonation
- UAC bypass

**Linux Privilege Escalation**
- SUID binaries
- Sudo misconfigurations
- Kernel exploits
- Cron job abuse
- Library hijacking
- Capability exploitation

### **LOLBAS (Living Off The Land Binaries And Scripts)**
- **URL**: https://lolbas-project.github.io/
- **Description**: Database of legitimate Windows binaries that can be used for attack purposes
- **Type**: Resource / Reference
- **Level**: 🟡 Intermediate - 🔴 Advanced
- **Cost**: Free
- **Purpose**: Fileless attack techniques using built-in tools
- **Best For**: Evasion and anti-forensics

### **GTFOBins**
- **URL**: https://gtfobins.github.io/
- **Description**: Database of Unix binaries that can be exploited for privilege escalation
- **Type**: Resource / Reference
- **Level**: 🟡 Intermediate - 🔴 Advanced
- **Cost**: Free
- **Use**: Privilege escalation techniques on Linux systems

### **Enum4Linux**
- **URL**: https://github.com/CiscoCXSecurity/enum4linux
- **Description**: SMB/LDAP enumeration tool for Windows domain enumeration
- **Type**: Enumeration Tool
- **Level**: 🟡 Intermediate
- **Cost**: Free / Open Source
- **Capabilities**:
  - User enumeration
  - Share enumeration
  - Password policy extraction
  - Group membership
  - RID cycling

---

## 👤 Social Engineering

### **Phishing & Awareness**

**SEToolkit (Social Engineering Toolkit)**
- **URL**: https://github.com/trustedsec/social-engineer-toolkit
- Automated phishing attacks and social engineering
- Used for red team engagements and security awareness

### **Techniques**
- Credential harvesting
- Phishing email campaigns
- Clone and host websites
- Payload injection
- Man-in-the-middle attacks

### **Prevention & Detection**
- Security awareness training
- Email filtering and monitoring
- User vigilance
- MFA implementation
- Threat simulation exercises

---

## 🛡️ Evasion Techniques

### **Antivirus Evasion**
- Obfuscation
- Polymorphic code
- Encryption
- Code injection
- Process hollowing
- DLL side-loading

### **EDR Evasion**
- Living off the land
- Detection rule bypass
- Behavior randomization
- API hooking bypass
- Memory manipulation

### **Network Evasion**
- DNS tunneling
- Encrypted communications
- Traffic shaping
- Proxy chains
- VPN/Tor usage

### **Detection Evasion Tools**
- Veil-Evasion
- Shellter
- Crypter tools
- Custom encode/decode

---

## 🏗️ Red Team Infrastructure

### **Command & Control (C2) Infrastructure**

**Components**
- C2 Server (Cobalt Strike, Empire, Sliver)
- Redirectors and proxies
- Domain fronting
- HTTPS/DNS tunneling
- Dead drop servers

### **Operational Security (OPSEC)**
- Infrastructure compartmentalization
- Domain registration
- VPS/server management
- Logging and monitoring
- Cleanup and sanitization

### **Tool Resources**
- **Mythic**: Modern C2 framework
- **Sliver**: Golang-based C2
- **Havoc**: Advanced red team framework

---

## 📚 Learning Resources

### **Red Team Books**
- "The Hacker Playbook" series
- "Red Team Field Manual (RTFM)"
- "Adversary Playbook"
- "Advanced Penetration Testing"

### **Online Training**
- Offensive Security Courses (OSCP, OSEE)
- Red Team Academy
- Cybrary red team paths
- YouTube channels (IppSec, John Hammond)

### **Certifications to Pursue**
- OSCP (Offensive Security Certified Professional)
- CEH (Certified Ethical Hacker)
- GPEN (GIAC Penetration Tester)
- ECIH (EC-Council Certified Incident Handler)

---

## ⚠️ Ethical Considerations

**Important Reminders:**
- ✅ Only conduct authorized testing
- ✅ Follow rules of engagement
- ✅ Maintain proper documentation
- ✅ Report findings responsibly
- ✅ Respect legal boundaries
- ❌ Never exceed scope
- ❌ Never use for illegal purposes
- ❌ Never harm systems without authorization

---

## 🔗 Quick Reference

| Tool | Purpose | Level |
|------|---------|-------|
| Metasploit | Framework | Intermediate |
| Burp Suite | Web Testing | Intermediate |
| Nmap | Reconnaissance | Intermediate |
| SQLMap | SQL Injection | Intermediate |
| Mimikatz | Credential Dumping | Advanced |
| Cobalt Strike | C2 | Advanced |
| HackTricks | Reference | Advanced |

---

**Last Updated**: June 2026  
**Status**: 🟢 Active - Regular Updates

*Have offensive security resources to share? Please contribute!* See [CONTRIBUTING.md](../../CONTRIBUTING.md)

**Remember**: With great power comes great responsibility. Use these tools and techniques ethically and legally.
