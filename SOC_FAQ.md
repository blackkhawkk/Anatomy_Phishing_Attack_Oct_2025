# 🎯 SOC Analyst Anti-Phishing Tools – FAQ

## 📌 Table of Contents
- [Introduction](#introduction)
- [General FAQs](#general-faqs)
- [Tool-Specific FAQs](#tool-specific-faqs)
- [Investigation Tools](#investigation-tools)
- [Simulation & Awareness](#simulation--awareness)
- [Threat Intelligence & SOC Integration](#threat-intelligence--soc-integration)
- [Advanced Detection Topics](#advanced-detection-topics)
- [Recommended SOC Stack (2025)](#recommended-soc-stack-2025)

---

## Introduction
This FAQ is designed for **SOC Analysts, Threat Hunters, and Blue Team Engineers** working on **phishing detection, investigation, threat intel correlation, and employee awareness operations** using tools like GoPhish, ThePhish, PhishTank, MISP, URLscan.io, Checkphish.ai, and more.

---

## General FAQs

| Question | Answer |
|----------|--------|
| **What is the best anti-phishing tool for SOC analysts?** | Tools like **ThePhish, GoPhish, PhishTank, MISP, Checkphish.ai, and URLscan.io** are widely used by SOC teams as of 2025. |
| **What are IOCs in phishing?** | **Indicators of Compromise (IOCs)** are phishing-related artifacts like malicious URLs, sender domains, attachments, IP addresses, and file hashes. |
| **What’s the difference between phishing and spam?** | **Spam** is bulk unsolicited email. **Phishing** is a targeted attack designed to steal credentials or data. |
| **Can these tools be used together?** | Yes. Combining **simulation, triage, IOC feeds, and automation** gives the best detection and response efficiency. |

---

## Tool-Specific FAQs

### GoPhish
- **What does GoPhish do?**  
  GoPhish is an **open-source phishing simulation framework** to test and report employee awareness levels.

### PhishTank
- **Is PhishTank free to use?**  
  Yes, PhishTank is a **free, community-driven phishing URL feed and verification platform**.

### Checkphish.ai
- **How does Checkphish.ai detect phishing?**  
  It uses **AI-based webpage analysis, DOM inspection, and visual pattern recognition** to flag phishing pages.

### ThePhish
- **What is ThePhish used for?**  
  ThePhish performs **email content, URL, and attachment analysis using machine learning scoring models**.

### MISP
- **Can MISP be used for phishing threats?**  
  Yes. **MISP shares phishing IOCs across SOC teams, enabling automated detection and correlation**.

### URLscan.io
- **How does URLscan.io help in phishing investigations?**  
  It provides **URL sandboxing**, **live screenshots**, **redirect tracing**, and **resource analysis** for forensic review.

---

## Investigation Tools

| Tool | Purpose |
|------|--------|
| **PhishTool** | GUI forensic email analysis: headers, attachments, URL scoring |
| **OLEtools** | Extracts **macros, scripts, and hidden URLs** from Office documents |
| **SpamAssassin** | Email gateway filtering using **heuristics and blacklist scoring** |
| **MailCleaner** | Blocks spam/malicious emails at **SMTP/WAF level** |
| **OpenPhish** | Real-time **phishing URL feed** |
| **PhishStats** | Tracks **live phishing URLs, target brands, hosting data** |

---

## Simulation & Awareness

| Question | Answer |
|----------|--------|
| **How does phishing simulation help employees?** | Improves **awareness and reaction time** against real phishing attempts. |
| **How often should simulations be conducted?** | **Monthly for high-risk sectors**, otherwise **quarterly**. |

---

## Threat Intelligence & SOC Integration

| Question | Answer |
|----------|--------|
| **Can these tools integrate with SIEM?** | Yes. Tools like **MISP, OpenPhish, PhishTool** provide APIs for SIEM alert ingestion. |
| **How do SOC teams respond quickly to phishing threats?** | By using **playbooks, IOC automation, phishing triage dashboards, and threat feeds**. |
| **How do I automatically block phishing URLs?** | **Ingest OpenPhish/PhishTank feeds into firewalls, email gateways, or SOAR automation.** |

---

## Advanced Detection Topics

| Question | Answer |
|----------|--------|
| **Can AI detect phishing better than signature tools?** | Yes. AI-based systems like **Checkphish.ai & ThePhish** detect phishing using **behavioral and visual indicators**, not just known patterns. |
| **Is QR code phishing detectable?** | Yes. **URLscan.io & Checkphish.ai** decode QR redirections to detect malicious endpoints. |

---

## Recommended SOC Stack (2025)

| Phase | Tools |
|------|------|
| **Awareness & Simulation** | GoPhish |
| **Inbound Triage & Detection** | ThePhish, PhishTool |
| **IOC Threat Intelligence** | MISP, OpenPhish, PhishTank |
| **URL & QR Analysis** | Checkphish.ai, URLscan.io |
| **Attachment & Macro Analysis** | OLEtools |
| **Email Gateway Filtering** | SpamAssassin, MailCleaner |
| **Automation & SIEM Integration** | MISP API, SOAR workflows |

---

## ✅ Contributing
Feel free to **add more phishing tools, API scripts, or SOC workflow automations** via pull request.

---

## 📎 License
This FAQ is provided under **MIT License** – free to use and modify for SOC & Threat Hunting documentation.

---
