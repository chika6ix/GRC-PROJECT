# Project 1 — IT Compliance Monitoring Framework

## Overview
Designed and implemented an IT compliance monitoring framework at CyBlack (UK), incorporating ISO 27001, NIST CSF, and CIS Controls into a unified governance view across six control domains.

## Problem Statement
The organisation had no centralised view of compliance posture. Controls were assessed ad hoc, KPIs were undefined, and executive leadership had no visibility into the security programme effectiveness.

## What I Built
- Defined six control domains: Access Management, Vulnerability Management, Incident Response, Change Management, Data Protection, Third-Party Risk
- Defined KPIs for each domain (patch compliance %, MFA adoption rate, open vulnerability count by severity)
- Automated data collection via Splunk dashboards
- Produced monthly executive compliance reports with RAG status by domain

## Framework Mapping

| Domain | ISO 27001 Annex A | NIST CSF | CIS Controls |
|---|---|---|---|
| Access Management | A.9 | PR.AC | CIS 5, 6 |
| Vulnerability Management | A.12.6 | DE.CM | CIS 7 |
| Incident Response | A.16 | RS.RP | CIS 17 |
| Change Management | A.12.1 | PR.IP | CIS 4 |
| Data Protection | A.8, A.18 | PR.DS | CIS 3 |
| Third-Party Risk | A.15 | ID.SC | CIS 15 |

## Outcomes
- Executive leadership gained a real-time compliance posture view
- KPI dashboards used directly in monthly governance meetings
- Control gaps identified and tracked through to remediation
