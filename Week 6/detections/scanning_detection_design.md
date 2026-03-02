# Scanning Detection Design

## Horizontal Scan
>25 distinct destination IPs in 5 minutes.
Deny ratio >40%.

## Vertical Scan
>15 distinct ports to same IP in 5 minutes.

## Suppression
- One alert per 30 min per source
- Allowlist security scanners
- Relax dev subnet thresholds

## Severity
Production scan: High
Internet noise: Low
Dev: Informational
