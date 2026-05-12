# Paid Ads Module

> This module is appended to CLAUDE.md during setup when the user's role is Paid Ads / Performance Marketing.

---

## Paid Ads-Specific Workflows

### Workflow — Campaign Tracker

Maintain `research/campaigns.md` with a running log of:
- Campaign name
- Platform (Google Ads, Meta, LinkedIn)
- Status (Active, Paused, Ended)
- Budget (daily/monthly)
- Key metrics: spend, impressions, clicks, CTR, CPC, conversions, cost per conversion
- Date range

### Workflow — Performance Report Processing

When the user shares performance data or says "process report":
1. Parse all metrics
2. Calculate week-over-week or period-over-period deltas
3. Append to `reports.md` using the standard format
4. Flag: campaigns with rising CPC, declining CTR, or cost per conversion above target
5. Flag: campaigns with strong performance worth scaling

### Workflow — Creative Tracker

Maintain `research/creatives.md` with:
- Creative name/ID
- Platform
- Format (static, carousel, video, responsive)
- Status (Live, Paused, In Review)
- Launch date
- Key metrics (CTR, conversion rate)
- Fatigue status (frequency check)

### Workflow — Budget Pacing

When the user shares budget data:
- Calculate daily run rate vs. monthly budget
- Flag underspend (less than 85% pacing) or overspend (more than 105% pacing)
- Project month-end spend at current rate

### Paid Ads-Specific Files

| File | Purpose |
|---|---|
| `research/campaigns.md` | Campaign tracker with metrics |
| `research/creatives.md` | Creative asset tracker |
| `research/audiences.md` | Audience targeting notes and performance |
| `research/budget-pacing.md` | Monthly budget tracking |
| `reports.md` | Performance reports, appended chronologically |

### Paid Ads Reporting Additions

When producing meeting MOMs or status updates, always include:
- Total spend vs. budget
- Lead/conversion volume and cost per conversion
- Top performing campaign and worst performing campaign
- Any creative refreshes needed
- Platform-specific flags (disapprovals, policy issues, frequency fatigue)
