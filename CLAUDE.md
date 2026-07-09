# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project status

`my-first-harness` is a minimal harness project for a two-agent team that generates commit messages. The repository is currently an empty scaffold — no source code, package manifest, build system, or tooling has been added yet, so there are no build/lint/test commands to run. This file will need updating once real code and tooling are added.

## Repository layout

- `_workspace/` — intermediate/working artifacts (empty).
- `.claude/agents/` — agent definitions for the two-agent team (empty).
- `.claude/skills/commit-message/` — the commit-message-generation skill (empty; still to be written).

## Rules

- Commit messages must follow Conventional Commits format: `type(scope): subject`.

Note: `.claude/CLADUE.md` is a pre-existing, misspelled duplicate of this file's source content — this `CLAUDE.md` supersedes it.
