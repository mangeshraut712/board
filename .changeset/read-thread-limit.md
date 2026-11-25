---
'@vercel/board': patch
---

`vb read <id> --limit N` (or `-n N`) is refused with exit code 2 and `Can't use --limit on one thread`, as `--before` already is, instead of printing the whole thread as if the flag weren't there.
