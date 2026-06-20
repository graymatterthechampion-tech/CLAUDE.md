# Claude Code Engineering Guidelines

## Operational Rules
- NEVER run destructive commands (e.g., `rm -rf`) without explicit confirmation.
- Always check the local test suite (`npm test`, `pytest`, etc.) before making a commit.
- Keep your terminal tool usage efficient: use specific search queries instead of viewing entire large directories.

## Code Style & Architecture
- Write strictly typed code. Follow the project's existing linting rules perfectly.
- Prioritize explicit, readable logic over clever, compact syntax.
- Handle edge cases, null pointers, and network failures aggressively.

## Automated Verification
- After modifying files, automatically run the specific test file associated with that change.
- Do not mark a task as complete until all tests pass successfully.
