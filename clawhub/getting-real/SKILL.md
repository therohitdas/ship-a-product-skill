---
name: getting-real
description: "Unofficial skill based on \"Getting Real\" by Basecamp. Use when an agent needs product-building guidance on scope, priorities, feature selection, process, interface design, launch, support, or keeping a product lean."
version: "1.0.0"
user-invocable: true
compatibility: Works with agents that support Agent Skills style repositories. Unofficial conversion generated with book-to-skill and then hand-tuned for routing.
metadata: {"openclaw":{"emoji":"📘"},"hermes":{"tags":["product","startup","ux","scope","shipping","founder"],"category":"productivity"}}
allowed-tools:
  - Read
  - Grep
argument-hint: [problem, topic, chapter number, or part name]
---

# Getting Real

**Author**: Basecamp
**Subtitle**: The smarter, faster, easier way to build a successful web application
**Status**: Unofficial derivative skill, not affiliated with Basecamp
**Structure**: 16 part files + full chapter map
**Generated**: 2026-07-04

## Mission

This skill is not a generic summary of the book. Its main job is to route attention to the right
part of the book fast.

Use this skill when the agent is dealing with:

- product scope creep
- unclear priorities
- feature bloat
- shipping too slowly
- messy interface decisions
- code/process/org drift
- launch, promotion, pricing, support, or post-launch discipline

## Routing First

Before answering, classify the user's problem into one of these buckets:

1. **Framing the product** -> `chapters/p02-starting-line.md`
2. **Staying small and adaptable** -> `chapters/p03-stay-lean.md`
3. **Choosing what matters now** -> `chapters/p04-priorities.md`
4. **Choosing or rejecting features** -> `chapters/p05-feature-selection.md`
5. **How to execute and ship** -> `chapters/p06-process.md`
6. **Team structure and communication** -> `chapters/p07-organization.md`
7. **Hiring and staffing** -> `chapters/p08-staffing.md`
8. **Interface and UX decisions** -> `chapters/p09-interface-design.md`
9. **Codebase and engineering tradeoffs** -> `chapters/p10-code.md`
10. **Specs, copy, and product language** -> `chapters/p11-words.md`
11. **Pricing, signup, and conversion** -> `chapters/p12-pricing-signup.md`
12. **Launch and promotion** -> `chapters/p13-promotion.md`
13. **Support and customer handling** -> `chapters/p14-support.md`
14. **Post-launch cleanup and growth** -> `chapters/p15-post-launch.md`

If the problem is about the book itself, author intent, or the general philosophy, start with:

- `chapters/p01-introduction.md`
- `chapters/p16-conclusion.md`

## Fast Triage Heuristics

Use these heuristics before giving advice:

- If the team wants "just one more feature," load `p05-feature-selection.md`.
- If the roadmap is bloated, load `p02-starting-line.md` and `p03-stay-lean.md`.
- If the product feels vague, load `p04-priorities.md`.
- If execution is stuck in planning, load `p06-process.md`.
- If UX is being debated abstractly, load `p09-interface-design.md`.
- If engineers are overbuilding, load `p10-code.md`.
- If docs/specs are expanding faster than product truth, load `p11-words.md`.
- If acquisition/conversion is the question, load `p12-pricing-signup.md` or `p13-promotion.md`.
- If churn, complaints, or trust issues show up after launch, load `p14-support.md` and `p15-post-launch.md`.

## How To Answer

1. Name the problem in plain English.
2. Route to the narrowest relevant part file.
3. Pull the chapter-level ideas from that file.
4. Give a concrete recommendation in the book's voice: smaller, sharper, more opinionated, more real.
5. If needed, mention the exact chapter titles that back the recommendation.

Do not flatten the book into soft, generic startup advice. The book is sharp on purpose.

## Core Operating Principles

- Build less than you think you need.
- Treat constraints as a design advantage.
- Fix time and budget; flex scope.
- Solve the core problem before polishing edges.
- Say no by default; force features to justify themselves.
- Replace documents and debate with working software.
- Design from the interface inward.
- Keep teams small, communication direct, and meetings rare.
- Write clearly because product words are product behavior.
- Launch earlier than is emotionally comfortable, then iterate in public.

## Part Index

- [p01 Introduction](chapters/p01-introduction.md) - What Getting Real is, when it applies, and how to use the philosophy.
- [p02 The Starting Line](chapters/p02-starting-line.md) - Scope, funding, constraints, conviction, and picking a meaningful problem.
- [p03 Stay Lean](chapters/p03-stay-lean.md) - Smallness, adaptability, and keeping the cost of change low.
- [p04 Priorities](chapters/p04-priorities.md) - Big ideas, sequencing, customer selection, scaling later, and building opinionated software.
- [p05 Feature Selection](chapters/p05-feature-selection.md) - How to reject, trim, and simplify features before they rot the product.
- [p06 Process](chapters/p06-process.md) - Move from idea to running software quickly and iteratively.
- [p07 The Organization](chapters/p07-organization.md) - Team shape, solitude, and avoiding meetings.
- [p08 Staffing](chapters/p08-staffing.md) - Hiring late, hiring carefully, and preferring rounded people.
- [p09 Interface Design](chapters/p09-interface-design.md) - Start with the UI, design around the epicenter, and defend clarity.
- [p10 Code](chapters/p10-code.md) - Less software, happier developers, clearer code, and controlled debt.
- [p11 Words](chapters/p11-words.md) - Replace dead specs with stories, real words, and a human product voice.
- [p12 Pricing and Signup](chapters/p12-pricing-signup.md) - Sampling, low-friction signup, and honest conversion mechanics.
- [p13 Promotion](chapters/p13-promotion.md) - Launch energy, promo pages, education, and lightweight growth loops.
- [p14 Support](chapters/p14-support.md) - Fast, humane support without hiding from pain.
- [p15 Post-Launch](chapters/p15-post-launch.md) - Tuneups, bug triage, restraint, and sustainable improvement.
- [p16 Conclusion](chapters/p16-conclusion.md) - Final push to stop planning forever and start moving.

## Topic Index

- **big idea / product thesis** -> `p04-priorities.md`
- **build less / scope discipline** -> `p02-starting-line.md`, `p05-feature-selection.md`
- **constraints** -> `p03-stay-lean.md`
- **copywriting / interface words** -> `p09-interface-design.md`, `p11-words.md`
- **customers / who to build for** -> `p04-priorities.md`
- **feature requests** -> `p05-feature-selection.md`
- **funding / bootstrap** -> `p02-starting-line.md`
- **hiring** -> `p08-staffing.md`
- **interface / ux** -> `p09-interface-design.md`
- **launch** -> `p13-promotion.md`
- **meetings** -> `p07-organization.md`
- **pricing / signup** -> `p12-pricing-signup.md`
- **process / shipping cadence** -> `p06-process.md`
- **scaling** -> `p04-priorities.md`
- **support** -> `p14-support.md`
- **technical debt / code** -> `p10-code.md`
- **testing in the wild** -> `p06-process.md`
- **writing / specs / docs** -> `p11-words.md`

## Supporting Files

- [chapter-map.md](chapter-map.md) - full list of all 91 chapters under their parts
- [glossary.md](glossary.md) - key terms and phrases from the book
- [patterns.md](patterns.md) - reusable tactics and decision patterns
- [cheatsheet.md](cheatsheet.md) - one-page decision rules

## Scope And Limits

This skill captures the book's product philosophy, not every modern technical concern.
It is strongest for product focus, scope control, UX clarity, shipping rhythm, and sane small-team execution.
