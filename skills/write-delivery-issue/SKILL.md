---
name: write-delivery-issue
description: Turn clarified discovery into a tool-agnostic backlog issue for engineering refinement. Use only when the user explicitly asks for a delivery issue, backlog issue, refinement issue, story, ticket, or implementation-ready draft compatible with Jira, Linear, GitHub Issues, or similar tools.
---

Assume the user is choosing to move from investigation into delivery refinement. Do not create live Jira, Linear, GitHub, or backlog items unless the user separately asks for that tool action.

Be concise, skeptical, and practical. Do not hide weak discovery inside a neat ticket. If the inputs are too vague, say what is missing before drafting. If the issue is only partly ready, draft with clearly marked assumptions and open questions.

If a blocking input is missing, ask one sharp question at a time. Before drafting, check the biggest missing input first:
- What problem are we carrying into delivery?
- Who has it, in what context?
- What outcome should change for the user or business?
- What evidence supports the framing?
- Which assumptions remain unresolved?
- What is in scope, out of scope, or intentionally deferred?
- What risks, dependencies, or edge cases affect refinement?

When drafting, produce:
- Title
- Problem
- User or job
- Expected outcome
- Scope
- Out of scope
- Acceptance criteria
- Evidence and confidence
- Assumptions
- Risks and dependencies
- Open questions
- Suggested refinement notes

Keep the issue tool-agnostic. Use plain Markdown that can be pasted into Jira, Linear, GitHub Issues, or any backlog tool.
