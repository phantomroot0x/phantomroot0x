 
<!-- =====================================================
     MUHAMMAD ZUBAIR | CYBERSECURITY PORTFOLIO
     GitHub: phantomroot0x
     Theme: Terminal Green + Bento Grid + Cyberpunk
===================================================== -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:001a0d,50:003b20,100:00ff66&height=180&section=header&text=PHANTOMROOT0X&fontSize=48&fontColor=00ff66&animation=fadeIn&fontAlignY=38&desc=CYBERSECURITY%20%7C%20SOC%20%7C%20BLUE%20TEAM%20%7C%20DFIR&descSize=14&descAlignY=60&descColor=ccffdd" width="100%"/>

<br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1200&color=00FF66&center=true&vCenter=true&width=650&lines=Hello%2C+I'm+Muhammad+Zubair;Computer+Science+Student;SOC+%7C+Blue+Team+%7C+Network+Security;Malware+Analysis+%7C+DFIR;Learn.+Build.+Analyze.+Document." alt="Typing SVG"/>

</div>

---

## `01 // SYSTEM IDENTITY`

```bash
┌──(phantomroot0x㉿kali)-[~]
└─$ whoami

Muhammad Zubair

┌──(phantomroot0x㉿kali)-[~]
└─$ cat profile.txt

ROLE       : Computer Science Student
UNIVERSITY : University of Buner
FIELD      : Cybersecurity
FOCUS      : SOC | Blue Team | Network Security
INTERESTS  : Malware Analysis | DFIR | Threat Intelligence
OBJECTIVE  : Building practical defensive security expertise
```

I'm a **Computer Science student** developing practical cybersecurity skills through security operations training, hands-on labs, technical projects, and security investigations.

My primary focus is understanding how security events are detected, investigated, correlated, and documented.

I believe effective security analysis requires more than knowing security tools. It requires understanding the underlying technologies, interpreting evidence, and making defensible technical conclusions.

---

## `02 // SECURITY OPERATIONS`

<div align="center">

| 🛡️ SOC & BLUE TEAM | 🌐 NETWORK SECURITY |
|:---:|:---:|
| Security Monitoring | Network Traffic Analysis |
| Threat Detection | IDS / IPS |
| Alert Investigation | DNS / HTTP / TLS |
| Incident Response | PCAP Analysis |

| 🦠 MALWARE ANALYSIS | 🔎 DFIR |
|:---:|:---:|
| Static Analysis | Evidence Collection |
| PE Investigation | IOC Extraction |
| Entropy Analysis | Incident Investigation |
| Threat Intelligence | Technical Documentation |

</div>

---

## `03 // FEATURED OPERATIONS`

### 🦠 OPERATION 01 — WINDOWS MALWARE ANALYSIS & IR

<details open>
<summary><b>View Investigation Details</b></summary>

**Repository:** [windows-malware-analysis-ir](https://github.com/phantomroot0x/windows-malware-analysis-ir)

A practical Windows malware investigation project focused on suspicious PE executables, static analysis, file characteristics, entropy investigation, and threat intelligence enrichment.

**Investigation capabilities:**

- PE file structure and metadata analysis
- File hashing and identification
- String extraction and investigation
- Section entropy analysis
- Overlay analysis
- Digital signature verification
- VirusTotal intelligence enrichment
- MalwareBazaar sample investigation
- IOC extraction and documentation
- Incident response methodology

**Tools:** PEStudio, Detect It Easy, TrID, Strings, CertUtil, VirusTotal, MalwareBazaar.

**[↗ Explore Repository](https://github.com/phantomroot0x/windows-malware-analysis-ir)**

</details>

---

### 🛡️ OPERATION 02 — SURICATA + ZEEK NETWORK SECURITY MONITORING

<details open>
<summary><b>View Network Security Lab</b></summary>

**Repository:** [suricata-zeek-network-security-monitoring](https://github.com/phantomroot0x/suricata-zeek-network-security-monitoring)

A hands-on Network Security Monitoring environment combining Suricata IDS/IPS and Zeek for traffic inspection, suspicious activity detection, and network event investigation.

**Implemented activities:**

- Suricata IDS/IPS deployment
- Emerging Threats rule management
- Custom detection rule development
- TLS-SNI detection
- NFQUEUE-based IPS testing
- `fast.log` investigation
- `eve.json` event analysis
- Zeek HTTP analysis
- DNS monitoring
- TLS traffic investigation
- PCAP analysis
- Nmap traffic investigation
- Suricata and Zeek event correlation

**Tools:** Suricata, Zeek, Wireshark, Nmap, Linux.

**[↗ Explore Repository](https://github.com/phantomroot0x/suricata-zeek-network-security-monitoring)**

</details>

---

### 🔐 OPERATION 03 — PHISHGUARD

<details>
<summary><b>View Project Details</b></summary>

**Repository:** [phishguard](https://github.com/phantomroot0x/phishguard)

A Python-based phishing analysis project designed to evaluate suspicious messages and URLs using sender information, suspicious keywords, URL characteristics, and risk scoring.

**Key concepts:**

- Phishing indicators
- Suspicious URL analysis
- Sender analysis
- Keyword-based detection
- Risk scoring
- Basic security automation

**[↗ Explore Repository](https://github.com/phantomroot0x/phishguard)**

</details>

---

### 🔑 OPERATION 04 — PASSWORD STRENGTH CHECKER

<details>
<summary><b>View Project Details</b></summary>

**Repository:** [password-strength-checker](https://github.com/phantomroot0x/password-strength-checker)

A Python security utility that evaluates password strength using entropy calculations, password length, and character diversity.

**Key concepts:**

- Password entropy
- Character diversity
- Strength evaluation
- Python CLI development
- Basic cryptographic concepts

**[↗ Explore Repository](https://github.com/phantomroot0x/password-strength-checker)**

</details>

---

## `04 // SECURITY LAB ARCHITECTURE`

My practical learning environment combines network monitoring, intrusion detection, and centralized security event analysis.

<div align="center">

```text
                  ┌──────────────────┐
                  │    KALI LINUX    │
                  │  Traffic Source  │
                  └────────┬─────────┘
                           │
                    NETWORK TRAFFIC
                           │
              ┌────────────┴────────────┐
              │                         │
       ┌──────▼───────┐          ┌──────▼──────┐
       │  SURICATA    │          │    ZEEK     │
       │   IDS / IPS  │          │     NSM     │
       └──────┬───────┘          └──────┬──────┘
              │                         │
              └────────────┬────────────┘
                           │
                    SECURITY EVENTS
                           │
                    ┌──────▼──────┐
                    │    WAZUH    │
                    │ SIEM / XDR  │
                    └──────┬──────┘
                           │
                  DETECTION & ANALYSIS
                           │
                    ┌──────▼──────┐
                    │ INVESTIGATION│
                    │  & RESPONSE  │
                    └─────────────┘
```

</div>

---

## `05 // TECHNICAL ARSENAL`

### 💻 Programming & Development

![Python](https://img.shields.io/badge/Python-001a0d?style=for-the-badge&logo=python&logoColor=00ff66)
![Bash](https://img.shields.io/badge/Bash-001a0d?style=for-the-badge&logo=gnubash&logoColor=00ff66)
![Git](https://img.shields.io/badge/Git-001a0d?style=for-the-badge&logo=git&logoColor=00ff66)
![GitHub](https://img.shields.io/badge/GitHub-001a0d?style=for-the-badge&logo=github&logoColor=00ff66)

### 🐧 Operating Systems

![Kali Linux](https://img.shields.io/badge/Kali_Linux-001a0d?style=for-the-badge&logo=kalilinux&logoColor=00ff66)
![Linux](https://img.shields.io/badge/Linux-001a0d?style=for-the-badge&logo=linux&logoColor=00ff66)
![Ubuntu](https://img.shields.io/badge/Ubuntu-001a0d?style=for-the-badge&logo=ubuntu&logoColor=00ff66)
![Windows](https://img.shields.io/badge/Windows-001a0d?style=for-the-badge&logo=windows&logoColor=00ff66)

### 🛡️ Security Tools

![Wazuh](https://img.shields.io/badge/Wazuh-001a0d?style=for-the-badge&logo=wazuh&logoColor=00ff66)
![Suricata](https://img.shields.io/badge/Suricata-001a0d?style=for-the-badge&logoColor=00ff66)
![Zeek](https://img.shields.io/badge/Zeek-001a0d?style=for-the-badge&logoColor=00ff66)
![Wireshark](https://img.shields.io/badge/Wireshark-001a0d?style=for-the-badge&logo=wireshark&logoColor=00ff66)
![Nmap](https://img.shields.io/badge/Nmap-001a0d?style=for-the-badge&logoColor=00ff66)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-001a0d?style=for-the-badge&logo=burpsuite&logoColor=00ff66)
![Metasploit](https://img.shields.io/badge/Metasploit-001a0d?style=for-the-badge&logo=metasploit&logoColor=00ff66)
![PEStudio](https://img.shields.io/badge/PEStudio-001a0d?style=for-the-badge&logoColor=00ff66)

### 🧠 Security Concepts

![TCP/IP](https://img.shields.io/badge/TCP%2FIP-001a0d?style=for-the-badge&logoColor=00ff66)
![DNS](https://img.shields.io/badge/DNS-001a0d?style=for-the-badge&logoColor=00ff66)
![HTTP/HTTPS](https://img.shields.io/badge/HTTP%2FHTTPS-001a0d?style=for-the-badge&logoColor=00ff66)
![TLS](https://img.shields.io/badge/TLS-001a0d?style=for-the-badge&logoColor=00ff66)
![PCAP](https://img.shields.io/badge/PCAP_Analysis-001a0d?style=for-the-badge&logoColor=00ff66)
![IDS/IPS](https://img.shields.io/badge/IDS%2FIPS-001a0d?style=for-the-badge&logoColor=00ff66)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-001a0d?style=for-the-badge&logoColor=00ff66)
![IOC Analysis](https://img.shields.io/badge/IOC_Analysis-001a0d?style=for-the-badge&logoColor=00ff66)

---

## `06 // CERTIFICATIONS & TRAINING`

<div align="center">

| CREDENTIAL | ISSUING ORGANIZATION | YEAR |
|:---|:---:|:---:|
| ISO/IEC 27001 Information Security Associate™ | SkillFront | 2026 |
| Google Foundations of Cybersecurity | Coursera | 2026 |
| Ethical Hacking Training | Zynex Solutions | 2025 |
| SOC Training | Secure Dev Labs | 2026 |
| SOC Internship Program — Batch III | Secure Dev Labs | 2026 |

</div>

**Credential verification:**

- [ISO/IEC 27001 — SkillFront Badge](https://www.skillfront.com/Badges/07151420182791)
- [Google Cybersecurity — Coursera Certificate](https://www.coursera.org/account/accomplishments/verify/ZIT667WM1XEN)

---

## `07 // PROFESSIONAL EXPERIENCE`

### 🏢 SOC INTERN — SECURE DEV LABS

**Duration:** One Month

Completed a SOC internship program focused on practical security operations training and cybersecurity fundamentals.

**Areas of exposure:**

- SOC operations fundamentals
- Security monitoring concepts
- Threat detection
- Security event investigation
- SIEM fundamentals

**Documentation:** [View Internship Completion Letter](https://lnkd.in/p/dhGmchiH)

---

## `08 // HANDS-ON CYBERSECURITY LABS`

### ⚔️ HACK THE BOX

**Machine: CAP — Completed**

Practical experience involving:

- Nmap enumeration
- PCAP analysis
- Credential reuse investigation
- Linux privilege escalation
- Linux `cap_setuid` capability exploitation

**[View HTB Achievement](https://labs.hackthebox.com/achievement/machine/3046138/351)**

### 🔎 TRYHACKME

| ROOM | ACHIEVEMENT |
|:---|:---|
| Defensive Security Intro | [View Room](https://tryhackme.com/room/defensivesecurityintroexp/congratulations?step=room-completion-share) |
| Junior Security Analyst Intro | [View Room](https://tryhackme.com/room/jrsecanalystintrouxo) |

---

## `09 // CURRENT DEVELOPMENT`

```bash
┌──(phantomroot0x㉿kali)-[~]
└─$ whoami

Muhammad Zubair

┌──(phantomroot0x㉿kali)-[~]
└─$ cat profile.txt

ROLE       : Computer Science Student
UNIVERSITY : University of Buner
FIELD      : Cybersecurity
FOCUS      : SOC | Blue Team | Network Security
INTERESTS  : Malware Analysis | DFIR | Threat Intelligence

MINDSET    : Learning && Building
APPROACH   : Side by side, bit by bit.
OBJECTIVE  : Learn. Build. Break. Analyze. Improve.
```

**Portfolio roadmap:**

| PROJECT | DOMAIN | STATUS |
|:---|:---|:---:|
| Windows Malware Analysis & IR | Malware / DFIR | ✅ Completed |
| Suricata + Zeek NSM | Network Security / SOC | ✅ Completed |
| Threat Intelligence Analysis | Threat Intelligence | 🔄 Developing |
| Web Security Labs | AppSec / VAPT | 🔄 Developing |
| Linux Malware Analysis | Malware / DFIR | 🔄 Planned |

---

## `10 // GITHUB ACTIVITY`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=phantomroot0x&show_icons=true&hide_border=true&bg_color=001a0d&title_color=00ff66&icon_color=00ff66&text_color=ccffdd" height="165"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=phantomroot0x&layout=compact&hide_border=true&bg_color=001a0d&title_color=00ff66&text_color=ccffdd" height="165"/>

<br>

<img src="https://streak-stats.demolab.com?user=phantomroot0x&hide_border=true&background=001a0d&ring=00ff66&fire=00ff66&currStreakLabel=00ff66&sideLabels=ccffdd&dates=ccffdd" width="80%"/>

</div>

---

## `11 // CONNECT`

<div align="center">

**Interested in cybersecurity, SOC operations, Blue Team engineering, and technical collaboration.**

<br>

[![GitHub](https://img.shields.io/badge/GitHub-phantomroot0x-001a0d?style=for-the-badge&logo=github&logoColor=00ff66)](https://github.com/phantomroot0x)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-001a0d?style=for-the-badge&logo=linkedin&logoColor=00ff66)](https://www.linkedin.com/in/muhammad-zubair-a30395309)

[![Email](https://img.shields.io/badge/Email-Contact-001a0d?style=for-the-badge&logo=gmail&logoColor=00ff66)](mailto:phantomroot0x@gmail.com)

<br>

```text
LEARN  →  BUILD  →  ANALYZE  →  DOCUMENT  →  IMPROVE
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff66,50:003b20,100:001a0d&height=120&section=footer" width="100%"/>

**`[ SYSTEM STATUS: CONTINUOUSLY LEARNING ]`**

</div>
