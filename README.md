# Mirrormind

Research question: "Does worldview fine-tuning change behavior or just style?"

`Mirrormind` is a documentation-first research project focused on behavioral differences between closely related LLM variants. The central goal is to test whether targeted worldview conditioning produces genuine changes in choices, refusals, priorities, and consistency, or whether it mainly changes tone, framing, and surface presentation.

## Model Framing

- `Base`: the reference model used as the neutral comparison point.
- `Saint`: a variant tuned toward strongly prosocial, cautious, and norm-reinforcing behavior.
- `Devil`: a variant tuned to stress-test contrary, adversarial, or values-shifted behavior under controlled research conditions.

These labels are shorthand for experimental conditions, not product names or deployment targets.

## Why This Matters

The question matters for several reasons:

- `AI safety`: if style and behavior diverge, alignment claims based on tone may be misleading.
- `agent design`: multi-agent systems need reliable expectations about how model variants actually behave under pressure.
- `consistency`: if a model sounds different but makes the same decisions, that implies a different kind of controllability than if its behavior truly changes.
- `evaluation`: current benchmarks often blur rhetorical style, preference shift, and decision policy.

## Scope

This repository documents the research frame, not the full experimental stack. Detailed prompts, training recipes, and pipeline internals are intentionally abstracted.

## Repository Map

- `STATUS.md`: current project state
- `docs/overview.md`: plain-language project explanation
- `docs/roadmap.md`: staged research plan
- `docs/ethics.md`: misuse risks and research boundaries
