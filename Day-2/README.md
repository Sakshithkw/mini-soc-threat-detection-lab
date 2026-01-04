# Day-2 – Wazuh SIEM Setup & Windows Agent Installation

## Tasks Completed
- Installed Wazuh SIEM
- Installed Windows Wazuh Agent
- Successfully connected Windows agent to Wazuh Manager dashboard

## Environment Details

| Component        | Details           |
|------------------|-------------------|
| SIEM             | Wazuh             |
| Manager OS       | Ubuntu Server     |
| Endpoint OS      | Windows 10        |
| Agent Status     | Active / Connected |
| Wazuh Version    | 4.7.x             |

## What I Verified
- Agent shows **Connected** in Wazuh UI
- Endpoint appears under **Agents list**
- Heartbeat communication is working

## What I Will Do Next (Day-3 Plan)
- Deploy Sysmon on Windows
- Generate logs & alerts
- Perform attack simulation (Brute force / Mimikatz / Suspicious process)
- Analyze alerts in Wazuh SIEM
