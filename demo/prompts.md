# Live Demo Prompt Script — Beyond the Chat Box

Prompts for the "Beyond the Chat Box: AI at Your Desk" webinar.
Designed for **live Cowork sessions** — paste each prompt into the
Cowork chat after pointing it at the right folder.

**Target runtime:** ~25 min total (~12 min Demo 1, ~13 min Demo 2),
inside a ~60-min webinar.

---

## Pre-Demo Setup

Before the webinar starts:

1. **Open Claude Desktop** in Cowork mode.
2. **Have a sandbox folder ready** at `demo/sample-business-folder/` containing
   3–5 plausible small-business files (sample invoice, an email saved as `.txt`
   or `.eml`, a one-page memo, a spreadsheet).
3. **Start a fresh Cowork session** — clean conversation, no prior history.

---

## Demo 1 — What's In My Folder? (~12 min)

### Folder to point Cowork at

`demo/sample-business-folder/`

### The Prompt

> Read everything in this folder. Then tell me:
>
> 1. What's here — a short index of files with one-line descriptions
> 2. What needs my attention this week — anything time-sensitive, decisions
>    owed, or follow-ups overdue
> 3. What's not here that probably should be — gaps you'd ask me about
>
> Don't write any files yet — just report back.

### What to narrate as Cowork works

- *"Notice Cowork is opening each file itself — I didn't have to upload them."*
- *"It's planning a sequence of actions first. That's the 'agentic' part."*
- When it produces the punch list: *"This came from reading actual files, not
  guessing from a description. That's the whole point."*

### Follow-up (if time)

> For the items you flagged as needing attention this week, draft a short
> reply or response for each one. Save the drafts as a single Word document
> in this folder called `Drafts_For_Review.docx`.

### Why this works

- Shows **folder context** (not file uploads)
- Shows **planning before action** (Cowork's chain-of-thought)
- Shows **writing real files** (.docx in your folder)

---

## Demo 2 — Saving Work as a Skill (~13 min)

### Option A — Save the Demo 1 prompt as a custom skill

After Demo 1 finishes, in the same session:

> Save what we just did as a skill called "Monday Briefing." It should:
>
> - Read the current working folder
> - Produce the same 3-part report (what's here, what needs attention,
>   what's missing)
> - Run once per week — set it up as a Monday morning scheduled task
>
> Tell me what you've saved and how I trigger it next week.

**Then** open a fresh chat and type `/monday-briefing` (or whatever skill
name Cowork shows) to demonstrate one-line re-running.

### Option B — Use a pre-built skill from the marketplace

> Show me what skills I have available right now. Pick one that's relevant
> for a small business owner — maybe inbox triage or a weekly briefing — and
> walk me through using it on this folder.

### What to narrate

- *"Watch how the saved skill turns 200 words of instruction into one
  command. That's the repetition tax going away."*
- *"Cowork can also install skills from a marketplace — Anthropic and other
  publishers ship skills you can use right away. The Small Business plugin
  alone gives you 15 pre-built workflows."*
- *"Scheduled tasks mean Cowork runs while you're not at your desk. The
  briefing's done when you sit down Monday morning."*

### Follow-up

> What other workflows in my week look like good candidates to turn into
> skills? Don't build them — just suggest 3 or 4 based on what you've seen
> in this folder.

### Why this works

- Shows **skills as the repetition cure**
- Shows **scheduled tasks** (a major Cowork-only feature)
- Closes the loop: Demo 1 was the "first time," Demo 2 is "every time after"

---

## Tips for the Presenter

- **Show the folder picker on screen** when starting — that visual
  ("Work in a folder") makes the whole concept click.
- **Don't rush past the planning step.** When Cowork shows its plan before
  acting, pause and read it aloud — that's the "auditable" promise.
- **If Cowork asks for approval**, narrate that out loud: *"Cowork is asking
  me to approve before it writes the file. That's the safety guardrail."*
- **If something fails live**, use it: *"That's actually a common scenario —
  let me show how Cowork handles it."* Re-prompt with more specificity.
- **If you're behind time**, skip Demo 1's follow-up and the
  "what other workflows" question. The save-as-skill moment is the lesson —
  protect it.
