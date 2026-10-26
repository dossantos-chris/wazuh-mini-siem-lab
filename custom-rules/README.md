# Custom Wazuh Rules

`local_rules.xml` contains five example rules for the Windows/Sysmon lab.

- **100101 — PowerShell process creation:** records PowerShell process starts (Event ID 1).
- **100102 — Command Prompt process creation:** records `cmd.exe` starts (Event ID 1).
- **100103 — File creation:** records Sysmon file-creation events (Event ID 11).
- **100104 — Registry value modification:** records Sysmon registry-value-set events (Event ID 13).
- **100105 — Office spawning PowerShell:** highlights PowerShell whose recorded parent image is Word, Excel, PowerPoint, or Outlook (Event ID 1).

The first four are broad visibility rules and can be noisy. The fifth is a higher-priority investigation lead.
