# Detecting-Obfuscated-PowerShell-Attacks
A practical cybersecurity project focused on detecting obfuscated PowerShell attack patterns using Sysmon, Windows Event Logs, and ELK Stack integration. Includes real-world examples, threat detection rules, and log analysis techniques to identify malicious PowerShell behavior in enterprise environments.

# Importance of this project?
PowerShell is a go-to tool for administrators — and a goldmine for attackers. It’s built into Windows by default, trusted by most security software, and powerful enough to run scripts, pull down files, tweak system settings, and more.

This level of access makes it perfect for malicious use. Threat actors frequently rely on encoded PowerShell commands with switches like -EncodedCommand, -NoProfile, and -WindowStyle Hidden to fly under the radar. You’ll often find these tactics in:
- Phishing attacks and payload execution
- Early-stage malware delivery
- "Living off the land" scenarios using built-in tools
- Post-exploitation kits like Metasploit and Cobalt Strike

To defend against these threats, analysts need to understand what stealthy PowerShell abuse looks like and how to detect it.
This lab is designed to sharpen those skills. You’ll learn how to:
- Monitor endpoint behavior using Sysmon
- Forward logs efficiently with Winlogbeat
- Hunt threats with powerful KQL searches in Kibana
- Connect hands-on activity to key MITRE ATT&CK tactics like:
- - T1059.001 – Abuse of PowerShell
- - T1027 – Obfuscation of commands or files
- - T1105 – Transferring malicious files from remote sources

By the end, you’ll have the experience needed to spot and investigate one of the most common — and dangerous — attacker entry points in the Windows ecosystem.
