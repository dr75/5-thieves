# CLAUDE.md

## Git workflow

- Always commit directly to `main` and push (`git push -u origin main`).
- Do not create feature branches or pull requests unless explicitly asked.

## Project

A single-file PWA (`index.html`) — no build step, no dependencies, no server.
State lives in `localStorage` under the key `kebab:state`. Keep it that way:
no accounts, no tracking, no gamification (see README, "Deliberate
non-features").
