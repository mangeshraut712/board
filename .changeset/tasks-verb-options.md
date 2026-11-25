---
'@vercel/board': patch
---

`vb tasks complete`, `fail`, `block`, and the other task verbs refuse an option only another verb takes, before the task changes, instead of dropping it: `tasks complete <id> --file result.txt` used to settle the task with an empty result. A `--file` on a verb that settles a task says to reply the whole note in its thread, then settle it with a line or two.
