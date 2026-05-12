# Account Management Module

> This module is appended to CLAUDE.md during setup when the user's role is Account Manager.

---

## Account Management-Specific Workflows

### Workflow — Client Persona Files

For each key client contact, create a `[name].md` file at the root with:
- Communication style (direct, detail-oriented, big-picture, etc.)
- Decision-making pattern (quick, consensus-driven, analytical)
- Hot buttons (what excites them, what frustrates them)
- Preferred communication channel
- Personal notes (interests mentioned in calls, family, etc.)

Update these after every meeting based on observed signals.

### Workflow — Upsell Tracker

Maintain `research/upsell-opportunities.md` with:
- Opportunity description
- Date identified
- Signal (what the client said or did that suggests this)
- Status (Identified, Pitched, In Discussion, Won, Lost, Parked)
- Estimated value
- Next step

### Workflow — Weekly Performance Report

When the user says "weekly report" or shares performance data:
1. Parse all data sources
2. Build a structured report with KPIs, campaign breakdown, and observations
3. Include week-over-week deltas
4. Draft key observations and next steps
5. Present for approval before finalizing
6. Save to `reports/` and log in `deliverables.md`

### Workflow — Client Email Drafting

When the user says "draft email about [topic]":
1. Check `brief.md` for current client context
2. Check persona files for tone preferences
3. Draft email following the account's style rules
4. Save to `emails/YYYY-MM-DD-[topic-slug].md`

### Account Management-Specific Files

| File | Purpose |
|---|---|
| `[client-contact-name].md` | Personality and communication profiles |
| `research/upsell-opportunities.md` | Upsell tracking |
| `reports/` | Client-facing performance reports |
| `reports.md` | Report data archive |

### Account Management Reporting Additions

When producing meeting MOMs, always include:
- Cross-functional team actions (not just your own)
- Client signals that indicate satisfaction, risk, or growth opportunity
- Items requiring client decision before next meeting
- Internal coordination notes (who needs to sync with whom)
