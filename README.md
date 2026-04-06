# 🛡️ SOC Lab Portfolio

## 🎯 Objective
This repository showcases my hands-on labs in Security Operations Center (SOC), focusing on log monitoring, threat detection, and incident analysis using tools like Wazuh, Splunk, and network security solutions.

---

## 🏗️ Lab Overview

| Lab Name              | Description                                      | Report |
|---------------------|--------------------------------------------------|--------|
| Wazuh Monitoring    | Deploy Wazuh Server + Agent for log monitoring   | 📄 [View Report](./wazuh-lab.docx) |
| Splunk SIEM         | Log analysis and detection using Splunk          | 📄 [View Report](./splunk-lab.docx) |

---

## 🔐 Lab 1: Wazuh SIEM Monitoring

### 🧩 Architecture
Attacker → Web Server (Wazuh Agent) → Wazuh Server
### ⚙️ Key Components
- Wazuh Server (SIEM)
- Wazuh Agent (on Web Server)
- Target: Web Application
- Attacker: Kali Linux

### 🚨 Detection Capabilities
- Log monitoring (authentication, system logs)
- Intrusion detection via Wazuh rules
- Alert generation and correlation

### 🧪 Use Cases
- SQL Injection detection
- XSS detection
- nmap scan port dectection
