# SOC Analyst Portfolio

Hi, I'm Mansi Prajapati, an MSc Cybersecurity graduate (De Montfort University, 2026) based in Leicester, UK. I'm looking for a **Tier 1 SOC Analyst** role in the UK.

This repository holds my hands-on SOC lab projects. Each project follows the same five parts: goal, setup, what I did, what I found, and my analyst conclusion. I also write down what went wrong, because fixing problems is part of the job.

## Projects

| # | Project | Skills shown | Status |
|---|---------|--------------|--------|
| 1 | [Windows log monitoring with Wazuh](projects/01-windows-log-monitoring-wazuh/README.md) | SIEM setup, Windows Event ID 4625, MITRE ATT&CK T1110, Sysmon, alert triage | Done |
| 2 | Brute-force attack from Kali, detected in Wazuh | Attack simulation, detection, incident summary | Planned |
| 3 | Phishing email analysis | Email headers, link and attachment checks | Planned |
| 4 | Alert triage report | True vs false positive decisions | Planned |

## Lab environment

- VMware Workstation on a 16 GB laptop
- Wazuh server (Ubuntu Server 24.04): indexer, manager and dashboard
- Windows 10 victim VM with Sysmon and the Wazuh agent
- Kali Linux attacker VM

All testing is done inside my own isolated lab. I never test against systems I don't own.

## Contact

- LinkedIn: https://www.linkedin.com/in/mansi-prajapati-8b5273293
