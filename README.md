# Ship a Product for AI Agents 📘

> AI product planning skill for agents that need help scoping an MVP, prioritizing features, shaping UX, planning launch, and shipping a lean software product.

![Single Skill Repo](https://img.shields.io/badge/repo-single_skill-0f172a)
![Agent Skills](https://img.shields.io/badge/format-Agent_Skills-2563eb)
![Unofficial](https://img.shields.io/badge/status-unofficial-f59e0b)

**Ship a Product** is an unofficial AI agent skill inspired by Basecamp's [*Getting Real*](https://basecamp.com/gettingreal). It helps an agent act more like a sharp startup founder, product lead, or lean product team member when building software.

If you're looking for an **AI product manager skill**, **MVP planning skill**, **feature prioritization skill**, or **startup planning skill**, this is the closest fit.

This repo packages **one flagship skill**: `ship-a-product`.

Use it when you want an agent to help with:

- MVP planning
- product scope
- feature prioritization
- product strategy
- UX and interface decisions
- launch planning
- startup product decisions
- post-launch product improvement

Instead of turning the book into a fuzzy summary, this skill routes the agent to the right product-building context fast: scope, priorities, feature selection, process, interface design, pricing, promotion, support, and post-launch decisions.

Works with 🦞 OpenClaw, <img src="assets/hermes.png" alt="" height="14"> Hermes Agent, Claude Code, Codex, Cursor, and other tools that support the [Agent Skills](https://skills.sh) format.

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

This skill acts like a product editor for an AI agent.

It helps an agent:

- cut scope before implementation balloons
- route feature debates to the right decision frame
- think from interface and customer experience first
- avoid overplanning and get to working software faster
- stay lean after launch instead of becoming a feature landfill

In plain English: this is the kind of skill that helps an agent build **a sharper product**, not just **more product**.

## What's In This Repo

- `skills/ship-a-product/` — standard skill layout
- `skills/ship-a-product/chapter-map.md` — all 91 chapters grouped by official book sections
- `skills/ship-a-product/chapters/` — 16 part files for fast routing
- `skills/ship-a-product/patterns.md` — reusable product decision patterns
- `skills/ship-a-product/glossary.md` — key terms from the book
- `skills/ship-a-product/cheatsheet.md` — quick decision rules

This repo intentionally contains **one skill only**. No aliases. No pack of near-duplicates. `ship-a-product` is the star.

## Install

Most users should install it with one command:

```bash
npx skills add therohitdas/ship-a-product-skill
```

That works because this repo contains **one skill only**.

**Works with:**
- 🦞 OpenClaw
- <img src="assets/hermes.png" alt="" height="14"> Hermes Agent
- Claude Code
- Codex
- Cursor
- Cline
- Any Agent Skills-compatible tool

**Manual**

```bash
git clone https://github.com/therohitdas/ship-a-product-skill.git
cp -r ship-a-product-skill/skills/ship-a-product ~/.claude/skills/
```

**General agent prompt**

Paste this into your agent:

```text
Install the ship-a-product skill from this GitHub repo:
https://github.com/therohitdas/ship-a-product-skill

I want you to use it whenever we're building a software product, scoping an MVP, prioritizing features, shaping UX, planning launch, or trying to stay lean.
Set it up for me.
```

## How To Use

Just install it and ask naturally:

- `Use ship-a-product to evaluate this SaaS idea`
- `Use ship-a-product to cut scope for this MVP`
- `Use ship-a-product to prioritize features for this product`
- `Use ship-a-product to critique this onboarding flow`
- `Use ship-a-product to plan a lean launch`

The skill's top-level `SKILL.md` is routing-first. It classifies the problem, then sends the agent to the most relevant book part before answering.

## What Decisions This Skill Helps With

`ship-a-product` is strongest when an agent needs to make or support decisions about:

- what problem the product should solve
- what the MVP should include or exclude
- which features to cut, defer, or simplify
- how to prioritize scope under time and budget constraints
- how opinionated the product should be
- which users the product is really for
- how the core interface and onboarding should work
- whether a problem needs software or a human workaround
- how to launch, promote, support, and refine the product after release

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
