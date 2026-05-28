# CLAUDE.md — Beyond the Chat Box Webinar

Guidance for AI/Claude sessions working in this folder.

## Webinar Overview

- **Title:** Beyond the Chat Box: AI at Your Desk
- **Topic:** Introduction to Claude Cowork for small business owners
- **Length:** ~60 minutes (SBAIC standard)
- **Format:** Live slides + two demos in real Claude Cowork sessions

This webinar is built from the `_Webinar_TEMPLATE/` template (see
`../_Webinar_TEMPLATE/CLAUDE.md` for template-level conventions).

## Teaching Spine

The webinar uses Anthropic's official three-step onboarding as the spine:

1. **Install** Claude Desktop
2. **Run** `/setup-cowork`
3. **Pick a folder** and start working

These three steps map to slides 6, 7, and 8 in `slides/webinar.qmd`.

## Demo Pattern

Unlike the April 2026 CRP webinar (which used the C.O.R.E. prompt framework
inside Chat), **this webinar's demos run inside actual Cowork sessions**:

- **Demo 1 — What's In My Folder?** Point Cowork at `demo/sample-business-folder/`
  and ask it to read everything and produce a punch list. Shows folder context.
- **Demo 2 — Saving Work as a Skill.** Take the Demo 1 prompt and save it as
  a named skill + scheduled task. Shows the repetition cure.

Demo prompts live in `demo/prompts.md` and `demo/demo-plan.txt`.

## Sample Folder

`demo/sample-business-folder/` doesn't ship populated with this template —
the presenter must add 3–5 sanitized small-business files before going live.
See `prep/PREP_CHECKLIST.md` for the file list.

## Cowork Dependencies for the Demo

The presenter needs:

- Claude Desktop installed (macOS Apple Silicon or Windows Pro+)
- A paid Claude plan (Pro/Max/Team/Enterprise)
- Cowork mode active
- At least one skill or plugin installed (so Demo 2 Option B has a fallback)

## When Editing These Materials

- **Slides:** `slides/webinar.qmd`. Re-render: `cd slides && quarto render webinar.qmd`.
- **Handout:** `handout/handout.qmd`. Re-render: `cd handout && quarto render handout.qmd`.
- **Demo prompts:** `demo/prompts.md` and `demo/demo-plan.txt`. Keep in sync.
- **Run-of-show:** `prep/RUN_OF_SHOW.md` — update after each delivery with
  timing observations and Q&A themes.

## After Each Delivery

Save artifacts back to this folder for next time:

- Screen recording of a successful Demo 1 → `demo/reference-outputs/`
- Screenshots of save-as-skill flow → `demo/reference-outputs/`
- Common Q&A themes → consider feeding into the next iteration's slides

## Related

- `../_Webinar_TEMPLATE/` — the source template for this webinar
- `../Webinar/` — April 2026 CRP webinar (Chat-mode example using C.O.R.E.)
- `../CLAUDE.md` — Presentations folder guidance
- `../../CLAUDE.md` — AI Clinic root guidance
