# Sample Log Onboarding Request

## Request Summary
Onboard application audit logs into a SIEM platform for centralized monitoring and search.

## Source Details
- Source name: Example Application Audit Logs
- Environment: Production
- Owner: Application Support Team
- Log format: JSON
- Transport: HTTPS Event Collector

## SIEM Details
- Index: app_audit
- Sourcetype: json:exampleapp:audit

## Expected Volume
Approximately 2 GB per day.

## Required Fields
- timestamp
- username
- action
- result
- source_ip
- hostname

## Validation Requirements
- confirm ingestion
- confirm timestamp parsing
- confirm searchable fields
- confirm no duplicate ingestion
