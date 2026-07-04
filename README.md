# Getting Real Skill for AI Agents 📘

> Unofficial agent skill based on Basecamp's *Getting Real* — tuned to route an agent to the right product-building chapter fast.

This repo packages **one flagship skill**: `getting-real`.

It is designed for agents that need help building a product end-to-end without drifting into vague startup advice. Instead of turning the book into a fuzzy summary, this skill is organized around the book's actual parts so an agent can load the right context for:

- product scope
- priorities
- feature selection
- shipping process
- interface design
- launch and promotion
- support
- post-launch discipline

Works with OpenClaw, Claude Code, Codex, Cursor, Hermes, and other agents that support Agent Skills style repositories.

## What *Getting Real* Is

[*Getting Real*](https://basecamp.com/gettingreal) is a product-building book from **Basecamp / 37signals**. Its core philosophy is brutally simple:

- build less
- solve the real problem first
- keep teams small
- fix time and budget, then flex scope
- ship real software instead of hiding in specs, meetings, and hypothetical planning

It is one of the cleanest books on building software products without drowning in process theater.

## Why This Helps An Agent Build A Full Product

Most agents are decent at producing output and terrible at **product judgment**. They can generate screens, code, docs, and plans all day, but they often:

- overbuild
- accept bad feature requests too easily
- polish details before the product thesis is clear
- confuse more work with better work

This skill acts like a product editor.

It helps an agent:

- cut scope before implementation balloons
- route feature debates to the right decision frame
- think from interface and customer experience first
- avoid overplanning and get to working software faster
- stay lean after launch instead of becoming a feature landfill

In plain English: this is the kind of skill that helps an agent build **a sharper product**, not just **more product**.

## What's In This Repo

- `skills/getting-real/` — standard skill layout
- `clawhub/getting-real/` — OpenClaw-friendly mirrored layout
- `skills/getting-real/chapter-map.md` — all 91 chapters grouped by official book sections
- `skills/getting-real/chapters/` — 16 part files for fast routing
- `skills/getting-real/patterns.md` — reusable product decision patterns
- `skills/getting-real/glossary.md` — key terms from the book
- `skills/getting-real/cheatsheet.md` — quick decision rules

This repo intentionally contains **one skill only**. No aliases. No pack of near-duplicates. `getting-real` is the star.

## Install

**Claude Code / Codex / Cursor / Cline / compatible tools**

```bash
npx skills add therohitdas/getting-real-skill --skill getting-real
```

**Hermes Agent**

```bash
hermes skills install skills-sh/therohitdas/getting-real-skill/skills/getting-real
```

**Manual**

```bash
git clone https://github.com/therohitdas/getting-real-skill.git
cp -r getting-real-skill/skills/getting-real ~/.claude/skills/
```

**OpenClaw / general agent prompt**

Paste this into your agent:

```text
Install the getting-real skill from this GitHub repo:
https://github.com/therohitdas/getting-real-skill

I want you to use it whenever we're building a software product, choosing features, shaping UX, planning launch, or trying to stay lean.
Set it up for me.
```

## How To Use

Just install it and ask naturally:

- `Use getting-real to evaluate this SaaS idea`
- `Use getting-real to cut scope for this MVP`
- `Use getting-real to review this feature roadmap`
- `Use getting-real to critique this onboarding flow`
- `Use getting-real to plan a lean launch`

The skill's top-level `SKILL.md` is routing-first. It classifies the problem, then sends the agent to the most relevant book part before answering.

## Official Book Structure

The live Basecamp page organizes the book into sections such as:

- Introduction
- The Starting Line
- Stay Lean
- Priorities
- Feature Selection
- Process
- Interface Design
- Pricing and Signup
- Promotion
- Support
- Post-Launch

Source: https://basecamp.com/gettingreal

## Unofficial + Provenance

This is an **unofficial** derivative skill. It is **not affiliated with Basecamp or 37signals**.

The initial conversion was generated using **book-to-skill**:

- https://github.com/virgiliojr94/book-to-skill

Then it was manually reworked to make the main skill much better at:

- routing by product problem
- redirecting attention to the right chapter cluster
- giving agents a stronger product-building frame

## Repository Goals

- Keep the repo lightweight
- Keep the skill opinionated
- Keep the chapter routing obvious
- Help agents build better products with less crap

## License

MIT for the repo contents in this repository. The underlying book and brand remain the property of their respective owners.
