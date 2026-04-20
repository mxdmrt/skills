# Agent Skills

A small collection of portable agent skills for discovery, research, and product thinking before implementation.

Each skill lives in its own directory and can be installed individually.

## Discovery Flow

These skills are designed to help in the problem space before ideas harden into designs, specs, or code.

1. **challenge-me** — Stress-test a product idea, user story, or UX direction with direct questions about the problem, evidence, tradeoffs, risks, accessibility, and what should be validated first.

```bash
npx skills@latest add mxdmrt/skills/challenge-me
```

2. **who-needs-this** — Challenge briefs, stories, concepts, and screenshots to find the real problem when an artifact looks solution-biased and needs evidence, assumptions, and framing pulled apart before ideation.

```bash
npx skills@latest add mxdmrt/skills/who-needs-this
```

3. **what-to-learn-next** — Turn a reframed problem into a focused discovery and validation plan by identifying the riskiest unknowns, the right evidence sources, and the fastest method to learn what matters.

```bash
npx skills@latest add mxdmrt/skills/what-to-learn-next
```

4. **make-sense-of-it** — Synthesize research notes, transcripts, screenshots, and observations into evidence-backed insights, confidence levels, tensions, and next decisions without over-claiming.

```bash
npx skills@latest add mxdmrt/skills/make-sense-of-it
```

## When To Use Which Skill

- Use **challenge-me** when the idea is still vague and needs pressure-testing before it turns into a solution.
- Use **who-needs-this** when a brief, concept, story, or screenshot already exists and may be framing the wrong problem.
- Use **what-to-learn-next** when the problem is clearer than the evidence and you need a concrete validation plan.
- Use **make-sense-of-it** when you already have raw research inputs and need structured synthesis without false certainty.

## Repository Structure

- `challenge-me/` — Challenge early ideas and UX directions.
- `who-needs-this/` — Reframe solution-biased artifacts around the underlying problem.
- `what-to-learn-next/` — Plan discovery work around the most decision-critical unknowns.
- `make-sense-of-it/` — Synthesize research inputs into evidence-backed insights and next steps.
