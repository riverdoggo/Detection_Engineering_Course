# Detection Engineering — Week 3

This repository contains the complete Week 3 deliverables for a detection engineering lab focused on alerting, webhook ingestion, and receiver hardening.

## Overview
Week 3 bridges detection logic and automation by building a custom webhook receiver capable of ingesting Azure Monitor alerts safely and reliably.

## Contents
- Alerting concepts and alert-ready query design
- Webhook payload analysis
- FastAPI-based alert receiver
- End-to-end wiring and evidence
- Receiver hardening (auth, dedupe, rate limiting)

## How to Run
```bash
pip install -r requirements.txt
python -m uvicorn app.main:app --reload
```

POST alerts to:
http://127.0.0.1:8000/alert

Include header:
X-Alert-Secret: dev-secret

## Status
Week 3 complete. Ready for Week 4 control-plane detections.
