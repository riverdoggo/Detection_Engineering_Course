# Sysmon Baseline

## Event ID Matrix

### Event ID 1 – Process Creation
- Exposes attacker technique: execution of binaries and scripts
- Defenders care because it reveals initial access and tool usage
- Strengths: full command line and parent process context
- Blind spots: in-memory execution not visible

### Event ID 3 – Network Connection
- Exposes attacker C2 communication
- Defenders care to detect data exfiltration and beaconing
- Strengths: process to destination mapping
- Blind spots: encrypted traffic content

### Event ID 11 – File Creation
- Exposes dropped payloads and staged tools
- Useful for malware delivery tracking
- Blind spots: fileless attacks

### Event ID 13 – Registry Modification
- Exposes persistence and configuration changes
- Blind spots: indirect registry changes

## Detection Value Ranking
1. Event ID 1 – highest detection value, medium noise
2. Event ID 3 – high value, higher noise
3. Event ID 13 – medium value
4. Event ID 11 – situational value
