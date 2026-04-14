# Superpowers

## Project
- **Name**: superpowers
- **Org**: AiFeatures (iAiFy)
- **Language**: JavaScript (Node.js plugin)
- **Description**: Complete software development workflow for coding agents. Composable skills, subagent-driven development, spec-first design, TDD emphasis.

## Structure
- `skills/` -- composable skill definitions
- `commands/` -- user-invokable commands
- `agents/` -- subagent definitions

## Conventions
- 94% PR rejection rate -- read CLAUDE.md and PR template before contributing
- Every PR must complete the full PR template
- Search existing open AND closed PRs before opening new ones
- Domain-specific changes belong in standalone plugins, not core
- Conventional Commits

## CI/CD
- Uses shared workflows from `Ai-road-4-You/enterprise-ci-cd`
