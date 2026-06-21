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

"Execute this task using Maximum Effort and adaptive deep reasoning. Before answering, map out your logic path in a hidden thinking block, flag any gaps or uncertainties in your knowledge pool, and deliberately cross-examine your own conclusions for biases. Do not summarize unless explicitly requested."




"Analyze the attached material/premise. Break it down into its core variables and hidden assumptions. Present your structural analysis first. Do not write the final essay/report yet. Wait for my confirmation on the variables."


"Act as an aggressive, skeptical peer reviewer. Audit this text line-by-line. Explicitly highlight any unsupported claims, logical leaps, or weak arguments. Rate the confidence of each section from 1-10 based purely on verifiable logic."
