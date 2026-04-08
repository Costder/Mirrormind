# Roadmap

## Phase 1: Dataset

Define the comparison set used to probe behavior under varied contexts.

- build task categories that expose preferences, refusals, framing, and tradeoffs
- separate style-heavy prompts from decision-heavy prompts
- create enough task diversity to test whether differences generalize

## Phase 2: Tuning

Create the experimental variants under controlled conditions.

- preserve a clear reference path back to the `Base` model
- keep the conditioning objective legible at a high level
- avoid mixing too many experimental variables at once

## Phase 3: Evaluation

Measure where the models differ and where they converge.

- compare outputs across repeated tasks
- inspect consistency across similar scenarios
- distinguish tone shifts from policy shifts
- examine edge cases where behavior appears unstable

## Phase 4: Analysis

Turn raw comparisons into conclusions that matter.

- identify which differences are superficial
- identify which differences alter actual model choices
- map where evaluation methods fail to capture the distinction
- document implications for safety, agent reliability, and benchmark design
