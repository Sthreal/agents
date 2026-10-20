---
"@cloudflare/think": patch
---

Stamp the assistant message id onto approval-continuation `start` chunks so live streams reconcile with the persisted reply instead of rendering it twice. Fixes #2503.
