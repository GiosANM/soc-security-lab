# SOC Security Lab

A defensive cybersecurity lab documenting hands-on SOC practice.

## Lab Topics
- TCP/IP, DNS, HTTP and HTTPS traffic analysis
- Wireshark packet analysis
- Windows Event ID 4624 and 4625
- Sysmon fundamentals
- Wazuh/SIEM learning
- Alert triage and incident documentation

## Suggested Lab
```text
Windows Host
   |
 VMware
   |-- Kali Linux
   |-- Ubuntu Server / Wazuh
   `-- Windows Lab VM / Sysmon
```

## Repository
- `network-analysis/` — Wireshark exercises
- `windows-events/` — Windows log investigations
- `detection-notes/` — defensive detection ideas
- `incident-reports/` — report templates

Only use systems and data you own or are explicitly authorized to test. Sanitize screenshots/logs before publishing.
