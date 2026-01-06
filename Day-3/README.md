🔹 Day-3 – Basic Attack Simulation & Alert Verification
🎯 Objective

Perform basic attack simulations to validate that Wazuh is successfully collecting Windows security events and generating alerts.

✅ Tasks Completed Today
1️⃣ Simulated Failed Login Attempts

Performed multiple wrong password logins

Triggered Windows Security Event ID 4625

Verified alerts in Wazuh dashboard

Rule description observed:

“Login failure – Unknown user or bad password”

Successfully confirmed:

Log collection working

Agent communication successful

Wazuh correlation rules triggering

2️⃣ User Account Creation / Deletion Events

Created a new local user account

Deleted/modified the same user account

Observed alerts such as:

User account created

User account deleted or disabled

Validated tracking of account management activities

3️⃣ Group Membership Changes

Added user to local groups

Observed alerts like:

Administrators group changed

Domain users group changed

🛡️ MITRE ATT&CK Mapping
Activity	MITRE Technique
Failed Login Attempts	T1110 – Brute Force
Account Creation	T1136 – Create Account
Privilege/Group Change	T1098 – Account Manipulation
📊 Outcome

By the end of Day-3:

✔️ Wazuh agent successfully sending logs
✔️ Multiple alerts visible in Security Events
✔️ Basic adversary simulation validated
✔️ SIEM pipeline working end-to-end
✔️ You now understand how Wazuh reacts to Windows events

🚧 Future Work (Will Be Added Later)

The following tasks will be performed and documented later:

Enable and integrate Sysmon

Create custom Wazuh detection rules

Tune alert noise and false positives

Add file integrity monitoring (FIM)

Collect PowerShell operational logs

Simulate additional attacks:

Suspicious process execution

Persistence mechanism creation

Data exfiltration simulation

Malware execution lab

Build final SOC use-case library

🔜 These will be completed gradually as part of lab improvement.
