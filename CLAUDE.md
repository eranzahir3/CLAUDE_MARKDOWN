# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project overview

<!-- TODO: One or two sentences: what this project is and who it's for. -->

This is a course exercise (HOME_WORKS_DEV_COURS) for practicing Claude Code workflows: `CLAUDE.md`, git, and worktrees. It doesn't contain application code yet.

## Repository

- Git repository with `main` as the default branch.
- Worktrees go **next to** this folder, not inside it. For example:
  ```
  git worktree add ../CLAUDE_MARKDOWN-<name> -b <name>
  ```
- Commit messages: short, imperative, lowercase (for example `add login form`).

## Commands

<!-- TODO: Fill these in once a stack is chosen. Keep only the ones that exist. -->

| Task              | Command |
|-------------------|---------|
| Install deps      | `TODO`  |
| Run / dev server  | `TODO`  |
| Build             | `TODO`  |
| Lint / format     | `TODO`  |
| All tests         | `TODO`  |
| Single test       | `TODO`  |

## Architecture

<!-- TODO: Describe the big picture once code exists:
     - main entry point(s)
     - how the main modules talk to each other
     - where state / data lives
     - anything non-obvious that would take reading several files to figure out -->

## Conventions

<!-- TODO: Add only rules specific to this project that Claude couldn't infer from the code,
     e.g. "use pnpm, not npm", "all API calls go through src/api/client.ts". -->

## Working with Claude

- Ask before running destructive git commands (`reset --hard`, `push --force`, deleting branches or worktrees).
- Keep this file up to date: after adding a tool, command or major module, update the matching section above.
