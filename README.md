# SOC Detection Engineering Lab (Splunk + Sysmon + Windows Logs)

This project is a complete Detection Engineering home-lab built on Splunk, Sysmon, and Windows Event Logs.  
It includes 5 high-value SOC detections, MITRE ATT&CK mapping, attack simulation steps, screenshots, and Sigma rules.

---

## 📌 Project Objectives

- Deploy Splunk Free and configure log ingestion  
- Collect Windows Event Logs, Sysmon logs, Linux logs (optional)  
- Build detection rules aligned with MITRE ATT&CK  
- Test detections using simulated attacks  
- Document the detection logic and results  
- Showcase real SOC-level detection engineering skills  

---

## 📁 Repository Structure
## ✔ Detections Included

1. Suspicious PowerShell Execution  
2. Credential Dumping (Mimikatz Activity)  
3. C2 Beaconing (Periodic Outbound Traffic)  
4. Persistence via Run Keys  
5. Brute-Force Login Detection  

Each detection includes:
- SPL query  
- Sigma query  
- Testing instructions  
- MITRE mapping  
- Explanation of logic  

---

## 🔧 Log Sources Configured

- Windows Event Logs  
- Sysmon Operational Logs  
- Linux Auth logs (optional)  

---

## 🧪 Testing Attacks Used

- Encoded PowerShell execution  
- Mimikatz simulator behaviour  
- Registry Run-Key creation  
- Custom periodic beaconing script  
- Repeated failed logins  

Full steps are provided in **documentation/testing_guide.md**.

---

## 🧩 MITRE ATT&CK Techniques

Aligned to:  
- T1059.001 – PowerShell  
- T1003 – Credential Dumping  
- T1136 – Persistence Via Registry Run Keys  
- T1071 – Command & Control  
- T1110 – Brute Force  

See **documentation/mitre_mapping.md**

---

## 📸 Screenshots

Screenshots of alerts and dashboards are inside `/screenshots`.

---

## 📝 Author Notes

This lab replicates real SOC workflows and demonstrates practical Detection Engineering capability comparable to SOC Analyst L2 responsibilities.
