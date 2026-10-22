# Sushil Tamang · SOC Analyst (L1) Portfolio
<!-- Portfolio README: defensive-security home labs + professional IT support, not production SOC employment. -->

<div align="center">
  <img src="./assets/soc-profile-banner.svg" alt="Sushil Tamang — Aspiring SOC Analyst (Level 1), Perth, Western Australia" width="100%" />

  <br />

  <img src="https://img.shields.io/badge/CAREER_GOAL-SOC_ANALYST_%7C_LEVEL_1-27c2b5?style=for-the-badge&amp;labelColor=102334" alt="Career goal: SOC Analyst Level 1" />
  <img src="https://img.shields.io/badge/FOCUS-SIEM_%26_ALERT_TRIAGE-418cf4?style=for-the-badge&amp;labelColor=102334" alt="Focus: SIEM and alert triage" />
  <img src="https://img.shields.io/badge/LOCATION-PERTH%2C_WA-64748b?style=for-the-badge&amp;labelColor=102334" alt="Location: Perth, Western Australia" />

  <p><strong>IT Support background • Hands-on defensive security labs • Seeking an entry-level SOC opportunity</strong></p>

  <a href="https://www.linkedin.com/in/sushiltamang10/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&amp;logo=linkedin&amp;logoColor=white" alt="Connect with me on LinkedIn" /></a>
  <a href="mailto:Susheelphakrin@gmail.com"><img src="https://img.shields.io/badge/Email-Let's_talk-0d9488?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Email me" /></a>
  <img src="https://img.shields.io/badge/Open_to-SOC_L1_%2F_Junior_Security_Analyst-22a06b?style=flat-square" alt="Open to SOC L1 and Junior Security Analyst opportunities" />
</div>

---

## 👋 About Me

I'm an **IT support professional and Master of Information Technology (Cybersecurity) student** based in Western Australia, working towards my **first SOC Analyst (Level 1)** role.

My professional experience at **Extratech Pty Ltd** includes troubleshooting Windows endpoints, responding to malware and access-related issues, supporting Microsoft Entra ID and MFA, administering Intune, and documenting and escalating service tickets. Alongside that experience, I've built **hands-on SOC home labs** to practise security monitoring, event analysis, alert triage, threat intelligence enrichment, and incident documentation.

I enjoy turning raw logs into a clear story: **what happened, which systems might be affected, what the evidence supports, and when to escalate**.

> 🎯 **Career focus:** SOC Analyst (L1) · Junior Cybersecurity Analyst · Security Operations Centre Analyst — **Perth, WA**
>
> My SOC experience is primarily **lab-based**; my professional experience is in **IT support**. I'm looking to apply both in a real security operations team.

## 🔍 How I Approach Level 1 SOC Triage

<div align="center">
  <img src="./assets/soc-l1-triage-workflow.svg" alt="SOC Level 1 workflow: monitor, validate, investigate, escalate, document" width="100%" />
</div>

| L1 responsibility | Practical experience |
| :--- | :--- |
| **Alert monitoring & initial triage** | Review Splunk and Wazuh alerts; examine endpoint and network telemetry in simulated environments. |
| **Log investigation** | Analyse Windows events, Sysmon telemetry, and Suricata IDS alerts to identify suspicious activity. |
| **Initial enrichment** | Use VirusTotal findings, source/destination context, and MITRE ATT&CK mapping to assess a signal. |
| **Classification & escalation** | Capture relevant evidence, describe potential impact, and provide clear handover notes to the next support tier. |
| **Incident documentation** | Apply ticketing, SLA awareness, structured troubleshooting, and communication habits gained from IT support. |

## 🧪 Featured SOC & Cybersecurity Labs

> My cybersecurity portfolio focuses on **SOC Level 1 fundamentals**: monitoring, log analysis, alert validation, investigation, clear escalation and documentation. Each project includes a dedicated walkthrough, architecture diagram and sample defensive-security material.

| Project | Stack | Documentation |
|:--|:--|:--|
| **01** 🛡️ Wazuh Active Response SOC Lab | Wazuh · pfSense · VirusTotal · FIM | [Explore project ↗](https://github.com/Ryalghost-SusheelTmz/wazuh-active-response-soc-lab) |
| **02** 📊 Splunk & Suricata Threat Detection | Splunk · Suricata IDS · SPL | [Explore project ↗](https://github.com/Ryalghost-SusheelTmz/splunk-suricata-threat-detection-lab) |
| **03** 🪟 Active Directory SIEM Detection | Windows Events · Sysmon · Splunk | [Explore project ↗](https://github.com/Ryalghost-SusheelTmz/active-directory-siem-detection-lab) |
| **04** 🤖 AI-Assisted Home SOC | Wazuh · Grafana · NetAlertX · AIRIA | [Explore project ↗](https://github.com/Ryalghost-SusheelTmz/ai-assisted-home-soc) |
| **05** 🌐 SafeLine WAF & DVWA Security Lab | SafeLine · Apache · DVWA · TLS | [Explore project ↗](https://github.com/Ryalghost-SusheelTmz/safeline-waf-dvwa-security-lab) |
| **06** 🔎 Web Vulnerability Assessment | OWASP ZAP · Burp Suite · Nessus · Power BI | [Explore project ↗](https://github.com/Ryalghost-SusheelTmz/web-vulnerability-assessment-capstone) |

<sub>**Publication status:** The six individual repository URLs above are reserved for project documentation currently being prepared for publication. Links will work once the corresponding repositories are created. Architecture graphics are illustrative; real lab screenshots and verified outputs will be added as available.</sub>

---

## 🚨 Example: How I'd Triage a Suspicious Sign-In Alert

*Illustrative L1 practice scenario — not a claim of handling a production SOC incident.*

| Step | Initial analyst action |
| :--- | :--- |
| **1. Review the alert** | Confirm alert time, host, account, source IP, and detection rule. |
| **2. Validate the evidence** | Check relevant Windows authentication logs (for example, Event ID `4625` for failed sign-ins) and nearby successful logons. |
| **3. Establish context** | Assess frequency, source location, affected accounts, and whether the behavior is expected. |
| **4. Assess & escalate** | Record indicators, possible impact, evidence links, and an escalation recommendation according to the playbook. |
| **5. Document the outcome** | Write clear case notes so another analyst can quickly continue the investigation. |

## 🧰 Tools & Technologies

**Security monitoring & investigation**

![Splunk](https://img.shields.io/badge/Splunk-151b28?style=flat-square&logo=splunk&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-1466b8?style=flat-square)
![Suricata](https://img.shields.io/badge/Suricata_IDS-de653b?style=flat-square)
![Sysmon](https://img.shields.io/badge/Sysmon-2667a8?style=flat-square)
![Grafana](https://img.shields.io/badge/Grafana-f46800?style=flat-square&logo=grafana&logoColor=white)
![VirusTotal](https://img.shields.io/badge/VirusTotal-3367d6?style=flat-square)
![MITRE ATTACK](https://img.shields.io/badge/MITRE_ATT%26CK-8d2d3d?style=flat-square)

**Systems, networking & scripting**

![Windows](https://img.shields.io/badge/Windows_Server-0a75d1?style=flat-square&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-29334a?style=flat-square&logo=linux&logoColor=white)
![Microsoft Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-295fae?style=flat-square)
![pfSense](https://img.shields.io/badge/pfSense-ca2739?style=flat-square)
![VMware](https://img.shields.io/badge/VMware-4c7188?style=flat-square)
![Python](https://img.shields.io/badge/Python-2b6494?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-226ab4?style=flat-square&logo=powershell&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2071ba?style=flat-square&logo=docker&logoColor=white)

## 💼 Relevant IT Support Experience

**IT Support Specialist (Part-time) | Extratech Pty Ltd**  
*October 2023 – January 2025 · Hurstville, NSW*

- Supported endpoint security, antivirus protection, identity/access management, MFA, and Windows troubleshooting.
- Worked with **Active Directory, Entra ID, Intune, Group Policy, DHCP, DNS, and VPNs**.
- Logged, prioritized and escalated technical incidents using **Zendesk**, with attention to SLA requirements and clear communication.

These foundations support the day-to-day discipline required in an L1 SOC: **technical investigation, prioritization, user context, ticket quality, and timely escalation**.

## 🎓 Education & Certifications

**Education**
- **Master of Information Technology (Cybersecurity)** — Kaplan Business School *(in progress)*
- **Bachelor of Information Technology** — Kent Institute of Sydney *(2022-2024)*

**Certifications & training listed on my resume**

![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B-c92b27?style=flat-square)
![CCNA](https://img.shields.io/badge/Cisco-CCNA-0877b6?style=flat-square)
![AZ-900](https://img.shields.io/badge/Microsoft-AZ--900-396caf?style=flat-square)
![ITIL 4](https://img.shields.io/badge/ITIL-4_Foundation-52525b?style=flat-square)
![TryHackMe](https://img.shields.io/badge/TryHackMe-Intro_to_Cyber_Security-b31f24?style=flat-square)

**Academic recognition:** High Achiever — Cyber Security & Digital Forensics (2026); Intermediate Programming & IT Project Management (2025).

## 🌱 Currently Developing

- More repeatable **alert-triage write-ups**, including log evidence, investigative steps, and escalation decisions.
- Stronger **Windows/Sysmon** and network detection analysis through home lab exercises.
- Practical familiarity with **SOC playbooks, prioritization, false-positive review, and defensive security operations**.

## 📬 Let's Connect

I'm interested in **SOC Analyst (Level 1)** and **Junior Cybersecurity Analyst** opportunities in **Perth, Western Australia**, including onsite and rostered environments.

- **LinkedIn:** [linkedin.com/in/sushiltamang10](https://www.linkedin.com/in/sushiltamang10/)
- **Email:** [Susheelphakrin@gmail.com](mailto:Susheelphakrin@gmail.com)

<div align="center">
  <sub>Built with curiosity, practical labs, and a commitment to clear security investigation.</sub>
</div>

<!-- Optional GitHub stats can be added after the individual lab repositories are published.
https://github-readme-stats.vercel.app/api?username=Ryalghost-SusheelTmz&show_icons=true&theme=tokyonight -->
