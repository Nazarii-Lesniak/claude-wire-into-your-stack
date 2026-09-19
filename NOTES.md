# NOTES

- **Server**: Connected `fetch` server for API docs access. Scoped permission to allow only read operations.
- **Skill**: Created `code-review` skill triggered on route and endpoint reviews.
- **Command**: Added `/review` command to automate basic pull-request checking.
- **Hook**: Configured `PostToolUse` hook on `Edit` to run `npm test` automatically.
- **Headless**: Executed single task with `--allowedTools` limited to read-only actions.
