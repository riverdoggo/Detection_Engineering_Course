# Sysmon Scope Decisions

## Excluded Telemetry

### DNS Logging
Not enabled due to high volume and overlap with network monitoring tools.
Risk accepted: some domain-based detections missed.
Will revisit if DNS tunneling becomes priority.

### Driver Loads
Excluded to reduce kernel level noise.
Risk accepted: advanced rootkit activity may be missed.

### Named Pipes
Not enabled because environment currently lacks known abuse cases.
Will reconsider if lateral movement activity increases.

## Engineering Tradeoffs
Focus is on stable, high signal telemetry first.
