# CLAUDE.md

## Git workflow

- Always commit directly to `main` and push (`git push -u origin main`).
- Do not create feature branches or pull requests unless explicitly asked.
- Before committing a change to `index.html`, set the `BUILT` constant to the
  current local time (`date '+%Y-%m-%d %H:%M'`). It is shown at the foot of the
  review page and is the only way to tell a deployed version from a cached one.

## Project

A single-file PWA (`index.html`) — no build step, no dependencies, no server.
State lives in `localStorage` under the key `kebab:state`. Keep it that way:
no accounts, no tracking, no gamification (see README, "Deliberate
non-features").
