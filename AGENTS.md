# AGENTS.md

Instructions for automation agents (Claude Code, Codex and similar) working in this repository.

## Repository

- **Name:** `orangeelefant/webraketen-org-profile`
- **Purpose:** Webraketen's agency profile: prices, process and the list of sites we build and run.
- **Live:** https://webraketen.se

## Rules

- Read `CLAUDE.md` and `TODO.md` before changing anything.
- Push directly to `main`. One logical change per commit.
- Never commit credentials. Reference secrets through environment variables.
- Every existing link to a client site keeps its URL and anchor text. The Webraketen backlink engine counts them.
- Public copy is Swedish unless the file is already in English.
- Add a line under `## [Unreleased]` in `CHANGELOG.md` for every change to content or configuration.
- `profile/README.md` is the agency text. The site list at its end is extended by the backlink engine.
