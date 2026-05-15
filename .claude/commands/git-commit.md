Look at the current git diff (staged and unstaged changes) using `git diff HEAD` and `git status`, then automatically generate a commit message with:

1. A **header** — short and concise (under 72 characters), summarizing the overall change
2. A **description** — a dash list explaining the specific details of what was done

Format the commit message as:
```
<header>

- <item 1>
- <item 2>
- ...
```

Then show the user the generated message and ask for confirmation before committing. If confirmed, run `git add -A` (if nothing is staged) and `git commit` with that message.
