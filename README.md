# AI Research Partner Guideline

Your blank-page problem, solved. This is a set of battle-tested templates and prompts for running UX research projects alongside an AI assistant — so you spend your time on insight, not on figuring out where to start.

No setup, no cloning, no code. Copy some text, paste it into your favorite AI chat, and go.

> **New here?** This repo has a few files, but you only need two at a time to get going: **one template** (what you're filling in) + [`AI-CONTEXT.md`](AI-CONTEXT.md) (how the AI should help). Everything else — the examples, [`AI-ROLE-PROMPT.md`](AI-ROLE-PROMPT.md) — is there for when you need it, not before. Start with the steps below.

## How to start a new project

1. Pick the template that fits your research (see below), then copy its contents or download the `.md` file — whatever your AI tool likes.
2. Open a chat with your AI assistant of choice (ChatGPT, Gemini, Claude, take your pick).
3. Share [`AI-CONTEXT.md`](AI-CONTEXT.md) first, then the template, then tell it what you're researching.
4. Work through the template section by section, filling in real notes, sources, and evidence — no filling in the blanks with vibes.
5. Ready to turn evidence into recommendations? Bring in [`AI-ROLE-PROMPT.md`](AI-ROLE-PROMPT.md) — it's where the AI stops taking notes and starts thinking like a research lead.

## Example prompt

Not sure what to type after sharing the files? Try this:

> I'm starting a [primary/secondary] research project about [topic/product]. Please read `AI-CONTEXT.md` and follow its ground rules, then help me fill out `primary-research-template.md` (or `secondary-research-template.md`) section by section — starting with 00/01 Project Setup.

Still not sure what "good" looks like? See a worked example: [`example-primary-research.md`](examples/example-primary-research.md) or [`example-secondary-research.md`](examples/example-secondary-research.md).

## Choosing a template

| Situation | Template |
|---|---|
| Talking to real users (interviews, usability tests, diary studies) | [`primary-research-template.md`](templates/primary-research-template.md) |
| Reviewing existing sources (reports, articles, competitor research) | [`secondary-research-template.md`](templates/secondary-research-template.md) |
| Both | Run each phase with its own template; feed secondary research findings into your primary research plan |

## What's in here

- [`templates/primary-research-template.md`](templates/primary-research-template.md) — for research where you talk to real people: interviews, usability tests, contextual inquiry, diary studies. Traceability model: **Research → Insight → Recommendation → Solution**.
- [`templates/secondary-research-template.md`](templates/secondary-research-template.md) — for research where you talk to the internet instead: literature reviews, competitive research, market research, case studies. Traceability model: **Source → Evidence → Pattern → Insight → Recommendation → Validation Gap → Decision**.
- [`AI-CONTEXT.md`](AI-CONTEXT.md) — the ground rules that keep your AI honest: evidence stays evidence, opinions stay opinions, and nothing gets invented.
- [`AI-ROLE-PROMPT.md`](AI-ROLE-PROMPT.md) — a sharper "senior research partner" persona for when it's time to turn evidence into recommendations stakeholders will actually act on.

## Quick tip for advanced users

Using an AI coding tool (Claude Code, Cursor, etc.) instead of a plain chat window? Clone this repo locally and it can read the files directly — no copy-pasting needed:

```bash
git clone https://github.com/thanabat/ai-research-partner-guideline.git
```

Point your tool at the folder, then just ask it to follow `AI-CONTEXT.md` (and `AI-ROLE-PROMPT.md` once you're synthesizing) using whichever template fits your project.
