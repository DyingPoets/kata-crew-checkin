# Field Crew Check-In — Monitoring Configuration
**Status:** Not configured
**Last updated:** [Session date]

## Current State

No production monitoring is configured. The app has been live for 3 weeks.
Failures are reported by field techs to their supervisors, who text the dispatcher.
Average time to detect a silent failure: unknown.

## What We Know Breaks

From the first 3 weeks of production:
- Check-in submissions occasionally fail silently (user sees success, no record created)
- GPS lookup times out on older Android devices (>8 sec = app appears frozen)
- Overnight batch job syncing check-ins to the payroll system has failed twice without alerting anyone

## Alert Configuration (To Be Designed)

| Alert Name | Trigger | Threshold | Who Gets Paged | Runbook |
|-----------|---------|-----------|----------------|---------|
| | | | | |

## Feedback Mechanism (To Be Designed)

| Design Decision | Choice | Rationale |
|----------------|--------|-----------|
| Question | | |
| Trigger (when to show) | | |
| Frequency cap | | |
| Data destination | | |
