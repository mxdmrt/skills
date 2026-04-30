# Agent Skills

A small collection of portable agent skills for discovery, research, and product thinking before implementation.

Each skill lives in its own directory under `skills/` and can be installed individually.

## Lean Discovery Flow

These skills are designed to keep discovery lean: investigate first, learn from evidence, then hand off only when the user explicitly chooses to move into design or delivery.

1. **challenge-me** — Stress-test product ideas, user stories, concepts, change requests, briefs, screenshots, and early design thinking. Use it to identify who has the problem, separate facts from guesses, reframe solution-biased requests, and clarify whether the conversation is about a real user need, business request, or speculative idea.

```bash
npx skills@latest add mxdmrt/skills --skill challenge-me
```

2. **learn-from-evidence** — Plan what to learn next and synthesize messy research inputs without over-claiming. Use it for notes, interviews, screenshots, observations, findings, learning plans, evidence gaps, patterns, contradictions, and confidence limits.

```bash
npx skills@latest add mxdmrt/skills --skill learn-from-evidence
```

3. **write-design-brief** — Turn clarified discovery into a design-facing brief with problem framing, user context, evidence, assumptions, constraints, exploration directions, and open questions.

```bash
npx skills@latest add mxdmrt/skills --skill write-design-brief
```

4. **write-delivery-issue** — Turn clarified discovery into a tool-agnostic backlog issue for engineering refinement, compatible with Jira, Linear, GitHub Issues, or any similar tool.

```bash
npx skills@latest add mxdmrt/skills --skill write-delivery-issue
```

## When To Use Which Skill

- Use **challenge-me** when an idea, feature, change request, user story, concept, or artifact needs pressure-testing before it turns into a solution.
- Use **learn-from-evidence** when you need to plan validation or synthesize raw notes, interviews, observations, screenshots, or findings into evidence-backed learning.
- Use **write-design-brief** only when the user explicitly asks to turn clarified discovery into a design-facing handoff.
- Use **write-delivery-issue** only when the user explicitly asks to turn clarified discovery into a refinement-ready backlog issue.

The handoff skills should preserve uncertainty. If the discovery is too weak, they should say what is missing before drafting.

## Lean Discovery Skill Directories

- `challenge-me/` — Challenge early ideas, solution-biased requests, and UX directions.
- `learn-from-evidence/` — Plan discovery work and synthesize evidence-backed insights.
- `write-design-brief/` — Draft design-facing briefs from clarified discovery.
- `write-delivery-issue/` — Draft tool-agnostic delivery issues from clarified discovery.
