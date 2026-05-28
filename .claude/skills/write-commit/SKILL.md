---
name: write-commit
description: Write a clear commit message based on my changes. Use when you've made code changes and need a good git commit message.
disable-model-invocation: true
---

## Task

I've made some code changes. Write a concise commit message that:

1. Starts with a verb (Add, Fix, Update, Refactor, etc.)
2. Is one sentence, under 72 characters
3. Explains the "why", not just the "what"

Use `git diff HEAD` and `git status` to see what changed before writing the message.

Provide only the commit message, nothing else.
