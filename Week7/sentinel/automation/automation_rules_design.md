# SOC Automation Rules

## Rule: Privileged Account Activity

Condition:
Alert involves domain admin.

Action:
Increase severity to High and tag PrivilegedActivity.

Reason:
Privileged compromise increases risk.

---

## Rule: Multiple Alerts Same Host

Condition:
3 alerts from same host in 10 minutes.

Action:
Create incident automatically.

---

## Rule: Known Safe Process

Condition:
Alert matches known benign process.

Action:
Auto-close alert.

---

## Rule: Threat Intelligence Match

Condition:
IP matches threat intelligence feed.

Action:
Escalate severity and notify SOC.
