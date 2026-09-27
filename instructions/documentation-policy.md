# Documentation Policy

## Directory structure

- `docs/guide/` — user-facing usage guides
- `docs/development/` — developer guides (setup, testing, release, contribution)
- `docs/design/` — how the system currently works
- `docs/adr/` — why important technical decisions were made

## Guidelines

- Write to `docs/design/` when describing the entire architecture.
- Write to `docs/adr/` when documenting a decision with trade-offs.
- Do not write a document for trivial implementation details or reversible choices.
- ADRs record what was decided and why, not the resulting specification.

## Principles

**Minimize reader cognitive load.**

Keep questioning your document against these principles:

1. **Structured** — hierarchy clear, scannable in seconds, nesting ≤4 levels
1. **Cohesive** — one topic per section, related items adjacent, list items share the same abstraction level
1. **Clarity** — reader-appropriate language, terms defined, no ambiguity
1. **Minimal** — every line carries signal, nothing redundant
1. **Completeness** — sufficient for the reader to achieve its intended purpose
1. **Consistency** — matches project conventions and actual behavior
