# User Research Project Template

Reusable templates for running UX research projects with full traceability from evidence to decision.

## What's in here

- [`templates/primary-research-template.md`](templates/primary-research-template.md) — for qualitative UX research: interviews, usability tests, contextual inquiry, diary studies. Traceability model: **Research → Insight → Recommendation → Solution**.
- [`templates/secondary-research-template.md`](templates/secondary-research-template.md) — for desk research: literature reviews, competitive research, market research, case studies. Traceability model: **Source → Evidence → Pattern → Insight → Recommendation → Validation Gap → Decision**.
- [`AI-CONTEXT.md`](AI-CONTEXT.md) — paste this into any AI chat (ChatGPT, Gemini, Claude, etc.) at the start of a project so it understands the templates and golden rules before helping you fill them out.

## How to start a new project

1. Copy the template that matches your method into `projects/<project-name>.md`:
   ```bash
   cp templates/primary-research-template.md projects/my-new-study.md
   ```
   (Use `secondary-research-template.md` instead for desk research.)
2. If you're using a chat-based AI to help, paste the contents of `AI-CONTEXT.md` into the chat first, then share your project file.
3. Fill in the template section by section, following the Golden Rules at the bottom of each template.

## Choosing a template

| Situation | Template |
|---|---|
| Talking to real users (interviews, usability tests, diary studies) | `primary-research-template.md` |
| Reviewing existing sources (reports, articles, competitor research) | `secondary-research-template.md` |
| Both | Run each phase with its own template; use secondary research findings as input to a primary research plan |
