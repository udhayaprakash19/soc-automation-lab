# soc-automation-lab
## Architecture
![SOC Automation Architecture](<img width="728" height="490" alt="Screenshot 2026-07-05 024307" src="https://github.com/user-attachments/assets/4a4e090a-1895-4b50-83fc-66e7d8b538d0" />
)
A home SOC automation lab built with Wazuh, Shuffle, and TheHive.
This project demonstrates a home Security Operations Center (SOC) automation lab using:

- Wazuh
- Shuffle
- TheHive
- Windows 10 Endpoint

## Workflow

1. Windows endpoint generates security events.
2. Wazuh detects suspicious activity.
3. Shuffle receives alerts.
4. Shuffle enriches IOCs.
5. TheHive creates a case.
6. SOC analyst reviews the alert.
7. Wazuh executes an automated response.

## Status

🚧 Work in Progress

This repository documents my learning journey in SOC automation and incident response.
