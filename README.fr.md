# Salut, moi c'est Honoré 👋

🇬🇧 [Read in English](README.md)

🎓 Licence Informatique et Systèmes à l'École Polytechnique de Lomé (Université de Lomé), orienté cybersécurité défensive (Blue Team, ingénierie SOC & DFIR).

🛠️ Je conçois des laboratoires et des pipelines de sécurité automatisés (Wazuh, Python, Ansible, Terraform, Docker) pour surveiller les menaces et accélérer la réponse aux incidents.

📍 Lomé, Togo

🎯 Objectif : intégrer une équipe SOC en tant qu'analyste / ingénieur détection, puis poursuivre en Master Cybersécurité.

![Wazuh](https://img.shields.io/badge/Wazuh-3AAFEE?style=flat-square&logo=wazuh&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## Ce que je construis

### 🛡️ [Nyx](https://github.com/4rthur-Root/NYX) : un mini-SOC pour les PME togolaises
Projet de fin de formation réalisé en binôme avec [Gaël Kpodonou](https://github.com/4rthur-Root), sous la direction du Dr Essohanam Djeki. Un moteur de corrélation en Python avec des règles de détection YAML, une réponse SOAR automatisée via l'API OPNsense, et un laboratoire KVM avec Samba AD, Dolibarr et Kali.

**Ma part :** le module de réponse (enrichissement AbuseIPDB, remédiation via l'API OPNsense, gestion des timeouts et des replis), le schéma JSON unifié des événements (validé avec mon binôme) et ses tests de conformité, le dashboard Flask et les vues Grafana, et l'analyse des résultats de réponse.

**Scénarios d'attaque testés :** brute-force SSH, exfiltration SMB, compromission de poste par BEC, brute-force web sur Dolibarr, upload de fichier malveillant.

**Ce que fait le système :** les scénarios testés déclenchent des alertes critiques, et le module SOAR répond automatiquement en bloquant l'adresse de l'attaquant via OPNsense.

**Limites connues et prochaines étapes :** pas de corrélation entre adresses IP différentes, pas de rechargement à chaud des règles, journaux et base de données non chiffrés. Prochaines étapes : syslog sur TLS, chiffrement de la base et prise en charge des règles Sigma.

### ⚙️ [mini-soc-iac](https://github.com/M4dnolyn/mini-soc-iac) : un SOC Wazuh as code
Un mini-SOC déployé automatiquement sur Docker avec Terraform, Ansible et un Makefile, avec des tests de détection pour le brute-force SSH et la surveillance d'intégrité des fichiers.

### 🔎 [dfir-lab-journal](https://github.com/M4dnolyn/dfir-lab-journal) : mon journal d'apprentissage DFIR
Montage du laboratoire, notes de méthodologie, analyse réseau avec Wireshark et réflexions, mis à jour au fil de ma progression.

### 🧪 [CyberLab Manager](https://github.com/4rthur-Root/CyberLab) : un orchestrateur de labs de VM
Une application JavaFX, réalisée en équipe de trois, qui gère des labs VirtualBox pour l'analyse de malware et le pentest, avec un journal, un audit et des rapports PDF.

**Ma part (IHM/UX et contrôleur) :** l'interface FXML en trois colonnes, le thème sombre en CSS externe, un contrôleur unique comme seul lien entre l'interface et les services, les actions VM asynchrones, et le workflow Git feature → develop → main.

---

## 🛠️ Compétences techniques

| Domaine | Outils et technologies |
|---|---|
| **SOC / SIEM** | Wazuh, Grafana, rsyslog, normalisation des logs (schéma JSON unifié, tests de conformité) |
| **Sécurité Web (CTF et labs)** | Burp Suite, utilisé ponctuellement en CTF et en labs (picoCTF, TryHackMe, Hack The Box, CTF régionaux) |
| **DFIR** | Wireshark, analyse réseau, investigation à partir de journaux |
| **Réponse aux incidents / SOAR** | Python, API REST, OPNsense, AbuseIPDB |
| **Infrastructure as Code** | Terraform, Ansible, Docker, Makefile |
| **Virtualisation et réseau** | KVM/QEMU, VirtualBox, GNS3, Linux |
| **Développement** | Python, Java (JavaFX, Maven), Flask, SQL, SQLite |
| **Collaboration** | Git, GitHub, GitHub Actions (CI/CD) |

**En cours d'exploration :** Elastic Stack, Splunk, YARA, MITRE ATT&CK.

---

## En ce moment

- Certification Blue Cape Security « DFIR Foundations and Techniques » (en cours) ; les prochains modules couvrent Splunk. Je documente mes labs dans mon [journal DFIR](https://github.com/M4dnolyn/dfir-lab-journal).

**Prochains objectifs :**

- Cours CyberWarfare Labs : Blue Team Fundamentals et Cyber Security Analyst (inscrit)
- Plus tard : certification Splunk Core Certified User

---

## Me contacter

[![Email](https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:honoregahounzo@gmail.com)  [![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/M4dnolyn)

---

> *« Convaincu que la meilleure défense repose sur l'automatisation, la rigueur et l'amélioration continue. Toujours prêt à échanger sur l'ingénierie SOC, les architectures SIEM/SOAR et le DFIR. »*
