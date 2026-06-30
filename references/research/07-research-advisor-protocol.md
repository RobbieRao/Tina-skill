# 07 - Research Advisor Protocol

Retrieval date: 2026-06-30.

This note summarizes an inspected open research-supervision skill repository as an internal protocol for Tina. It is not a separate persona.

## Source Quality

- Primary source: public repository README files, handbook markdown files, plugin `SKILL.md` files, and repository metadata.
- Local inspection commit: `a1be308f5415052b403cffa298bc9c8d3d709e3a`, dated 2026-06-26.
- Public repository metadata on 2026-06-30: created 2026-04-19, last pushed 2026-06-26, default branch `main`, 3403 stars, 251 forks.
- Reliability: high for the repository's own intent and workflow design; not a factual source for ergonomic design itself.

## What the Protocol Adds to Tina

The protocol frames graduate research support as a last-mile supervision problem. Students may know general advice but still need timely judgment on idea quality, paper logic, figure quality, and submission readiness.

It contributes seven internal modules:

- Idea evaluation.
- AI-assisted research workflow.
- Introduction drafting.
- Technical-paper skeleton.
- Benchmark and evaluation-paper skeleton.
- Pre-submission review.
- Scientific figure design.

## Transferable Mental Models

### Research is a last-mile supervision problem

The hard part is not only knowing broad advice. It is applying judgment to the current idea, draft, figure, or experiment at the moment when a small decision changes the outcome.

### Idea quality is multi-axis

For Tina's domain, idea axes become:

- Higher: better fit, comfort, usability, prediction accuracy, or safety margin.
- Faster: faster measurement, scan processing, CAD generation, prototype iteration, or evaluation.
- Stronger: better cross-population robustness, noise tolerance, motion tolerance, or real-world generalization.
- Cheaper: lower scan cost, fewer labels, less expert annotation, reduced prototype cost, or lower deployment complexity.
- Broader: transfer across headwear, eyewear, earwear, neck/back products, XR, medical devices, vehicles, or digital interfaces.

### A paper is a logic chain

The chain is:

1. Scenario and background.
2. Existing work and limitations.
3. Problem definition or goal.
4. Key challenges.
5. Method overview.
6. Contributions.

### Figures are scientific arguments

Three figures carry most of the review load:

- Motivated example: what problem exists and why existing methods fail.
- Solution overview: how the method or system works.
- Experimental results: what evidence supports the claim.

### AI is an accelerator, not the research owner

AI may help with literature organization, code, debugging, figure drafts, and language polish. The researcher owns research question, experimental design, technical route, core claims, data validity, and final writing.

## Integration Rules

Use this protocol as Tina's research-supervision layer.

When the user asks about research direction, papers, experiments, figures, writing, or submission:

1. Run Tina's domain gate first: target population, body or perception variables, product contact surface, measurement, model, prototype, validation.
2. Run the advisor gate second: idea axis, lifecycle, capability fit, logic chain, figure plan, pre-submission risks.
3. Return a concrete next action.
4. Keep academic integrity constraints visible when AI assistance is involved.

