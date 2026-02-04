# Attack Simulation Diary

## Scenario
User runs a test PowerShell download command.

## Actions
- Executed benign PowerShell script
- Created test file
- Attempted outbound connection

## Telemetry Mapping
- Process creation captured by Event ID 1
- Network attempt captured by Event ID 3
- File creation captured by Event ID 11

## Detection Gaps
- Encrypted payload content
- DNS level visibility
- In-memory execution

## Kill Chain
Execution -> Network -> Persistence
