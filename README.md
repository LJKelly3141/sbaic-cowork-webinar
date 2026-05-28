# Beyond the Chat Box: AI at Your Desk — Webinar Materials

Reproducible prep + delivery materials for the introductory Claude Cowork webinar.

**Presenter:** Dr. Logan Kelly · Small Business AI Center
**Hosted by:** TBD
**Date:** TBD 2026
**Target runtime:** ~60 minutes (15 min concept · 25 min demo · 5 min takeaways · 10 min Q&A · 5 min open/close)
**Repository:** [Beyond the Chat Box Webinar](https://github.com/LJKelly3141/sbaic-cowork-webinar)

## What This Webinar Teaches

Audience leaves knowing:

1. **What Cowork is** and how it differs from Chat (folder context, real
   files, skills, scheduled tasks, local VM)
2. **The three steps to start** — install Claude Desktop, run `/setup-cowork`,
   pick a working folder
3. **Two concrete things they can do** — point Cowork at a folder, save
   a prompt as a reusable skill

Built from the official Anthropic onboarding framing
([Get started in Claude Cowork in three steps](https://claude.com/resources/tutorials/get-started-in-claude-cowork-in-three-steps)).

## Folder Structure

```
Webinar_BeyondChat/
├── README.md              ← You are here
├── CLAUDE.md              ← Folder guidance for AI/Claude sessions
├── prep/
│   ├── RUN_OF_SHOW.md     ← Timed slide-by-slide facilitator guide
│   └── PREP_CHECKLIST.md  ← Pre-webinar tech & content checklist
├── slides/                ← Slide deck (Quarto RevealJS)
│   ├── webinar.qmd
│   └── custom.scss
├── handout/               ← Audience-facing notes handout
│   └── handout.qmd
├── demo/
│   ├── prompts.md         ← Live demo prompts (copy-paste)
│   ├── demo-plan.txt      ← Plain-text demo plan
│   ├── sample-business-folder/  ← Sandbox Cowork points at (populate before delivery)
│   ├── reference-outputs/ ← Screenshots/recordings for backup
│   └── optional-extensions/
└── briefings/             ← Background reading on Cowork features
```

## Quick Start — Deliver This Webinar

1. Work through `prep/PREP_CHECKLIST.md` the day of.
2. **Populate `demo/sample-business-folder/`** with 3–5 sanitized small-business
   files (invoice, email, memo, spreadsheet). This folder doesn't ship in the
   template — you create it for your delivery.
3. Have `prep/RUN_OF_SHOW.md` open on a second screen.
4. Open `slides/webinar.html` for the presentation.
5. Keep Claude Desktop (Cowork mode) and `demo/prompts.md` open.

## Rendering

Requires [Quarto](https://quarto.org/docs/get-started/) and TinyTeX.

```bash
cd slides && quarto render webinar.qmd && open webinar.html
cd handout && quarto render handout.qmd && open handout.pdf
```

## References

- [Get started with Claude Cowork](https://support.claude.com/en/articles/13345190-get-started-with-claude-cowork)
- [Get started in Claude Cowork in three steps](https://claude.com/resources/tutorials/get-started-in-claude-cowork-in-three-steps)
- [Using Claude Cowork for your small business](https://claude.com/resources/tutorials/using-claude-for-your-small-business)
- [Customize Claude Cowork](https://claude.com/resources/tutorials/customize-claude-cowork)
- [Install Claude Desktop](https://support.claude.com/en/articles/10065433-install-claude-desktop)

## License

Materials provided for educational use by the Small Business AI Center.
