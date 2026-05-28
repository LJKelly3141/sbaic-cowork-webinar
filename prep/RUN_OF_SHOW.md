# Run-of-Show — Beyond the Chat Box: AI at Your Desk

**Length target:** ~60 minutes total
~5 min open · ~15 min concept slides · ~25 min demo · ~5 min takeaways · ~10 min Q&A

**Presenter:** Dr. Logan Kelly · Small Business AI Center
**Hosted by:** TBD
**Date:** TBD 2026

---

## Timing Block

| Block | Slide(s) | Time | Cumulative |
|-------|----------|------|------------|
| Open + intro | Title | 2 min | 2 |
| Today's Plan | Today's Plan | 1 min | 3 |
| **Chat vs. Cowork** | Chat vs. Cowork | 3 min | 6 |
| What Makes Cowork Different | What Makes Cowork Different | 3 min | 9 |
| Three Steps to Start | Three Steps | 1 min | 10 |
| Step 1: Install | Step 1 | 2 min | 12 |
| Step 2: `/setup-cowork` | Step 2 | 2 min | 14 |
| Step 3: Pick a Folder | Step 3 | 2 min | 16 |
| Privacy & Trust | Privacy & Trust | 2 min | 18 |
| Section: Live Demo | (section header) | 1 min | 19 |
| **Demo 1: What's In My Folder?** | Demo 1 | 12 min | 31 |
| **Demo 2: Saving Work as a Skill** | Demo 2 | 13 min | 44 |
| Section: Your Move | (section header) | 1 min | 45 |
| Three Things to Try | Three Things | 2 min | 47 |
| Resources & Contact | Resources & Contact | 2 min | 49 |
| Q&A | Q&A | 10–11 min | 59–60 |

> **Buffer rule:** If you're at minute 35 and haven't finished Demo 2's
> save-as-skill moment, skip the "what other workflows" follow-up. If at
> minute 45 you haven't reached Your Move, jump straight to Resources & Q&A.

---

## Slide-by-Slide Notes

### Title (2 min)
- Welcome. *"Today is mostly demo. By the end, you'll know how to install
  Cowork, what your first session looks like, and how to make AI work
  repeatable."*

### Today's Plan (1 min)
- Set expectations: short on theory, heavy on demo.

### Chat vs. Cowork (3 min)
- **This is THE slide.** Walk every row. The takeaway: *"Chat is for asking;
  Cowork is for doing."*
- Anecdote: *"The Capital Readiness webinar I did last month used Chat.
  Every demo started with 'upload these two files.' Cowork removes that step."*

### What Makes Cowork Different (3 min)
- Six bullets. Don't list — pause on each.
- Skills + scheduled tasks are the underrated ones. Mention 15 prebuilt
  Small Business workflows ship out of the box.

### Three Steps to Start (1 min)
- Roadmap slide. *"Install, run setup, pick a folder. We'll do each."*

### Step 1 — Install (2 min)
- Be explicit about Windows Pro + Hyper-V. People get stuck here.
- Mention free tier doesn't include Cowork — Pro at $20/mo or higher.

### Step 2 — `/setup-cowork` (2 min)
- Role-matched plugin install is the underrated trick.
- Mention: *"You don't have to know what plugin you need — Cowork picks
  based on what you do."*

### Step 3 — Pick a Folder (2 min)
- If feasible, **show the folder picker live** in Cowork.
- Sound bite: *"The folder is your scope of trust. Cowork sees what's in
  it, and nothing else."*

### Privacy & Trust (2 min)
- Address this proactively. *"Isolated VM. Files don't leave. You approve
  every write."*
- Common question to pre-empt: *"Yes, you can use it on customer data —
  the files don't go to the cloud for training."*

### Section: Live Demo (1 min)
- *"Two demos. First: 'what's in my folder.' Second: 'save that as a skill
  so I never type that prompt again.'"*

### Demo 1 — What's In My Folder? (12 min)
1. **(1 min)** Show the `demo/sample-business-folder/` in Finder/Explorer.
   *"Here's the folder. A few files. Cowork's never seen them."*
2. **(1 min)** Click "Work in a folder" → point at that folder. *"This is the
   whole 'context engineering' for Cowork."*
3. **(1 min)** Paste the Demo 1 prompt from `demo/prompts.md`. Read it aloud.
4. **(7 min)** Submit. Narrate Cowork's planning step, then its work as it
   opens files. *"Notice it's reading the spreadsheet directly. It doesn't
   need an upload."*
5. **(2 min)** Punch list arrives. Critique one item: *"That follow-up
   suggestion is good. This one I'd push back on — let me show you why."*

### Demo 2 — Saving Work as a Skill (13 min)
1. **(1 min)** Frame: *"That prompt I just typed? I'll never type it again.
   Watch this."*
2. **(1 min)** Paste the Option A "Save as Monday Briefing" prompt.
3. **(5 min)** Cowork creates the skill + schedules a recurring task.
   Narrate: *"This is the repetition tax going away."*
4. **(2 min)** Open a fresh chat. Type `/monday-briefing` or whatever name
   Cowork registered. *"One command. Same result."*
5. **(2 min)** If time, demo a pre-built marketplace skill briefly.
6. **(2 min)** Wrap: *"You just saw the two big shifts. Folder = scope.
   Skill = repeatability."*

### Section: Your Move (1 min)
- Energy pivot. *"Three things you can do this week."*

### Three Things to Try This Week (2 min)
- Read each one. Mention they're in the handout.

### Resources & Contact (2 min)
- `claude.com/download` for the app.
- Point to handout for full link list and reference reading.

### Q&A (10+ min)
- Common questions to be ready for:
  - *"Does this work on Windows Home?"* — No, Hyper-V required.
  - *"What about my data?"* — Local VM, doesn't leave machine.
  - *"What if Cowork does something wrong?"* — You approve every write.
  - *"How do I share a skill with my team?"* — Plugins / marketplace.
  - *"Can I use this without paying?"* — No, Pro plan minimum.

---

## Things to Have Open On Your Screen

| Tab / Window | What For |
|--------------|---------|
| Slide deck (full-screen, presenter view) | Main presentation |
| **Claude Desktop in Cowork mode** | Live demo |
| `demo/sample-business-folder/` in Finder/Explorer | Show the folder visually |
| `demo/prompts.md` | Copy-paste source |
| `prep/RUN_OF_SHOW.md` | On second monitor or printed |

---

## Recovery Plays

- **Cowork is slow / stuck** → *"While that runs, let me show you what the
  finished output looks like — here's a saved screenshot from yesterday's
  run."* Have a backup screen recording or screenshots in
  `demo/reference-outputs/`.
- **Cowork refuses an action** → Use it as a teaching moment about safety.
  *"Cowork is asking me to confirm — that's the guardrail working."*
- **Behind on time at minute 35** → Skip Demo 1's follow-up.
- **Behind at minute 45** → Skip Demo 2's follow-up + "Your Move" header.
- **Internet issues** → Cowork can still run locally for read tasks. If
  worst-case, fall back to screen-recorded demo + narrate live.

---

## Pre-Demo Sanity Check (5 min before going live)

- [ ] Cowork is signed in, in fresh session
- [ ] `demo/sample-business-folder/` populated with 3–5 sample files
- [ ] Run the Demo 1 prompt once **earlier today** against a different folder
      to confirm Cowork is responsive
- [ ] Notifications muted
- [ ] Audio + camera test done

See [`PREP_CHECKLIST.md`](PREP_CHECKLIST.md) for the full checklist.
