# Control Room — Brain

This file is the single source of truth for this account. It auto-loads every session. All workflows, rules, and context live here.

> **Status: ACTIVE** — Imago Photography | Ashish Vishal | SEO

---

## FIRST-RUN SETUP

When this control room has not been personalized yet (you see "NEEDS SETUP" above), run the following onboarding automatically:

### Step 1 — Ask these questions (one block, wait for all answers)

```
Welcome to your Control Room. I need a few details to set this up for you.

1. YOUR NAME: (e.g., Diksha)
2. YOUR ROLE/FUNCTION: (e.g., SEO Specialist, Account Manager, Performance Marketing, Social Media, Content)
3. CLIENT NAME: (e.g., Wellspring Therapeutic Partners)
4. CLIENT INDUSTRY: (e.g., Healthcare, Painting, Insurance)
5. CLIENT LOCATION: (e.g., Michigan, USA)
6. KEY CLIENT CONTACTS: (Name + Role, one per line. e.g., "Jessica — Owner / Director")
7. KEY INTERNAL TEAM: (Name + Role, one per line. e.g., "Harshit — Account Lead")
8. MEETING CADENCE: (e.g., Weekly on Wednesdays, Biweekly on Thursdays)
9. WHAT DO YOU REPORT ON? (e.g., keyword rankings, ad performance, social engagement, lead volume)
10. ANY HARD STYLE RULES? (e.g., "No em dashes in client emails", "Always use metric units")
```

### Step 2 — Personalize this file

Using the answers, replace everything from `## Account Overview` downward with the personalized version. Change "NEEDS SETUP" to "ACTIVE" in the status line above.

### Step 3 — Check the transcripts/ folder

If the user has dropped any meeting transcripts or call recordings into `transcripts/`, process each one using Workflow 1 below.

### Step 4 — Confirm

```
Your control room is live. Here's what's set up:
- CLAUDE.md (this file) — personalized with your account details
- brief.md — ready for client intelligence
- meetings.md — ready for meeting logs
- next-steps.md — ready for action tracking
- feedback.md — ready for client signals
- deliverables.md — ready for deliverable logging

DROP ZONE: Paste a meeting transcript or say "process transcript" any time.
You can also drop files into the transcripts/ folder and say "process all transcripts."
```

---

## Account Overview

- **Client:** Imago Photography
- **Industry:** School Photography Services
- **Location:** United Kingdom
- **Account Owner:** Ashish Vishal (Damco Digital)
- **Meeting Cadence:** Weekly
- **Key contacts:** Will Cardwell — Co-founder, Imago & Imagotech

---

## Participants

| Name | Role | Side |
|---|---|---|
| Ashish Vishal | SEO Specialist | Agency |
| Harshit Kaushik | Account Manager | Agency |
| Will Cardwell | Co-founder | Client |

---

## File Structure

| File / Folder | Purpose |
|---|---|
| `CLAUDE.md` | This file. The brain. Auto-loaded every session. |
| `brief.md` | Living client brief. Updated after every meeting. |
| `meetings.md` | Index of all meetings with date, attendees, and link to MOM. |
| `next-steps.md` | Running action tracker. Updated after every meeting. |
| `feedback.md` | Client signals, preferences, approvals, and pushbacks. |
| `deliverables.md` | Full log of all deliverables produced for this account. |
| `deliverables/` | All output files stored here. |
| `emails/` | Outbound emails drafted for the client, stored by date. |
| `moms/YYYY-MM-DD/` | One folder per meeting: mom.md, actions.md, feedback.md. |
| `research/` | Internal research, keyword docs, benchmarks, competitive analysis. |
| `transcripts/` | Drop zone. Paste or save meeting transcripts here for processing. |

---

## Workflow 1 — When a Meeting Transcript is Shared

Run all steps automatically without being asked. Trigger: user pastes a transcript, shares a file, or says "process transcript."

### Step 1 — Identify the meeting date
Extract from the transcript or the user's message.

### Step 2 — Create the MOM folder
Create `moms/YYYY-MM-DD/` with three files:

#### `moms/YYYY-MM-DD/mom.md` — Client email (MOM)

```
Subject: MOM — Imago Photography [Meeting Type] | [Date]

Hi Will,

Great speaking with you today. Here's a quick recap of what we covered and what's next.

**What we discussed:**
- [3-5 bullets, crisp, one topic each, no jargon]

**Action items before our next call ([next meeting date]):**

| # | Action | Owner |
|---|---|---|
| ... | ... | ... |

Looking forward to [next date]. Let us know if anything comes up in the meantime.

Best,
Ashish
```

#### `moms/YYYY-MM-DD/actions.md` — Internal team briefing

```
Internal Team Briefing
Imago Photography — [DD Month YYYY] | Due before [next meeting date]

Key discussions to know:
- [One tight sentence per topic — what changed and why it matters]

Ashish's actions:
- [Specific action] | By [date]

Harshit's actions:
- [Specific action] | By [date]

[Only include people who have actions.]
```

#### `moms/YYYY-MM-DD/feedback.md` — Client signals

```
Client Signals
From Will Cardwell | [DD Month YYYY]

- [Signal, preference, approval, pushback, or constraint — one bullet per item]
```

5-8 bullets. Factual, no interpretation. Include: approvals, pushbacks, capacity constraints, audience intelligence, and anything that should influence future decisions.

### Step 3 — Update meetings.md
Add a row with the date, attendees, and link to the MOM folder.

### Step 4 — Update brief.md
Extract new client intelligence and append to the relevant sections. Look for:
- Staff changes or new hires
- Service capacity updates
- Target audience signals
- Brand or messaging preferences
- Seasonal or contextual insights
- Budget changes or constraints

Never overwrite existing content. Add a `[YYYY-MM-DD update]` tag when appending.

### Step 5 — Update next-steps.md
Extract all action items and add to the running to-do list with owner, source meeting, due date, and status.

### Step 6 — Update feedback.md
Append new client signals to the master feedback log.

### Step 7 — Produce the Linear update

```
Linear Update — Imago Photography | [DD Month YYYY]

Meeting: [Meeting Type] [Date]

What changed:
- [One sentence — key decision or shift]
- [One sentence — next priority or focus area]

Tasks:
| Owner | Task | Due |
|---|---|---|
| [Name] | [Task] | [Date] |
```

Ready to paste directly into Linear. Only include tasks with clear owners and deadlines.

---

## Workflow 2 — When a Deliverable is Produced

Log every deliverable in `deliverables.md` with:
- Date
- Deliverable name
- Type (presentation, report, email, document, prototype)
- Audience (client-facing or internal)
- File location

---

## Workflow 3 — Weekly Status Check

When the user says "status" or "where are we":
1. Read `next-steps.md` for open action items
2. Read the most recent MOM for last meeting context
3. Read `brief.md` for current client state
4. Produce a concise status summary: what's done, what's pending, what's overdue, and what's coming up

---

## Style Rules

- MOM emails: professional, warm, concise. Client-ready as-is.
- No jargon in client emails — write in plain English that Will can understand without an SEO background.
- All recommendations must be data-backed — cite the metric or source, never make claims without evidence.
- What we discussed: short bold headers per topic, one crisp paragraph each. Not bullet walls.
- Action items: specific and owned. No vague tasks.
- Brief updates: factual, no interpretation. Just what was said or observed.
- UK English spelling in all client-facing documents.

---

## SEO Module

### Reporting Metrics

Track and report on the following for Imago Photography:
- Organic traffic (sessions and trend)
- Keyword rankings (target keywords and movements)
- Click growth (Google Search Console)
- Backlinks (new links acquired, lost, domain authority)
- AI search visibility (appearances in SGE / AI Overviews / Perplexity / ChatGPT)

### Workflow — Keyword Tracking

Maintain a running keyword tracker in `research/keywords.md` with:
- Target keyword
- Current ranking position
- Search volume
- Difficulty score
- URL targeting this keyword
- Date last checked

When the user shares ranking data, update the tracker and flag:
- Keywords that moved up 5+ positions (wins)
- Keywords that dropped 5+ positions (alerts)
- New keywords entering top 20

### Workflow — Content Brief Generation

When the user says "content brief for [keyword]":
1. Check `research/keywords.md` for existing data on that keyword
2. Draft a content brief with: target keyword, secondary keywords, search intent, suggested title, H2 structure, word count target, competitor URLs to reference
3. Save to `research/content-briefs/[keyword-slug].md`
4. Log in `deliverables.md`

### Workflow — Competitor Analysis

Maintain `research/competitors.md` with:
- Competitor name and URL
- Domain authority (if known)
- Key pages ranking for target keywords
- Content gaps (topics they cover that we don't)
- Backlink intelligence

### SEO-Specific Files

| File | Purpose |
|---|---|
| `research/keywords.md` | Keyword tracking and ranking history |
| `research/competitors.md` | Competitor SEO analysis |
| `research/content-briefs/` | Content briefs for blog posts and pages |
| `research/technical-audit.md` | Technical SEO findings and fixes |
| `research/backlinks.md` | Backlink tracking and outreach |

### SEO Reporting Additions

When producing meeting MOMs or status updates, always include:
- Keyword ranking changes (top movers up and down)
- Organic traffic trend (if data is available)
- Content published since last meeting
- Technical fixes completed
- AI/LLM visibility notes (appearances in AI Overviews, ChatGPT, Perplexity)
