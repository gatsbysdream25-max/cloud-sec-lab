# cloud-sec-lab
Home Security lab for cloud training 
# Shane Barnett - Cloud Security Engineer Portfolio

> **Transitioning from infrastructure/construction background to cloud security engineering**  
> **Focus:** Azure Security | Network Security | Penetration Testing | SIEM

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://linkedin.com/in/shane-barnett)
[![Email](https://img.shields.io/badge/Email-barnett.shane.t%40gmail.com-red)](mailto:barnett.shane.t@gmail.com)

---

## 👨‍💻 About Me

Cloud Security Engineer with hands-on experience building enterprise-grade security infrastructure. Former electrician and Combat Engineer (Ohio Army National Guard) transitioning technical infrastructure knowledge into cybersecurity specialization.

**Current Status:** Pursuing Azure Security Engineer certifications (AZ-900 → AZ-104 → AZ-500)

**Location:** Hillsboro, Ohio | **Clearance Eligible:** Veteran Status

---

## 🎯 Technical Skills

### Cloud & Security
- **Cloud Platforms:** Microsoft Azure (Security, Networking, IAM)
- **Security Tools:** Pi-hole, Graylog SIEM, WireGuard VPN, DVWA, Fail2ban
- **Network Security:** DNS Security, VPN Configuration, Intrusion Detection
- **Penetration Testing:** OWASP Top 10, Web Application Security

### Infrastructure & Systems
- **Operating Systems:** Linux (Ubuntu, Debian, Kali), Windows Server
- **Containerization:** Docker, Docker Compose
- **Networking:** TCP/IP, DNS, DHCP, VPN, Network Segmentation
- **Scripting:** Bash, PowerShell, (Python - learning)

### Compliance & Frameworks
- **Frameworks:** NIST Cybersecurity Framework, ISO 27001 concepts
- **Standards:** HIPAA awareness, Security best practices

---

## 🏗️ Home Security Lab Projects

### **Project 1: Pi-hole DNS Security & Monitoring**
**Platform:** Raspberry Pi 4 | **Status:** ✅ Production

**What I Built:**
- Deployed Pi-hole DNS server for network-wide security monitoring
- Configured static IP addressing and network integration
- Implemented DNS-level ad blocking and malicious domain filtering
- Set up real-time query logging for threat analysis

**Skills Demonstrated:**
- DNS security architecture
- Network traffic analysis
- Linux system administration
- Service configuration and management

**Access:** `http://192.168.0.207/admin`

**Key Metrics:**
- Real-time DNS query monitoring
- Blocked malicious domains tracking
- Network-wide protection for all devices

---

### **Project 2: Graylog SIEM Implementation**
**Platform:** Docker | **Status:** ✅ Production

**What I Built:**
- Deployed Graylog SIEM using Docker containerization
- Configured MongoDB for data storage
- Set up Elasticsearch for log indexing and search
- Created log inputs for centralized aggregation
- Configured syslog collection from multiple sources

**Skills Demonstrated:**
- SIEM deployment and configuration
- Docker containerization
- Log aggregation and analysis
- Security event correlation
- Infrastructure monitoring

**Access:** `http://192.168.0.207:9000`

**Technical Stack:**
- Graylog 5.0
- Elasticsearch OSS 7.10.2
- MongoDB 5.0
- Docker Compose orchestration

---

### **Project 3: WireGuard VPN Infrastructure**
**Platform:** Raspberry Pi 4 | **Status:** ✅ Production

**What I Built:**
- Deployed WireGuard VPN server for encrypted remote access
- Configured secure peer-to-peer tunneling
- Integrated with Pi-hole for DNS-level security on VPN traffic
- Set up routing to force all traffic through security stack

**Skills Demonstrated:**
- VPN architecture and deployment
- Network encryption protocols
- Secure remote access configuration
- Network routing and tunneling

**Security Benefits:**
- Encrypted traffic for remote connections
- DNS security via Pi-hole integration
- Secure access to home lab environment
- Network traffic monitoring for VPN users

---

### **Project 4: DVWA Penetration Testing Lab**
**Platform:** Apache + MariaDB | **Status:** ✅ Production

**What I Built:**
- Deployed Damn Vulnerable Web Application (DVWA) for security testing
- Configured Apache web server on alternate port (8080)
- Set up MariaDB database backend
- Created isolated testing environment for vulnerability research

**Skills Demonstrated:**
- Web application security testing
- OWASP Top 10 vulnerability assessment
- SQL Injection techniques
- Cross-Site Scripting (XSS) testing
- Command Injection exploitation
- Security report documentation

**Access:** `http://192.168.0.207:8080/DVWA`

**Testing Capabilities:**
- SQL Injection (various bypass techniques)
- XSS (Reflected, Stored, DOM-based)
- Command Injection
- File Upload vulnerabilities
- Authentication bypass
- CSRF attacks

---

### **Project 5: Fail2ban Intrusion Prevention**
**Platform:** Linux | **Status:** ✅ Production

**What I Built:**
- Deployed fail2ban for automated intrusion prevention
- Configured SSH brute-force protection
- Set up automated IP banning for suspicious activity
- Created monitoring for failed authentication attempts

**Skills Demonstrated:**
- Intrusion detection and prevention
- Automated threat response
- Security monitoring
- Attack pattern recognition

**Protection Capabilities:**
- Real-time SSH brute-force prevention
- Automated IP blacklisting
- Failed authentication tracking
- Alert generation for security events

---

## 🏆 Certifications

### **Completed:**
- ✅ **Microsoft 365 Fundamentals (MS-900)** - 2024
- ✅ **OSHA 10-Hour Safety Certification**

### **In Progress:**
- 🔄 **Azure Fundamentals (AZ-900)** - Expected March 2026

### **Planned (2026):**
- 📅 **Azure Administrator Associate (AZ-104)** - Q1 2026
- 📅 **Azure Security Engineer Associate (AZ-500)** - Q2 2026
- 📅 **CISSP** - Long-term goal

---

## 💼 Professional Experience Highlights

### **Unique Background:**
- **Infrastructure Expertise:** Electrician with structured cabling experience (CAT5/CAT6, network termination, testing)
- **Security Mindset:** Combat Engineer (Ohio Army National Guard 2010-2016)
- **Enterprise Exposure:** Former Logistics Account Executive at Total Quality Logistics (TQL)
- **Business Acumen:** Self-employed contractor (2018-Present)

### **Transferable Skills:**
- Physical + logical infrastructure understanding
- Security-first operational approach (military training)
- Enterprise environment exposure (Fortune 500)
- Project management and client communication
- Systematic troubleshooting methodology

---

## 📊 Lab Architecture

```
Internet
    |
    ├── WireGuard VPN Server (Raspberry Pi 4)
    |   └── Encrypted Tunnel
    |
Home Router (192.168.0.1)
    |
    ├── Raspberry Pi 4 (192.168.0.207)
    |   ├── Pi-hole DNS (Port 80)
    |   |   └── DNS Filtering & Monitoring
    |   |
    |   ├── Graylog SIEM (Port 9000)
    |   |   ├── MongoDB (Database)
    |   |   ├── Elasticsearch (Indexing)
    |   |   └── Log Aggregation
    |   |
    |   ├── DVWA (Port 8080)
    |   |   ├── Apache Web Server
    |   |   ├── MariaDB Database
    |   |   └── Vulnerable Web App
    |   |
    |   ├── WireGuard VPN
    |   |   └── Encrypted Remote Access
    |   |
    |   └── Fail2ban
    |       └── Intrusion Prevention
    |
    └── Desktop PC (192.168.0.x)
        ├── VirtualBox VMs:
        |   ├── Ubuntu (Development)
        |   ├── Kali Linux (Penetration Testing)
        |   └── Windows 10 (Testing)
        |
        └── Traffic routes through Pi-hole DNS
```

---

## 🎓 Learning & Development

### **Current Learning Path:**
1. **Azure Fundamentals (AZ-900)** - In progress
2. **Azure Administrator (AZ-104)** - Next (Q1 2026)
3. **Azure Security Engineer (AZ-500)** - Target (Q2 2026)

### **Hands-On Practice:**
- Daily security lab operations and monitoring
- Regular penetration testing practice (DVWA)
- Log analysis and SIEM tuning (Graylog)
- Network traffic analysis (Pi-hole)

### **Community Engagement:**
- Mentoring peers in virtualization and Linux configuration
- Documenting projects for knowledge sharing
- Building portfolio for career transition

---

## 📈 Career Goals

### **Immediate (2026):**
- Complete Azure security certification path (AZ-900 → AZ-104 → AZ-500)
- Secure Cloud Security Engineer role at enterprise company
- Target companies: TQL (former employer), GE Aerospace, Adena Health

### **Mid-Term (3-5 years):**
- Senior Cloud Security Engineer position
- Security clearance (leveraging veteran status)
- Specialized expertise in Azure security architecture

### **Long-Term (10 years):**
- Security Architect or Principal Security Engineer
- CISSP certification
- Thought leadership in cloud security

---

## 📫 Contact & Links

- **Email:** barnett.shane.t@gmail.com
- **LinkedIn:** [linkedin.com/in/shane-barnett](#) *(update with your actual LinkedIn)*
- **Location:** Hillsboro, Ohio 45133
- **Phone:** Available upon request

---

## 📝 Documentation & Resources

### **Project Documentation:**
Each project includes:
- Architecture diagrams
- Configuration files
- Setup instructions
- Lessons learned
- Security findings

### **Screenshots & Evidence:**
- Pi-hole dashboard showing DNS query monitoring
- Graylog SIEM interface with log aggregation
- DVWA penetration test reports
- Network traffic analysis examples

---

## 🚀 Why Hire Me?

**Unique Value Proposition:**

1. **Rare Skill Combination:**
   - Infrastructure knowledge (electrician/cabling) + Cloud security expertise
   - Physical security understanding (military) + Logical security implementation
   - Enterprise operations exposure (TQL) + Technical security skills

2. **Self-Starter with Proven Initiative:**
   - Built complete security lab independently
   - Self-funded certification path
   - Demonstrated continuous learning

3. **Security-First Mindset:**
   - Military training in operational security
   - Hands-on penetration testing experience
   - SIEM and monitoring expertise

4. **Business Understanding:**
   - Former enterprise employee (TQL - Fortune 500)
   - Self-employed contractor (project management, client relations)
   - Understands security impact on business operations

5. **Clearance Eligible:**
   - Veteran status (Combat Engineer, Ohio Army National Guard)
   - No security concerns
   - Ideal for defense/government contractors

---

## 📊 Lab Statistics

**Environment:**
- **Platform:** Raspberry Pi 4 (8GB RAM, 64GB Storage)
- **Operating System:** Raspberry Pi OS (64-bit Debian-based)
- **Uptime:** 24/7 production environment
- **Network:** Isolated lab network with VPN access

**Metrics:**
- DNS queries monitored: Thousands daily
- Logs aggregated: All system and application logs
- Penetration tests conducted: Ongoing OWASP Top 10 practice
- Security tools deployed: 5+ enterprise-grade solutions

---

## 🔒 Security & Compliance

**Lab Security Measures:**
- Static IP addressing
- Fail2ban intrusion prevention
- VPN-only remote access (WireGuard)
- Regular system updates
- Isolated testing environment (DVWA)
- Encrypted traffic (WireGuard VPN)

**Compliance Awareness:**
- NIST Cybersecurity Framework alignment
- HIPAA concepts (relevant for healthcare targets)
- ISO 27001 security controls
- OWASP Top 10 vulnerability testing

---

## 🛠️ Future Lab Enhancements

**Planned Additions:**
- [ ] Netdata real-time monitoring dashboard
- [ ] Portainer container management UI
- [ ] Grafana visualization for Pi-hole metrics
- [ ] Additional OWASP testing tools
- [ ] Automated threat intelligence feeds
- [ ] Security alert automation

**Azure Cloud Integration (Future):**
- [ ] Azure Sentinel SIEM integration
- [ ] Azure Security Center deployment
- [ ] Hybrid cloud security architecture
- [ ] Azure-based penetration testing lab

---

## 📚 References & Resources

**Tools & Technologies Used:**
- [Pi-hole](https://pi-hole.net/) - Network-wide ad blocking and DNS security
- [Graylog](https://www.graylog.org/) - Open source log management and SIEM
- [WireGuard](https://www.wireguard.com/) - Fast, modern VPN protocol
- [DVWA](https://dvwa.co.uk/) - Damn Vulnerable Web Application for security testing
- [Fail2ban](https://www.fail2ban.org/) - Intrusion prevention software

**Learning Resources:**
- Microsoft Learn (Azure certification paths)
- OWASP Testing Guide
- NIST Cybersecurity Framework
- Raspberry Pi documentation

---

**Last Updated:** February 15, 2026

**Note:** This lab represents ongoing professional development and is actively maintained for continuous learning and skill enhancement in cloud security engineering.

---

*This portfolio demonstrates hands-on security engineering capabilities, self-directed learning, and practical implementation of enterprise security tools. All projects are documented, tested, and production-ready.*
