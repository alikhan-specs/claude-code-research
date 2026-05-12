---
type: project
created: 2026-05-04
updated: 2026-05-12
status: reference
side: personal
phase: reference-clone
tags: [personal, claude-code, research, fork, reference]
linked: [[claude-code-advance]], [[jarvis]]
---

# Claude Code Research — Context

## 1. What it is
Sister research clone to [[claude-code-advance]]. Where `-advance` mirrors the **npm-exposed Anthropic source** (`nirholas/claude-code`), this one tracks **`instructkr/claude-code`** — an alternative Claude Code implementation maintained by an independent contributor. Comparing the two surfaces the patterns common to all Claude Code-class tools versus the implementation choices specific to Anthropic.

## 2. Why it exists
Two-source comparison is sharper than single-source study. Reading two implementations of the same problem domain (one from Anthropic, one from `instructkr`) reveals which design decisions are inherent to the architecture versus which were chosen by one team. Ali uses both as reference when designing Jarvis and the broader personal agentic stack.

## 3. Where it lives
| | |
|---|---|
| **Vault** | `30-projects/claude-code-research/` (submodule) |
| **Remote** | `github.com/alikhan-specs/claude-code-research` |
| **Upstream** | `github.com/instructkr/claude-code` |
| **Side** | Personal — public fork |

## 4. Tech stack (of the source under study)
Similar shape to [[claude-code-advance]] — TypeScript, Claude Code-class runtime, alternative implementation patterns. Details to be filled when comparative reading produces them.

## 5. Current state (as of 2026-05-12)
**Reference-only.** Last commit `13294d6 chore: add project context file` (2026-05-05) — submodule pointer added, no active modifications. The repo serves as a read-only reference; active research lives in [[claude-code-advance]].

## 6. Recent decisions
- **2026-05-04** — created as parallel to [[claude-code-advance]] specifically to enable comparative reading.
- **Public fork of public repo** — no IP concerns; lives on personal GitHub.
- **No active modifications** — keeping the fork as a pristine reference. If Ali wants to experiment, that goes in [[claude-code-advance]] or a fresh branch.

## 7. Open threads / blockers
- **Comparative findings not captured** — Ali has not yet produced a side-by-side architectural comparison of the two snapshots. Worth a focused session.
- **Upstream activity unclear** — `instructkr/claude-code` evolution rate not tracked; may or may not stay current.

## 8. What "done" looks like
Reference repos don't have a "done." Useful milestone: a vault `consolidated/claude-code-implementations-compared.md` note synthesising findings across `-advance` and `-research`.

## 9. People involved
- Ali — sole reader
- No collaborators

## 10. Cross-references
- Related vault: [[claude-code-advance]] (primary research clone), [[jarvis]] (consumer of architectural insights)
- Strategic narrative: same as `-advance` — research-grounded agentic tool design

## 11. How to work on this with the clone
Pure reference. The clone reads code here only for comparison against `-advance`. No active development. If a comparison study starts, the output note belongs in `20-memory/consolidated/`, not inside this repo.
