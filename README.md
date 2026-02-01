# UX Invariants — Sample Variant

The UX Invariants Sample distribution is a limited subset of UX Invariants intended
for evaluation and quick trial in AI-assisted workflows.

**[Purchase the complete production-ready set of UX Invariants](https://ux-invariants.cubicle6.com/purchase).**

## What this is

- A small, representative slice of the invariant set
- Structured Markdown specs meant for LLM conditioning and human review
- Framework-agnostic and tooling-agnostic

## What this is not

- A design system or component library

## Contents

- `AGENTS.md` — paste into `AGENTS.md` to condition agents
- `ux-invariants/` — invariant specs in Markdown
- `standalone-prompts` - invariants formatted for standalone prompting

## How to use

1. Copy the contents of `AGENTS.md` into your project `AGENTS.md`.
2. Copy the entire `./ux-invariants/` directory and paste it alongside your project `AGENTS.md`.
3. Run your AI workflow with the invariants in context.
4. During review, reference invariant IDs when flagging violations.

## Notes

This variant prioritizes clarity over completeness. For production use, the pro
variant is intended to include the full invariant set and supporting context.
