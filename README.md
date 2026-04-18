# Active Directory SOC Detection Lab

## Overview
A home SOC lab environment built to simulate real enterprise attacks and detect 
them using industry-standard tools. This project demonstrates hands-on experience 
with Active Directory, Sysmon, Splunk SIEM, and MITRE ATT&CK-mapped attack 
simulation using Atomic Red Team.

## Lab Architecture
| Machine | OS | Role |
|---|---|---|
| DC01 | Windows Server 2022 | Active Directory Domain Controller |
| TARGET-PC | Windows 10 Enterprise | Domain-joined victim machine + Sysmon |
| SIEM | Ubuntu Server 22.04 | Splunk SIEM — log ingestion & detection |
| ATTACKER | Kali Linux | Attack simulation (brute force, credential dumping) |

## Tools & Technologies
- **Hypervisor:** VirtualBox 7.2.6
- **SIEM:** Splunk Enterprise
- **Logging:** Sysmon (SwiftOnSecurity config)
- **Attack Simulation:** Atomic Red Team (MITRE ATT&CK)
- **Frameworks:** MITRE ATT&CK, Cyber Kill Chain

## Project Status
🔨 In Progress — Environment Setup Phase

## Phases
- [ ] Phase 1: Environment Setup & VM Configuration
- [ ] Phase 2: Active Directory Setup
- [ ] Phase 3: Sysmon + Splunk Installation & Log Ingestion
- [ ] Phase 4: Attack Simulation with Atomic Red Team
- [ ] Phase 5: Detections, Alerts & Dashboards
- [ ] Phase 6: Documentation & Write-up
