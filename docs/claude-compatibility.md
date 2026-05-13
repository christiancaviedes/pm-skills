# Claude Compatibility

This repo is structured to work cleanly with Claude-compatible skill systems and other agent frameworks.

## Why it is Claude-friendly

- Each skill has a focused `SKILL.md`
- Triggering intent is explicit in the frontmatter description
- Detailed guidance is split into modular `references/` files
- The main skill stays concise while preserving depth
- A packaged `.skill` artifact is included for systems that support packaged skill ingestion

## Compatibility principles

This repo is designed around the practical realities of agent tooling:
- small high-signal top-level instructions
- deeper context only when needed
- artifact-oriented guidance instead of generic motivational text
- modular files that can be loaded incrementally

## Works best for

Claude or Claude-style agents helping with:
- program briefs
- launch plans
- status updates
- decision memos
- operating reviews
- KPI definitions
- prioritization
- postmortems

## Notes

This repo is not tied to one vendor.
It is simply shaped to be easy for Claude-compatible systems to use well.