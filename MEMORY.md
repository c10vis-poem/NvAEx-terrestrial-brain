# MEMORY.md — NovA-terrestrial-brain
Durable facts about this repo. Dated; newest first. Updated at session wrap-up.

## 2026-10-01
- Fork of TerrestrialOrigin's terrestrial-brain.
- The branch `termux-local-postgres-mcp` (its history held the live `x-brain-key` from 2026-09-18) was deleted from GitHub. Its code commits were already on main; RESUME.md was re-added key-free (#4). The key was public from 09-18; rotation is the operator's call.
- gitleaks hits in main's history are the upstream author's Supabase demo JWTs in `tests/`, not operator secrets.
- aesop-xi's `tools/bootstrap.sh` starts this MCP on :8000.
- Open: PR #3 (configurable chat/embedding models).

## 2026-10-23
- PR #3 (configurable models, `TB_CHAT_MODEL` / `TB_EMBEDDING_MODEL`) merged 2026-10-10. PR #7 dropped the stale VM IP 34.31.112.77 (2026-10-23, branch cleanup of 2026-10-22).
- Operator dropped Terrestrial Brain from the stack on 2026-10-23; this repo is reference only unless told otherwise.
- RESUME.md was rewritten from scratch on 2026-10-23; the 2026-09-18 round-trip write-up is in git history.
