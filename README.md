<!-- ══════════════════════════════════════════════════════════════════ -->
<!--        ANVESH RAJU VISHWARAJU — GitHub Profile README           -->
<!-- ══════════════════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2800&pause=1000&color=1D9E75&center=true&vCenter=true&width=700&lines=whoami+%3D%3D+Anvesh+Raju+Vishwaraju;SOC+Analyst+%7C+Threat+Intel+%7C+AI-Security;MS+Cybersecurity+%E2%80%94+UNC+Charlotte;MTech+AI+%E2%80%94+University+of+Hyderabad;Building+where+LLMs+meet+the+SOC" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arv007)
[![Email](https://img.shields.io/badge/Email-Reach%20Out-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anvesh65422@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-anvesh--raju--vishwaraju-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/its-me-anvesh-var)

<br/>

![Security+](https://img.shields.io/badge/CompTIA-Security%2B-FF0000?style=flat-square&logo=comptia&logoColor=white)
![eJPTv2](https://img.shields.io/badge/eLearnSecurity-eJPTv2-006400?style=flat-square&logoColor=white)
![AWS CCP](https://img.shields.io/badge/AWS-Cloud%20Practitioner-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![CASA](https://img.shields.io/badge/CSA-CASA-0078D4?style=flat-square&logoColor=white)
![MITRE](https://img.shields.io/badge/MITRE-ATT%26CK-red?style=flat-square&logoColor=white)
![Location](https://img.shields.io/badge/📍-Hyderabad%2C%20India-lightgrey?style=flat-square)

</div>

---

## `$ cat about_me.txt`

```
Name      : Anvesh Raju Vishwaraju
Degrees   : MS Cybersecurity — UNC Charlotte (2023)
            MTech AI — University of Hyderabad (2022)
Research  : IDRBT — RBI's Technology Research Institute
            -> AI/ML applications in BFSI security
SOC Exp   : L1 Analyst — Innovative Intelligent Solutions (June 2024 – Dec 2025)
              Splunk | Wazuh | MITRE ATT&CK | Incident Response
Edge      : I build AI-native security tools, not just run them.
            Every project here has an LLM/RAG/automation layer.
Open To   : SOC Analyst L1/L2 · SIEM Engineer · Threat Intel · Cloud Security
            -> Anywhere, India
```

---

## 🧠 What Sets Me Apart

I sit at the **intersection of AI/ML and cybersecurity** — trained in both at postgraduate level, with hands-on SOC production experience and a research background at **IDRBT** (the Reserve Bank of India's technology arm). Every tool I build has an intelligence layer on top of raw log data — not just dashboards, but systems that reason about threats.

---

## 🎯 Core Competencies

| Area | Skills |
|------|--------|
| 🔵 **SIEM & Detection Engineering** | Splunk SPL · Microsoft Sentinel KQL · Wazuh · ELK Stack · QRadar |
| 🤖 **AI / LLM Security** | LangChain · Claude API · ChromaDB · RAG Pipelines · LLM Summarisation · NLP |
| 🧠 **Threat Intelligence** | MITRE ATT&CK · IOC Extraction · OTX · VirusTotal API · BFSI Threat Profiling |
| 🌐 **Network & Log Analysis** | Wireshark · Zeek NDR · Suricata IDS · DNS/HTTP/SSH/Firewall log analysis |
| 🔍 **Offensive Security** | Metasploit · BloodHound · Burp Suite · AD attack paths · eJPTv2 certified |
| ☁️ **Cloud & IAM** | AWS · Azure AD · Microsoft Entra ID · Zero Trust architecture |
| ⚙️ **Scripting & Automation** | Python · Bash · PowerShell · KQL · SPL · Streamlit · REST APIs |

---

## 🔬 Projects

> Each project has an **AI/automation layer** that goes beyond standard SOC labs — turning passive detection into active intelligence.

---

### 🤖 [Cybersecurity RAG Assistant](https://github.com/its-me-anvesh-var/cybersecurity-rag-assistant)
`LangChain` `Claude API` `ChromaDB` `Streamlit` `Python` `Sentence-Transformers`

**The AI-powered SOC analyst assistant.** Query CVEs, IOCs, MITRE TTPs, and threat actor profiles in natural language — the system retrieves and synthesises answers from a curated security knowledge base.

- 1,500+ lines of production code | 85% retrieval precision | <5% hallucination rate
- Architecture: RecursiveCharacterTextSplitter → 384-dim embeddings → ChromaDB → Claude API (temp=0.3)
- 2–3s average latency | Streamlit UI for analyst-friendly interaction
- **Differentiator vs community phishing scanners**: Adapts to novel threat queries without predefined templates — full RAG pipeline, not keyword matching

---

### 🏠 [SOC Home Lab — Multi-SIEM Detection Environment](https://github.com/its-me-anvesh-var/soc-home-lab)
`Wazuh` `Splunk` `Suricata` `Active Directory` `Python` `MITRE ATT&CK`

**Full enterprise SOC simulation** — multi-VM environment with a live AD domain, endpoint agents, and network sensors running simultaneously. Built to understand detection gaps, not just generate alerts.

- Custom Wazuh detection rules mapped to MITRE ATT&CK: T1078, T1110, T1547, T1071
- Suricata IDS tuned to reduce false positives on lateral movement traffic
- Python log-parsing pipeline for automated IOC enrichment before analyst review
- Published incident response playbooks with full attack timelines
- **Differentiator vs 5-VM multi-SIEM labs**: Python automation enriches every alert before it hits the queue — analyst reviews context, not raw logs

---

### 🔎 [BFSI Threat Intelligence Research](https://github.com/its-me-anvesh-var/bfsi-threat-intel)
`Python` `OTX` `VirusTotal API` `MITRE ATT&CK` `Pandas`

**Banking-sector threat intelligence pipeline** — built on research started at IDRBT (RBI's tech institute). Automates IOC collection, enrichment, and MITRE mapping for financial sector threats.

- Integrates OTX pulses + VirusTotal API for multi-source IOC validation
- Outputs structured, analyst-ready threat reports (JSON + human-readable)
- MITRE ATT&CK technique tagging for every collected indicator
- **Differentiator**: Domain-specific BFSI focus — banking trojans, phishing kits, and credential harvesting campaigns targeting Indian financial institutions specifically

---

### 🤖 [LLM Threat Intelligence Summariser](https://github.com/its-me-anvesh-var/llm-ti-summariser)
`Python` `Claude API` `OTX` `NLP` `Prompt Engineering`

**LLM-powered threat feed digestion** — ingests raw threat intel and outputs structured analyst summaries with actionable detection queries.

- Pulls live feeds from OTX and CVE databases
- Prompts Claude API with structured templates for consistent, analyst-ready output
- Output includes: affected systems, CVSS severity, **auto-generated SPL/KQL detection queries**, and IOC list
- **Differentiator vs roadmap/study repos**: Generates working Splunk and Sentinel queries directly from threat data — bridges intel and detection engineering

---

### ⚔️ [AD Attack & Defence Lab](https://github.com/its-me-anvesh-var/ad-attack-defence-lab)
`BloodHound` `Metasploit` `Splunk` `Active Directory` `PowerShell` `MITRE ATT&CK`

**Full kill-chain simulation** against a hardened AD environment. Red side attacks, blue side detects — every step mapped to MITRE ATT&CK with corresponding Splunk rules.

- BloodHound attack-path enumeration → Metasploit privilege escalation
- Covers: Kerberoasting (T1558.003), Pass-the-Hash (T1550.002), DCSync (T1003.006)
- Splunk detection rules for each offensive technique
- PowerShell defensive hardening scripts alongside every detection
- **Differentiator vs DFIR/forensics projects**: Bidirectional — both the attack playbook and the detection rule ship together

---

### 🦠 [Malware Analysis & API Security Lab](https://github.com/its-me-anvesh-var/malware-api-security)
`Python` `VirusTotal API` `MITRE ATT&CK` `YARA` `Behavioral Analysis`

**Dual-lens analysis** — static/dynamic malware analysis from Blue Team perspective, with live VirusTotal API integration for automated IOC reputation checks.

- 10+ malware families: execution lifecycle, persistence (T1547), evasion (T1027)
- Automated VirusTotal API enrichment for file hashes, IPs, and domains
- YARA rule development for signature-based detection
- **Differentiator vs malware-sample repos**: Integrated live API lookup layer — makes this a reusable analyst tool, not just a static study repo

---

### 🛠️ [PentestX](https://github.com/its-me-anvesh-var/pentestx)
`Python` `Bash` `VirusTotal API` `NVD API` `PowerShell`

**SOC analyst's command-line toolkit** — fast, scriptable utilities for daily operations. Built for analysts who live in the terminal and need automation without a GUI.

- **log-parser**: extracts IOCs (IPs, hashes, domains) from raw log files in bulk
- **hash-checker**: bulk VirusTotal reputation lookup via API with CSV output
- **cve-fetcher**: queries NVD API for CVSS scores, affected versions, and patch status
- **alert-formatter**: converts raw JSON alerts into structured markdown incident reports
- **Differentiator**: Fully scriptable and CI/CD integrable — not a GUI dashboard, a pipeline component

---

## 🏅 Certifications

| | Certification | Issuer | Focus |
|---|---|---|---|
| 🏆 | **CompTIA Security+** | CompTIA | Security foundations, threat analysis, risk management |
| 🏆 | **eJPTv2** — Junior Penetration Tester | eLearnSecurity | Active exploitation, network pentesting |
| 🏆 | **AWS Cloud Practitioner** | Amazon Web Services | Cloud architecture, shared responsibility, IAM |
| 🏆 | **CASA** — Cloud App Security Assessor | Cloud Security Alliance | Cloud application security posture |

---

## 🧑‍🎓 Education & Research

| Degree | Institution | Period | Focus |
|---|---|---|---|
| **MS Cybersecurity** | UNC Charlotte, USA | 2022–2023 | Network security, digital forensics, threat detection |
| **MTech AI** | University of Hyderabad | 2022 | NLP, ML, deep learning — thesis at IDRBT |
| **BTech CSE** | Vasavi College of Engineering | 2020 | Computer science foundations |

**IDRBT Research** (Institute for Development & Research in Banking Technology — RBI's tech arm):
Applied AI/ML research for banking-sector security — anomaly detection, fraud pattern recognition, and secure system design for BFSI infrastructure. This is where the BFSI Threat Intel project was born.

---

## 🛠️ Full Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-3A3A3A?style=for-the-badge&logoColor=white)
![Elastic](https://img.shields.io/badge/Elastic%20Stack-005571?style=for-the-badge&logo=elastic&logoColor=white)
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft%20Sentinel-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-EF3B2D?style=for-the-badge&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude%20API-CC785C?style=for-the-badge&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-0085CA?style=for-the-badge&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=its-me-anvesh-var&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=its-me-anvesh-var&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="45%" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=its-me-anvesh-var&theme=tokyonight&hide_border=true" width="60%" />
</div>

---

## 📬 Open To Work

```
Target Roles  : SOC Analyst L1/L2  |  SIEM Engineer  |  Threat Intel Analyst
                Cloud Security Analyst  |  Detection Engineer
Location      : Open to Relocation | Hyderabad , India  (open to remote)
Availability  : Immediate
Contact       : anvesh65422@gmail.com
LinkedIn      : linkedin.com/in/arv007
```

[![Open To Work](https://img.shields.io/badge/Open%20To%20Work%20India-1D9E75?style=for-the-badge)](mailto:anvesh65422@gmail.com)

---

<div align="center">

*"I don't just run tools — I understand why the alert fired, what the attacker intended, and how to stop the next one before it hits."*

<br/>

<img src="https://komarev.com/ghpvc/?username=its-me-anvesh-var&color=1D9E75&style=flat-square&label=Profile+Views" />

</div>
