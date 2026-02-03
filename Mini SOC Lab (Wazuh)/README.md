# Mini Home SOC Lab – Wazuh SIEM Deployment

Personal project demonstrating Tier 1 SOC analyst skills using **Wazuh** (open-source SIEM/XDR).

## What I built

- Deployed Wazuh 4.14.2 all-in-one server using OVA in VirtualBox
- Installed & connected Wazuh agent on Windows 11 Pro
- Configured realtime File Integrity Monitoring (FIM) on custom folder
- Simulated privilege escalation (new user + added to Administrators)
- Detected Level 12 alert (Administrators Group Changed)
- Mapped behaviors to **MITRE ATT&CK** (T1098, T1078, T1074, etc.)
- Reviewed & triaged 500+ events

## Documentation

Full write-up with screenshots:  
📄 [Documentation.pdf]

## Screenshots

All evidence is in the `/screenshots/` folder:
- Agent installation & connection
- Custom FIM configuration
- File creation/deletion events
- Critical Level 12 alert
- Threat Hunting overview

## Key Learnings

- Group membership changes trigger high-severity alerts
- Realtime FIM is powerful but needs careful path selection
- Sysmon + Wazuh gives much better visibility

## Next Steps

- Write custom detection rules
- Run Atomic Red Team simulations
- Add Linux agent

Built by: **Nosa**  
Date: February 2026  
#CyberSecurity #SOC #BlueTeam #Wazuh #SIEM