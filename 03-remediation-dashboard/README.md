# Project 3 — Control Deficiency Remediation Dashboard

## Overview
Developed and managed a control deficiency remediation tracking system consolidating open findings from internal assessments, vulnerability scans, and audits into a single governance view.

## Problem Statement
Findings from different sources were tracked in separate spreadsheets with no unified view, no consistent ownership, and no SLA tracking or escalation process.

## Dashboard Components

1. Finding Inventory — all open findings from all sources
2. SLA Tracker — severity-based target dates with breach flags
3. Ownership Matrix — clear accountability per finding
4. Escalation Flags — automatic flag for findings approaching SLA
5. Closure Verification — technical validation before marking closed
6. Executive Summary — weekly snapshot for governance reporting

## SLA Thresholds

| Severity | Remediation SLA |
|---|---|
| Critical | 48 hours |
| High | 7 days |
| Medium | 30 days |
| Low | 90 days |
| Informational | 180 days |

## Remediation Tracker Fields

| Field | Description |
|---|---|
| Finding ID | Unique reference |
| Source | Internal audit / Vulnerability scan / External audit / Compliance review |
| Finding Title | Short description |
| Severity | Critical / High / Medium / Low / Informational |
| Control Domain | Which control area the finding relates to |
| Finding Detail | Full description of the gap or deficiency |
| Recommended Action | Specific remediation steps |
| Owner | Accountable person |
| Date Identified | When finding was raised |
| SLA Target Date | Calculated from severity and identification date |
| Current Status | Open / In Progress / Closed / Accepted / Overdue |
| Closure Evidence | Reference to evidence of remediation |
| Verified By | GRC Analyst who confirmed closure |
| Closure Date | Actual date closed |

## Outcomes
- 100% SLA adherence on vulnerability remediation
- Average remediation cycle time reduced
- Leadership had always-current view of open obligations
