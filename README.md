# Hi, I'm Honoré 👋

🇫🇷 [Lire en français](README.fr.md)

🎓 Final-year Computer Science and Systems student (Licence) at École Polytechnique de Lomé (University of Lomé), oriented toward defensive cybersecurity (Blue Team, SOC engineering & DFIR).

🛠️ I design automated security labs and pipelines (Wazuh, Splunk, Python, Ansible, Terraform) to monitor threats and speed up incident response.

📍 Lomé, Togo

🎯 Goal: join a SOC team as an analyst / detection engineer, then pursue a master's degree in cybersecurity.

![Wazuh](https://img.shields.io/badge/Wazuh-3AAFEE?style=flat-square&logo=wazuh&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## What I'm building

### 🛡️ [Nyx](https://github.com/4rthur-Root/NYX): a mini-SOC for Togolese SMEs
Final-year project built in a pair with [Gaël Kpodonou](https://github.com/4rthur-Root), supervised by Dr Essohanam Djeki. A Python correlation engine with YAML detection rules, an automated SOAR response through the OPNsense API, and a KVM lab with Samba AD, Dolibarr and Kali.

**My part:** the response module (AbuseIPDB enrichment, remediation through the OPNsense API, timeouts and fallbacks), the unified JSON event schema and its conformance tests, the Flask dashboard and the Grafana views, and the analysis of the response results.

**Attack scenarios tested:** SSH brute force, SMB exfiltration, BEC workstation compromise, web brute force on Dolibarr, malicious file upload.

**Lab results against the targets I set:** 

### ⚙️ [mini-soc-iac](https://github.com/M4dnolyn/mini-soc-iac): a Wazuh SOC as code
A mini-SOC deployed automatically on Docker with Terraform, Ansible and a Makefile, with detection tests for SSH brute force and file-integrity monitoring.

### 🔎 [dfir-lab-journal](https://github.com/M4dnolyn/dfir-lab-journal): my DFIR learning log
Lab setup, methodology notes, Wireshark network analysis and reflections, updated as I progress.

### 🧪 [CyberLab Manager](https://github.com/4rthur-Root/CyberLab): a VM lab orchestrator
A JavaFX application, built by a team of three, that manages VirtualBox labs for malware analysis and pentesting, with a journal, an audit log and PDF reports.

**My part (UI/UX and controller):** the three-column FXML interface, the external dark-theme CSS, a single controller as the only link between the UI and the services, asynchronous VM actions, and the feature → develop → main Git workflow.

---

## 🛠️ Technical skills

| Domain | Tools and technologies |
|---|---|
| **SOC / SIEM** | Wazuh, Splunk, Grafana, rsyslog, log normalization (unified JSON schema, conformance tests) |
| **Threat detection** | YARA, MITRE ATT&CK |
| **Web security (CTFs and labs)** | Burp Suite, used on picoCTF, TryHackMe and Hack The Box |
| **DFIR** | Wireshark, network analysis, log-based investigation |
| **Incident response / SOAR** | Python, REST APIs, OPNsense, AbuseIPDB |
| **Infrastructure as Code** | Terraform, Ansible, Docker, Makefile |
| **Virtualization and networking** | KVM/QEMU, VirtualBox, GNS3, Linux |
| **Development** | Python, Java (JavaFX, Maven), Flask, SQL, SQLite |
| **Collaboration** | Git, GitHub, GitHub Actions |

**Currently exploring:** Elastic Stack.

---

## Currently

- Working through the Blue Cape Security "DFIR Foundations and Techniques" certification (in progress), documenting my labs in my [DFIR journal](https://github.com/M4dnolyn/dfir-lab-journal)

**Next goals:**

- Splunk Core Certified User certification
- CyberWarfare Labs courses: Blue Team Fundamentals and Cyber Security Analyst (enrolled in October 2026)

---

## Get in touch

[![Email](https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:honoregahounzo@gmail.com) [![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/M4dnolyn)

---

> *“Convinced that the best defense lies in automation, rigor, and continuous improvement. Always open to discussing SOC engineering, SIEM/SOAR architectures, and DFIR.”*
