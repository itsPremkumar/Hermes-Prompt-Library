# Hermes-Prompt-Library

Versioned prompt library for the autonomous AI company (`Hermes-Full-Autonomous-Company`).

## Rules
- Every prompt is versioned (`major.minor`).
- Each prompt carries: purpose, input format, output format, usage instructions, tested models, source URL, tested use case, actual results, limitations.
- Outdated versions go to `archive/` — never deleted.
- Prefer **officially published** prompt guidance over unverified "leaked system prompt" content.

## Current prompts
| File | Version | Type | Notes |
|---|---|---|---|
| `executive-master-operating-prompt-v2.0.md` | 2.0 | Executive / Operating | The master constitution. Also `CONSTITUTION.md` in the main company repo. Adopted v1.0 (Paperclip+OpenClaw reality-matched) and fixed fictional-stack + leaked-prompt assumptions. |

## Archive (superseded)
- `archive/v0.1-constitution-draft.txt` — first constitution draft (n8n/Mem0/CrewAI assumptions)
- `archive/v0.2-ultimate-draft.txt` — "ultimate" draft (same stack assumptions)
- `archive/v0.3-full-draft.txt` — full prompt draft
- `archive/v0.4-md-draft.md` — markdown version of the full draft
- `archive/v0.5-prompt-py.txt` — `prompt.py` (the user's original chat + an improved version)
- `archive/v1.0-prior-master.md` — prior master operating prompt (good structure, but pre-consolidation)

## Improvement loop
1. Discover a new technique → evaluate vs current best.
2. If superior → replace, move old to `archive/` with a note.
3. Cite the source. Commit + push.
