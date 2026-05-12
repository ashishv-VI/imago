# SEO Module

> This module is appended to CLAUDE.md during setup when the user's role is SEO.

---

## SEO-Specific Workflows

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
- LLM/AI visibility notes (if applicable)
