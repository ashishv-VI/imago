# Control Room Starter Kit
### Built by Harshit | Damco Digital

---

## What is this?

A pre-built project template for Claude Code that turns your client account into an organized, automated workspace. When you drop a meeting transcript, it automatically generates:
- A client-ready MOM email
- An internal team briefing with assigned actions
- A client signals log
- Updates to the living brief, action tracker, and meeting index
- A Linear-ready update you can paste directly

It also tracks deliverables, maintains a running client brief, and adapts to your specific function (SEO, Paid Ads, Social Media, Content, or Account Management).

---

## How to set up (5 minutes)

### Step 1 — Download and extract
Unzip the `control-room-starter-kit.zip` file. You'll get a folder called `Control Room Starter Kit`.

### Step 2 — Rename the folder
Rename it to your client's name. Example: `Wellspring Control Room` or `Ark Painting CR`.

### Step 3 — Move it to your Documents
Put the renamed folder in `Documents/` (or wherever you keep your Claude Code projects).

### Step 4 — Open in Claude Code
Open Claude Code and navigate to your new folder. The CLAUDE.md file will auto-load.

### Step 5 — Run setup
Type: **"set up this control room"**

Claude will ask you 10 questions about your role, your client, and your team. Answer them, and it personalizes everything automatically. It also detects your function and adds the right module (SEO workflows for SEO people, ad tracking for paid ads people, etc.).

### Step 6 — Drop your transcripts
If you have meeting transcripts, paste them into the chat or drop them into the `transcripts/` folder and say "process all transcripts." Claude will process each one and build your meeting history, action tracker, and brief automatically.

---

## What's inside

```
Your Client CR/
  CLAUDE.md              <-- The brain. Auto-loads. Holds all rules and workflows.
  brief.md               <-- Living client brief. Grows after every meeting.
  meetings.md            <-- Meeting index with links to MOMs.
  next-steps.md          <-- Running action tracker.
  feedback.md            <-- Client signals and preferences.
  deliverables.md        <-- Log of everything produced.
  modules/               <-- Function-specific add-ons (auto-selected during setup)
    seo.md
    paid-ads.md
    social-media.md
    content.md
    account-management.md
  moms/                  <-- One folder per meeting with MOM, actions, signals
  deliverables/          <-- Output files go here
  research/              <-- Keyword docs, competitor analysis, benchmarks
  emails/                <-- Drafted client emails
  transcripts/           <-- DROP ZONE: put meeting transcripts here
```

---

## Daily usage

| You want to... | Just say... |
|---|---|
| Process a meeting | Paste the transcript, or say "process transcript" |
| Check account status | "Where are we?" or "status" |
| Draft a client email | "Draft email about [topic]" |
| See open action items | "What's pending?" |
| Log a deliverable | "Log deliverable: [name]" |
| Update the brief | "Add to brief: [new info]" |
| Get a Linear update | "Linear update" |

---

## Tips

- **Transcripts are the fuel.** The more meetings you process, the smarter your control room gets. The brief, feedback log, and action tracker all grow from transcripts.
- **Don't edit CLAUDE.md manually** unless you're adding new workflows or style rules. The setup process handles personalization.
- **The modules/ folder** contains role-specific workflows. During setup, the right one gets merged into your CLAUDE.md. You can also manually add workflows from other modules if your role overlaps.
- **The transcripts/ folder** is a drop zone. Save .txt or .md files there and say "process all transcripts" to batch-process them.

---

## Questions?
Ask Harshit. Or just ask Claude — it knows how this system works.
