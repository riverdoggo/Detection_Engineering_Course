# MITRE ATT&CK Mapping

| Detection | Tactic | Technique | Sub-technique | Reason |
|-----------|-------|-----------|---------------|-------|
| Suspicious Process Tree | Execution | T1059 | T1059.001 | Office spawning PowerShell |
| Credential Dumping | Credential Access | T1003 | T1003.001 | LSASS access attempts |
| Rare Process Execution | Defense Evasion | T1036 | - | Unusual binary usage |
| Suspicious Scheduled Task | Persistence | T1053 | T1053.005 | Task scheduler persistence |
| Suspicious Outbound Traffic | Command and Control | T1071 | - | Anomalous external connections |