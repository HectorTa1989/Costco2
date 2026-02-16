---
description: Automatically commit and push all files using the mapping in Docs/COMMIT_MESSAGES.md
---

1. run the sync script
// turbo
2. run `powershell -ExecutionPolicy Bypass -File Scripts/sync_commits.ps1`

---

**How to use:**
Type `/sync-commits` in the chat. 
Antigravity will parse the commit message document and commit each changed file with its specific message automatically.
