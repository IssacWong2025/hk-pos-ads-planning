# Task Plan - HK POS Ads Planning

If resumed: read files in this order:
1) task_plan.md
2) findings.md
3) progress.md
4) docs/index.html

## Objective
Deliver and iterate an execution-ready first-month Meta ads strategy for Hong Kong restaurant POS with HKD 6,000 budget and clear weekly decision rules.

## Current Status
- Phase 1 complete: Strategy v1 published to HTML and GitHub Pages.
- Phase 2 complete: Copy/message refinement and creative production brief published in v1.1.
- Phase 3 in progress: Tracking and audience quality verification framework defined; waiting for real data validation.
- Phase 4 in progress: Weekly KPI dashboard and numeric thresholds now documented; pending week-level live calibration.
- Phase 5 in progress: v1.1 artifacts published; handoff questions prepared.

## Scope Lock (Do Not Change Without Explicit Approval)
- Channel: Meta only (Facebook / Instagram)
- Budget month 1: HKD 6,000
- Budget split: 70% consultation lead generation / 30% retargeting
- Market: Hong Kong
- Language: Traditional Chinese only
- Ad delivery window: 09:00-22:00 (HKT)

## Deliverables
- Live plan page: docs/index.html
- Version snapshot: docs/versions/*.html
- Change notes: CHANGELOG.md

## Definition of Done per Phase
- Phase 2 DoD:
  - 3 message angles finalized
  - Each angle has at least 2 creative variants (1:1 and 9:16)
  - Claims boundaries defined (what can/cannot be said)
- Phase 3 DoD:
  - Event definitions mapped to data source (Meta/GA4/Firebase/CRM)
  - Retargeting audiences validated for size and overlap
  - Exclusion logic confirmed
- Phase 4 DoD:
  - Weekly KPI panel fixed (lead volume, valid conversation rate, registration rate, activation rate)
  - stop/scale thresholds numeric and operationalized
- Phase 5 DoD:
  - v1.1 HTML published
  - Changelog updated
  - handoff note added for next session

## Open Questions (Need User Input)
1. Legal/compliance final boundary for cost-saving phrasing (what is strictly disallowed in ads).
2. Real creative asset inventory available this week (photos, videos, screenshots, UGC style clips).
3. Data reliability reality check for activation chain (Meta -> GA4/Firebase -> CRM match rate).

## Next Session First Actions
1. Confirm compliance whitelist/blacklist wording with legal/sales lead.
2. Collect first-week real metrics and compare with current KPI thresholds.
3. Validate audience overlap and exclusion in ad account, then adjust A1/A2/A3 split if needed.

## Error Log
| Date | Error | Attempt | Resolution | Notes |
|---|---|---:|---|---|
| 2026-02-12 | apply_patch context mismatch on legacy files | 1 | Replaced full file content instead of contextual patching | Triggered by encoding/content drift |
