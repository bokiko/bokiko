# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Is

GitHub profile README repository (`bokiko/bokiko`). The `README.md` renders on [github.com/bokiko](https://github.com/bokiko) as the profile page. There is no application code, build system, or tests.

## Repository Structure

- `README.md` — The profile page content (Markdown with HTML/badges)
- `.github/workflows/mirror-gitlab.yml` — Mirrors all branches/tags to GitLab on push
- `.kyzn/` — KyZN analysis config; `kyzn-report.md` — latest analysis output

## How to Work Here

All changes are to `README.md`. No build or test steps — just edit and push.

Key elements in the README:
- **Typing SVG header** — animated text cycling "Miner. / Builder. / Data nerd." via `readme-typing-svg.demolab.com`
- **Profile links** — bokiko.io, X, Medium (shield.io badges)
- **Project tables** — categorized (AI & Developer Tools, Mining & Crypto) with emoji icons, repo links, descriptions, and star counts
- **Collapsible section** — `<details>` block for secondary projects
- **Tech stack icons** — via `skillicons.dev`
- **GitHub stats** — `github-readme-stats.vercel.app` and `github-readme-streak-stats.herokuapp.com`

## Conventions

- Use shield.io flat-square style badges for profile links
- Project tables use emoji column + bold repo name + inline language/star badges
- Keep the "Currently building" line updated with the active focus project
- Commit messages follow conventional commits: `feat:`, `fix:`, `docs:`
