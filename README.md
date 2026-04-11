# 🔐 Indicators of Compromise (IOC) Detection & Incident Response Project


## 📌 Overview

In today's evolving threat landscape, organizations face increasingly sophisticated cyber attacks. This project focuses on identifying, analyzing, and responding to **Indicators of Compromise (IOCs)** using a structured incident response methodology.

It demonstrates how cybersecurity analysts leverage **forensics, threat intelligence, and detection engineering** to detect malicious activity and secure compromised systems.

---

## 🚨 Problem Statement

Traditional security mechanisms often fail to detect advanced threats in real time. Organizations require:

- Faster detection of malicious activities  
- Efficient triage and investigation processes  
- Strong incident response strategies  
- Integration of threat intelligence into workflows  

This project addresses these challenges by implementing an **IOC-driven detection and response model**.

---

## 🎯 Objectives

- Develop a strong understanding of IOC-based threat detection  
- Simulate real-world incident response scenarios  
- Perform forensic analysis across multiple system layers  
- Analyze malware using hash-based intelligence  
- Design mitigation and eradication strategies  
- Improve overall security posture using actionable insights  

---

## 🏗️ Architecture & Workflow

    +----------------------+
    |  Suspicious Activity |
    +----------+-----------+
               |
               v
    +----------------------+
    |   IOC Identification |
    +----------+-----------+
               |
               v
    +----------------------+
    |   Detection Engine   |
    | (AV, Logs, Network)  |
    +----------+-----------+
               |
               v
    +----------------------+
    |   Triage & Analysis  |
    +----------+-----------+
               |
               v
    +----------------------+
    |   Forensic Evidence  |
    | (Disk, Memory, Logs) |
    +----------+-----------+
               |
               v
    +----------------------+
    | Mitigation & Response|
    +----------+-----------+
               |
               v
    +----------------------+
    | Eradication & Review |
    +----------------------+



---

## 🧠 Indicators of Compromise (IOCs)

IOCs are **observable artifacts** that indicate a system compromise.

### 🔍 Categories of IOCs

| Category        | Examples                                      |
|----------------|----------------------------------------------|
| File-based     | Hash values (MD5, SHA-256), file paths       |
| Network-based  | IP addresses, DNS queries, URLs              |
| Host-based     | Registry keys, processes, services           |
| Behavioral     | Unusual login patterns, privilege escalation |
| Memory-based   | Injected code, suspicious processes          |

---

## 🔄 Incident Response Lifecycle

### 1. Identification
- Detect abnormal system behavior  
- Alerts triggered by antivirus or monitoring tools  

### 2. Triage
- Collect indicators (hashes, logs, IPs)  
- Assess severity and impact  
- Prioritize response  

### 3. Containment
- Isolate affected systems  
- Block malicious connections  

### 4. Investigation
- Perform forensic analysis  
- Correlate logs, memory, and file system artifacts  

### 5. Eradication
- Remove malware and persistence mechanisms  
- Patch vulnerabilities  

### 6. Recovery
- Restore systems  
- Monitor for reinfection  

---

## 🛰️ Detection Techniques

### 🔹 Signature-Based Detection
- Hash comparison with known malware databases  

### 🔹 Behavior-Based Detection
- Detect anomalies in system or user behavior  

### 🔹 Log Analysis
- Firewall logs  
- System logs  
- Authentication logs  

### 🔹 Threat Intelligence
- IOC matching with external databases  

---

## 🧾 Digital Forensics & Evidence Collection

### Key Evidence Sources

| Source           | Description                              |
|----------------|------------------------------------------|
| File System     | Suspicious files and metadata           |
| Network Logs    | Traffic patterns and connections        |
| Event Logs      | System and authentication events        |
| Registry        | Persistence mechanisms                  |
| Memory Dumps    | Running processes and injected code     |
| Endpoint Logs   | User and application activity           |

---

## 🔐 Hash Analysis & Malware Investigation

### 🔹 Algorithms Used
- MD5  
- SHA-1  
- SHA-256  

### 🔹 Workflow
1. Extract files from compromised system  
2. Generate hash values  
3. Compare with threat intelligence sources  
4. Identify malicious artifacts  

---

## 🧪 Tools & Technologies

### 🔍 Threat Intelligence
- VirusTotal  
- Malware Bazaar  

### 🧠 Memory Forensics
- Volatility Framework  

### 🛡️ Threat Hunting
- Cybereason  
- Endgame  
- Sqrrl  

### ⚙️ Analysis Tools
- Firewall logs  
- Antivirus tools  
- Hash utilities  

---

## 🧬 Case Study: Malware Analysis using Hash Intelligence

### 📥 Source
- Malware Bazaar  
- Focus: **Mirai Malware Family**

### 🔍 Analysis using VirusTotal

- Multi-engine scan results  
- File reputation scoring  
- Hash identification  
- Related artifacts (domains, IPs, URLs)  

### 📊 Key Insights
- Detection ratios  
- Behavioral analysis  
- Threat intelligence correlations  

---

## 🛡️ Mitigation & Defense Strategies

- Isolate compromised systems  
- Apply patches and updates  
- Run full system scans  
- Reset credentials and enforce MFA  
- Block malicious IPs/domains  
- Deploy EDR solutions  
- Conduct security awareness training  

---

## ❌ Eradication & Recovery

- Remove malware artifacts  
- Eliminate persistence mechanisms  
- Clean registry entries  
- Harden systems  
- Continuous monitoring (SIEM/EDR)  

---

## 📊 Key Learnings

- IOCs enable early threat detection  
- Correlation across multiple sources is critical  
- Hash-based detection should be combined with behavior analysis  
- Structured incident response is essential  

---

## 🚀 Future Enhancements

- Integrate SIEM tools (Splunk, Wazuh)  
- Automate IOC pipelines  
- Implement real-time alerting  
- Add ML-based anomaly detection  
- Expand malware dataset  

---

## 📚 References

- https://www.virustotal.com  
- NIST Incident Response Framework  
- MITRE ATT&CK Framework  

---

## 👤 Author

**Revathi Chundi**  
Cybersecurity Graduate Student | SOC Analyst | Threat Hunter  

---
