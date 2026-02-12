# Findings - HK POS Ads Planning

## Confirmed Business Inputs
- Product: HK restaurant POS SaaS (B2B SMB)
- Primary target segment: single-store fast food / cha chaan teng owners (<=55)
- Month-1 priority timing segment: using POS now and contract near expiry (cost-down intent)
- Primary channel: Meta
- Conversion path priority: WhatsApp/phone consultation first, not pure app download

## Locked Operational Inputs
- Lead intake SLA target: first response within 5 minutes (daytime)
- Follow-up cadence: 3 touches within 24 hours
- Ad schedule: 09:00-22:00 (HKT)
- Language: Traditional Chinese only
- Public social proof assets: none available in month 1 (no public local case studies)

## Metrics and Definitions
- Month-1 success metrics:
  - Valid registrations
  - 7-day activation rate
- Effective activation event definition:
  1) registration/login complete
  2) printer + payment terminal binding complete
  3) menu setup complete
- Temporary baseline assumption:
  - 7-day activation rate = 30%
  - Denominator = successful login registrations

## Strategy Decisions (v1)
- Total budget: HKD 6,000 / 30 days
- Budget split:
  - C1 Consultation acquisition: HKD 4,200 (70%)
  - C2 Registration retargeting: HKD 1,800 (30%)
- Weekly ramp:
  - W1 1200 / W2 1400 / W3 1600 / W4 1800
- Audience packs:
  - A1 Broad restaurant owner
  - A2 Restaurant operations interests
  - A3 Contract-expiry cost-down angle
  - A4 High-intent retargeting (30d)
  - A5 Post-registration non-activated (14d)
- Optimization rule:
  - stop/scale with 48-hour observation after each budget increase

## Risks and Assumptions
- Risk: No public case proof may reduce trust at conversion stage.
- Risk: Attribution chain not fully validated (GA4 + Firebase + CRM alignment pending).
- Assumption: Sales can execute agreed SLA consistently during ad hours.

## Pending Data to Improve v1.1
- Real valid-conversation rate baseline
- Real consultation-to-registration conversion rate
- Real registration-to-effective-activation conversion and time-to-activate
