![HydraSec Banner](https://raw.githubusercontent.com/omaral-fayyadh/Omar-Cyber-Profile/main/assets/img/hydrasec_github_banner.html)

<div align="center">

# عمر الفياض | Omar Al-Fayyadh

### Cybersecurity Professional · AI Security Founder · Telecom Engineer

*"I don't waste time. Not even the worst of it."*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Omar_Al--Fayyadh-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/omaralfayyadh/)
[![Website](https://img.shields.io/badge/Website-tdsllc.info-00C896?style=for-the-badge&logo=google-chrome&logoColor=white)](https://tdsllc.info)
[![YouTube](https://img.shields.io/badge/YouTube-Channel-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@omaral-fayyadh4307)
[![Email](https://img.shields.io/badge/Email-info@tdsllc.info-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:info@tdsllc.info)

</div>

---

## 🐍 HydraSec — AI Threat Intelligence Platform

> *The project that started with a concept and became a working prototype in a single session.*

**HydraSec** is a multi-head AI threat intelligence platform I conceived, architected, and built. Instead of one model making one decision, four specialized AI heads analyze every security event simultaneously — then an Arbiter synthesizes them into a single explainable verdict.

```
┌─────────────────────────────────────────────────────────────┐
│                     HYDRASEC ARCHITECTURE                   │
├──────────┬──────────┬──────────────┬────────────────────────┤
│   STAT   │   NRAL   │     GEN      │         WSDO           │
│Statistical│ Neural  │  Generative  │        Wisdom          │
│ Anomaly  │Behavioral│  Adversarial │    LLM Reasoning       │
│Detection │Intelligence│ Simulation │      Analyst           │
└────┬─────┴────┬─────┴──────┬───────┴──────────┬────────────┘
     │          │             │                  │
     └──────────┴──────┬──────┴──────────────────┘
                       │
              ┌────────▼────────┐
              │    ARBITER      │
              │ Consensus Engine│
              │ Confidence Vote │
              └────────┬────────┘
                       │
              ┌────────▼────────┐
              │  FINAL VERDICT  │
              │ CRITICAL / HIGH │
              │  MEDIUM / LOW   │
              └─────────────────┘
```

**Stack:** `FastAPI` `React` `SQLite` `Anthropic Claude API` `JWT Auth` `Python 3.13`

**Features:**
- 4 AI detection heads running in parallel
- Confidence-weighted Arbiter consensus engine  
- JWT authentication with user accounts
- Threat history database with severity filtering
- File ingestion: CSV, PCAP, LOG formats
- Full REST API with auto-generated docs

> *"Sentinel tells you something happened. HydraSec tells you what it means."*

---

## 👨‍💻 Security Projects

### 🔴 Cowrie Honeypot → Microsoft Sentinel → SOAR Pipeline
**`Azure` `Microsoft Sentinel` `Logic Apps` `KQL` `AMA` `DCR`**

Designed and deployed an end-to-end cloud security automation pipeline integrating a Cowrie honeypot with Microsoft Sentinel.

- Ingested attacker logs via **Azure Monitor Agent (AMA)** and **Data Collection Rules (DCR)** into custom Sentinel tables
- Engineered a **Logic Apps SOAR playbook** to auto-enrich incidents — parsed entities, filtered IPs via threat intel, posted attacker metadata back into Sentinel incident comments
- **Reduced manual triage time by ~90%** in simulated SOC environment
- Built custom **Sentinel Workbook Dashboard** visualizing brute-force trends, attacker IP patterns, and attack timelines

📄 [View Project →](https://github.com/omaral-fayyadh/Cowrie-Microsoft-Sentinel-SOAR-Honeypot)

---

### 🟠 Splunk SIEM Detection Engineering Lab
**`Azure` `Splunk Enterprise` `SPL` `MITRE ATT&CK` `Universal Forwarder`**

Built a full Splunk detection engineering environment from scratch on Azure.

- Deployed **Splunk Enterprise** and ingested honeypot + Linux system logs using Universal Forwarder with custom parsing
- Developed **SPL-based detection rules** for brute-force attempts, privilege escalation, and anomalous authentication
- Mapped attacker TTPs to **MITRE ATT&CK** framework for structured threat correlation
- **Improved detection accuracy by ~30%** through iterative rule tuning

📄 [View Project →](https://github.com/omaral-fayyadh/Cowrie-Splunk-Honeypot)

---

### 🟡 Multi-Honeypot Threat Telemetry Environment
**`Azure` `T-Pot` `Elastic` `Splunk` `Microsoft Sentinel`**

Deployed and hardened T-Pot honeypot suite on Azure to simulate enterprise attack surfaces across multiple protocols simultaneously.

- Correlated multi-protocol attacker activity across **Elastic, Splunk, and Sentinel** platforms
- Refined detection rules based on real-world live attacker behavior patterns
- Collected and analyzed threat intelligence from active internet-facing honeypots

🎥 [Watch Walkthrough →](https://youtu.be/d71xenzgNo0)

---

## 🛡️ Certifications

<div align="center">

| Certification | Issuer | Status | Link |
|---|---|---|---|
| **CCSK** — Certificate of Cloud Security Knowledge | Cloud Security Alliance | ✅ Certified 2025 | [View Badge](https://www.credly.com/badges/9f56e3cc-c396-4e90-872a-8bc2228634d8) |
| **AZ-900** — Azure Fundamentals | Microsoft | ✅ Certified 2025 | [View Transcript](https://learn.microsoft.com/en-us/users/omaralfayyadh-0997/transcript/7k13gs19el4jw8j) |
| **Security+** | CompTIA | 📅 Scheduled 2026 | — |
| **AZ-500** — Azure Security Engineer | Microsoft | 📘 In Progress | — |

</div>

---

## 🎓 Education

### 🏛️ Master of Science — Information Assurance & Cybersecurity
**Davenport University** · *2025*

- **4.0 GPA** · Graduated with Distinction
- Thesis: *Implementing Multi-Factor Authentication for Augmented and Virtual Reality Platforms*
- Inducted into the **National Society of Leadership and Success (NSLS)**
- Completed while simultaneously running a business and raising a family

### 🏛️ Bachelor of Science — Civil Engineering  
**Al-Mustansiriyah University** · *Baghdad, Iraq · 2009*

- Founded and operated a **telecommunications ISP during studies** that grew to serve nearly **60% of the country**

---

## 💼 Professional Experience

```
2026 — Present    Founder & Product Architect · HydraSec
2016 — 2024       Founder & Principal Engineer · Telecom Design Solutions, LLC
2024 — 2025       NOC Technician · Comcast Business
2021 — 2024       OSP Engineer II · Verizon
2013 — 2016       OSP Engineer · Rainbow Design Services
```

**Clients served:** Verizon · Spectrum · Comcast · Municipalities across the US

---

## 🛠️ Technical Skills

```python
SIEM_SOAR     = ["Microsoft Sentinel", "Splunk", "KQL", "SPL", "Azure Logic Apps"]
CLOUD         = ["Microsoft Azure", "Azure Defender", "NSGs", "Entra ID", "AMA", "DCR"]
SECURITY_OPS  = ["Alert Triage", "Incident Response", "Threat Hunting", "Honeypots", "MITRE ATT&CK"]
NETWORKING    = ["TCP/IP", "DNS", "VLANs", "Cisco", "FortiGate", "Zabbix"]
DEV_STACK     = ["Python", "FastAPI", "React", "SQLite", "JWT", "REST APIs"]
LANGUAGES     = ["English (Fluent)", "Arabic (Native)", "Japanese (Self-taught)"]
```

---

## 🌏 Japanese Language in Action

I taught myself Japanese **from books** — three scripts, thousands of characters, no classes, no teacher.

In 2011, I delivered a speech **in Japanese in front of the Japanese Ambassador** at the University of Jordan. I also collaborated with **JICA (Japan International Cooperation Agency)** to establish the first formal educational exchange program between Iraq and Japan.

🎥 [**Watch the Ambassador Speech →**](https://www.youtube.com/watch?v=DakeCiT-wnk)

> 🇯🇵 *この動画は、ヨルダン大学で開催された日本語イベントでのスピーチの様子です。日本大使の前で話す機会をいただき、大変光栄でした。*

---

## 🌍 The Story Behind the Profile

I built a telecom network covering 60% of Iraq as a student. Survived a religious war. Spent a year in hiding — and taught myself Japanese from books during that time. Immigrated to the United States with nothing. Built a telecom engineering company from zero. Earned a 4.0 GPA while running a business and raising a family. Worked in a NOC to understand security from the inside. And then built HydraSec.

I don't have a conventional path. I have a relentless one.

---

<div align="center">

**Omar Al-Fayyadh**  
Founder · Telecom Design Solutions, LLC · HydraSec  
📧 info@tdsllc.info · 📞 (331) 333-9484 · 📍 Naperville, IL

*Building at the intersection of infrastructure engineering and AI security.*

</div>
