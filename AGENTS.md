# AGENTS.md

Instructions for automation agents (Claude Code, Codex and similar) that work in this repo.

## Repository

- **Name:** `orangeelefant/webraketen-org-profile`
- **Purpose:** The Webraketen profile: prices, process and the list of sites that Webraketen builds and runs.
- **Live:** https://webraketen.se

## Rules

- Read `CLAUDE.md` and `TODO.md` before you change anything.
- Push directly to `main`. Make one logical change in each commit.
- Never commit credentials. Reference secrets through environment variables.
- Keep the URL and the anchor text of each link to a customer site. The Webraketen backlink engine counts them.
- Public copy is Swedish unless the file is in English.
- Add one line under `## [Unreleased]` in `CHANGELOG.md` for every change to content or configuration.
- `profile/README.md` is the Webraketen text. The backlink engine adds sites to the list at its end.
