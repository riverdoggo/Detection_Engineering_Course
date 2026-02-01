# Week 4 — Azure Control-Plane Detection Strategy

Week 4 focuses on **control-plane threat detection design** in Microsoft Azure.
The objective is not tooling or portal interaction, but **analytical detection engineering**:
identifying high-impact attacker actions, mapping them to telemetry, and defining
clear alerting and response logic.

This week demonstrates:
- Threat modeling of Azure control-plane abuse
- High-signal detection logic based on AzureActivity telemetry
- Severity modeling and alert governance
- MITRE ATT&CK alignment
- Kill-chain validation

No live Azure subscription is required.
All detections are derived from documented control-plane telemetry.
