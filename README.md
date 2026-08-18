<div align="center">

<img src="assets/banner.svg" alt="Ilyas Ajelyan — Blue Team · SOC · Detection Engineering" width="100%" />

<p>
Fourth-year <b>Cybersecurity &amp; Networks</b> engineering student at <b>EMSI Tanger</b>,
focused on defensive security, SOC operations, and detection engineering —
SIEM/SOAR, Sigma-style rules, MITRE ATT&amp;CK, alert triage, log analysis, and
incident response, with a side interest in blockchain security.
</p>

<a href="https://linkedin.com/in/ilyas-ajelyan"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:ajelyanilyas01@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/ajelyanilyas"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>

</div>

---

## 🎯 What I focus on

- **Detection engineering** — SIEM alert logic, Sigma-style rules, MITRE ATT&CK mapping
- **SOC operations** — log analysis, event correlation, threat hunting, alert triage
- **Network security** — IDS/IPS (Suricata, Zeek), traffic analysis, secure architecture
- **Incident response** — triage, playbooks, post-incident analysis

## 🎓 Education

**Cycle Ingénieur — Cybersecurity & Networks** · *EMSI, Tanger* · 2025 – Present
- Core modules: network security, cryptography, intrusion detection, vulnerability analysis, secure system design.
- SEC555-aligned detection engineering: log-pipeline design, SIEM alert creation, and threat-hunting methodology through lab exercises.

**Cycle Ingénieur — Computer Science & Networks** · *EMSI, Tanger* · 2024 – 2025
**Classes Préparatoires (CPGE) — Mathematics & Physics** · *EMSI* · 2021 – 2024
**Baccalauréat — Sciences Mathématiques** · 2019 – 2021

## 💼 Experience

**Cybersecurity Engineering Intern (PFA)** · *Smart Automation Technologies (Growly), Tanger* · 2026
- Designed and deployed **SecureBox**, an inline network-security appliance on Raspberry Pi pairing real-time detection with a **fully offline AI SOC assistant** — end-to-end architecture, backend, and web console.
- Built the detection pipeline: **Suricata** IDS/IPS + **Zeek** telemetry → Fluent Bit → **FastAPI**, with alerts correlated and mapped to **MITRE ATT&CK**.
- Engineered a **SOAR** layer with tiered, human-in-the-loop playbooks and a deterministic action broker executing only signed, reversible, journaled actions (Ed25519-signed catalog, RBAC, hash-chained audit log).
- Implemented a local **RAG assistant** (Qdrant + BGE-M3 + Gemma via Ollama) grounded on 71,000+ security documents (ATT&CK, Sigma, OWASP, NIST, CIS).

**Technical Intern** · *DSI — Amendis (Groupe Veolia), Tanger* · Summer 2025
- Contributed to the technical audit and partial redesign of an internal portal; identified and helped fix critical application bugs, improving stability and service continuity.

## 🚀 Featured projects

My Blue Team work forms a connected toolkit — **Nightjar** raises the alerts,
while **ThreatPulse** and **ioc-enrich** enrich the indicators behind them.

| Project | What it is | Stack |
|---------|-----------|-------|
| **[🛡️ Nightjar](https://github.com/ajelyanilyas/Nightjar)** | Detection-as-Code mini-SIEM: ingests logs, evaluates version-controlled YAML rules, and raises MITRE ATT&CK–mapped alerts on a live dashboard — with a built-in attack replayer. | Python · FastAPI · YAML · MITRE ATT&CK |
| **[📡 ThreatPulse](https://github.com/ajelyanilyas/ThreatPulse)** | A live, self-updating threat-intelligence platform that auto-ingests malware feeds (URLhaus, ThreatFox, Feodo Tracker) hourly and serves a searchable dashboard with on-demand enrichment. | Python · FastAPI |
| **[🔎 ioc-enrich](https://github.com/ajelyanilyas/ioc-enrich)** | IOC enrichment &amp; triage CLI — queries URLhaus, VirusTotal &amp; AbuseIPDB and aggregates a weighted threat verdict for an indicator. | Python |
| **🤖 SecureBox** *(internship)* | Inline network-security appliance on Raspberry Pi pairing real-time detection with a fully offline AI SOC assistant — Suricata/Zeek → FastAPI, alerts mapped to MITRE ATT&CK, plus a signed/reversible SOAR action broker. | Suricata · Zeek · FastAPI · SOAR · RAG |
| **[⛓️ Medichain-plus](https://github.com/ajelyanilyas/Medichain-plus)** | Dual-chain (Hyperledger Fabric + Polygon) healthcare platform with automated parametric micro-insurance and role-based access control. | Solidity · Hyperledger Fabric · Polygon · JavaScript |

<sub>Also: a Ransomware Behaviour Simulator (AES-256, isolated VM) and a heuristic Phishing / Malicious-URL detector — academic security projects in Python.</sub>

## 🧰 Tech &amp; tools

**Security &amp; SOC**

![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT&CK-C0392B?style=flat-square)
![Suricata](https://img.shields.io/badge/Suricata-EF3B2D?style=flat-square)
![Zeek](https://img.shields.io/badge/Zeek-4B8BBE?style=flat-square)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-3B82F6?style=flat-square)
![Elastic](https://img.shields.io/badge/Elastic%20SIEM-005571?style=flat-square&logo=elastic&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat-square)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Platforms &amp; infra**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Kali](https://img.shields.io/badge/Kali-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GNS3](https://img.shields.io/badge/GNS3-00A5A5?style=flat-square)

## 📜 Certifications &amp; training

- Object-Oriented Programming in **C++** — *EPFL* (Coursera)
- Python for Web Data · Interactivity with JavaScript — *University of Michigan* (Coursera)
- Software Engineering &amp; Project Management — *HKUST* (Coursera)
- Introduction to Machine Learning — *Duke University*
- Introduction to NoSQL Databases — *IBM*

## 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ajelyanilyas&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ajelyanilyas&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

## 🌍 Languages

**Arabic** — Native &nbsp;·&nbsp; **French** — Fluent &nbsp;·&nbsp; **English** — Professional (technical)

---

<div align="center"><sub>Open to cybersecurity internships — threat detection · security monitoring · vulnerability analysis.</sub></div>
