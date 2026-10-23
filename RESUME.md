# RESUME (2026-10-23)

## Current state
- Fork `c10vis-poem/NvAEx-terrestrial-brain` (of TerrestrialOrigin's terrestrial-brain), default/PR base `main`, protected with required status checks, workflow `ci.yml`. Open PRs: none. Local `NovA-terrestrial-brain` main was one commit behind and was fast-forwarded.
- **On 2026-10-23 the operator dropped Terrestrial Brain (and OmniRoute, mem0, OpenWiki) from the stack.** This repo is no longer part of the active stack; its docs below still describe it as live. Nothing was deleted or rewritten.
- The previous RESUME (2026-09-18 "round trip proven": phone -> TB -> OpenRouter -> Postgres -> vault, VM-hosted) is replaced by this one; it remains in git history.

## Changed this week (2026-10-18..2026-10-23)
- PR #7 `chore/drop-stale-vm-ip` (merged 2026-10-23): removed the stale VM IP 34.31.112.77 from RESUME.md (the GCP VM is retired). Part of the 2026-10-22 branch cleanup.
- PR #3 (merged 2026-10-10, earlier than this window): configurable chat/embedding models via `TB_CHAT_MODEL`, `TB_EMBEDDING_MODEL`.

## Open items (in order)
1. Operator to decide the repo's fate now that Terrestrial Brain is dropped (archive, keep as reference, or leave). No action taken.
2. The `x-brain-key` that leaked in history was public from 2026-09-18 (see MEMORY.md); rotation was left to the operator. Status of rotation: not found by the files read.
3. Remote branch `origin/chore/drop-stale-vm-ip` remains after merge; delete only on operator command.

## Next steps
- None required until item 1 is decided.

## Sources
Read: CLAUDE.md (session context), old RESUME.md (head), MEMORY.md, `git log origin/main --since=2026-10-18`, PR #7 and #3 metadata, branch protection. Not read: README.md, ThreatModel.md, Planning/, openspec/, CI logs, CLAUDE.md contents beyond context.
