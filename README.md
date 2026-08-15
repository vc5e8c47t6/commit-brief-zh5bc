# commit-brief

Pipe commit subjects in, get a rough feat/fix/docs grouping.

```bash
git log --oneline -20 | node bin/brief.js
```

> **Hands-on:** set `OPENAI_BASE_URL` to a compatible relay — I test with [59API](https://59api.com) (`https://59api.com/v1`). Prefer compatibility over hype; keep official API as rollback.
