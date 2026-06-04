# SOC Home Lab

## Overview
Enterprise-grade SOC simulation environment built for 
threat detection, incident response, and security automation.

## Architecture
![Architecture](architecture/diagram.png)

## Components
| Component | Role | Status |
|---|---|---|
| ELK 8.x (Contabo VPS) | SIEM | ✅ Live |
| Elastic Agent + Fleet | Log collection | ✅ Live |
| Elastic Defend | EDR | ✅ Live |
| pfSense | Firewall / IDS | ✅ Live |
| Windows Server 2022 | Active Directory | 🔄 In Progress |
| Windows 10 | Endpoint | 🔄 In Progress |
| Juice Shop (Docker) | Vulnerable app | 📅 Planned |
| TheHive + Cortex | IR Platform | 📅 Planned |
| Shuffle SOAR | Automation | 📅 Planned |

## Detection Rules
| Rule | MITRE ID | Status |
|---|---|---|
| PowerShell Encoded Command | T1059.001 | 📅 Planned |
| LSASS Dump | T1003.001 | 📅 Planned |
| Scheduled Task Persistence | T1053.005 | 📅 Planned |
| Ransomware Simulation | T1486 | 📅 Planned |
| HTTP C2 Traffic | T1071.001 | 📅 Planned |

## IR Cases
| Case | Status |
|---|---|
| Case 01 — Phishing Campaign | 📅 Planned |
| Case 02 — Ransomware Simulation | 📅 Planned |
| Case 03 — Lateral Movement | 📅 Planned |

## Tools & Technologies
`ELK 8.x` `pfSense` `Sysmon` `Elastic Agent` 
`TheHive` `Cortex` `Shuffle` `Atomic Red Team` `GoPhish`