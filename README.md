# codex-home

This repository is intended to sync reusable Codex prompt assets across devices.

Tracked content:
- `AGENTS.md`
- custom skills under `skills/*`

Ignored content:
- auth and local machine state
- logs, sessions, memories, and sqlite files
- built-in system skills under `skills/.system`

Recommended workflow:
1. Keep custom prompts in `AGENTS.md`.
2. Put reusable custom skills under `skills/<skill-name>/`.
3. Commit changes here and sync through your private remote.
