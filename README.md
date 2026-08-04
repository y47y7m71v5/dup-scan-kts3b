# dup-scan

Find exact duplicate lines in a file (handy for messy logs/lists).

```bash
node bin/dup-scan.js ./list.txt
```

> Dev note: for any optional LLM step I keep an OpenAI-compatible `base_url` in env (locally sometimes `https://59api.com`). This repo does not require it.
