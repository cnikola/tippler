# CLAUDE.md

This file provides guidance for AI assistants working in this repository.

## Project Overview

**tippler** is a tool for offloading chunks from *picsanto* for review. The repository was created in 2014 and is currently in a placeholder/bootstrapping state — no implementation code has been committed yet.

## Repository State

This repository is essentially empty at the moment:

```
tippler/
├── README.md      # One-line project description
└── CLAUDE.md      # This file
```

There are no source files, configuration files, build scripts, tests, or dependencies defined yet.

## Development Conventions

Since the codebase has not been built out yet, the following conventions should be followed when implementation begins:

### Branching

- `master` — stable/main branch
- `claude/<session-id>` — AI-assisted session branches (e.g. `claude/claude-md-mme09n2mvtywepmn-Ym3t3`)

### Git Workflow

- Commit messages should be clear and descriptive
- Keep commits focused and atomic
- Push feature/session branches before merging into `master`

### Adding Code

When adding implementation code to this repository, update this file with:

1. **Language and framework** in use
2. **Build and run commands** (e.g. `npm install && npm start`, `make`, `cargo build`)
3. **Test commands** (e.g. `npm test`, `pytest`, `cargo test`)
4. **Environment setup** — required env vars, `.env.example`, etc.
5. **Project structure** — directory layout and what each folder contains
6. **Code style / linting** — formatter, linter, and how to run them

## Key Context

- The project name "tippler" suggests a drip/chunk-based transfer or review tool
- "picsanto" appears to be a related or upstream project; tippler acts as a review buffer or staging area for content from it
- No language or runtime has been committed to yet

## Notes for AI Assistants

- Do not assume any language, framework, or dependency exists — the repository has no code
- When implementing features, prefer minimal, focused changes
- Update this CLAUDE.md whenever significant structure is added to the project
- Check `git log` and `git status` before starting work to understand current state
