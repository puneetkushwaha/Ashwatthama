# Contributing to Ashwatthama

Thank you for contributing to Ashwatthama! Please check existing issues and pull requests before creating new ones.

## Setup

Prerequisites:

- [Rust](https://rustup.rs)
- [Bun](https://bun.sh)
- [Node.js 22+](https://nodejs.org)

```bash
bun install
bun dev
```

## Before Submitting

1. Code passes checks: `bun check`
2. Auto-fix issues: `bun fix`
3. Formatting only when needed: `bun format`
4. App runs: `bun dev`
5. Run release validation when touching release flow: `bun release:check`
6. Rebase on main: `git rebase origin/main`
7. Squash commits into logical units

## Guidelines

- Follow the existing code style
- Use descriptive commit messages (i.e., "Add autocompletion")
- One logical change per commit
- Update documentation if needed

## Rust Tests

- Keep small unit tests in a `#[cfg(test)] mod tests` block beside the code they exercise.
