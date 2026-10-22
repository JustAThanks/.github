# Contributing

Thank you for helping.
Every repository has an `AGENTS.md` with the full conventions, and a `CLAUDE.md` with the map.
This page is the short version.

## Before you start

- Open an issue first for anything larger than a small fix, so the direction is agreed before the work.
- Check `docs/` in the `justathanks` repository for the plan and the decisions already made.

## Setting up

Each repository's `README.md` has the exact commands.
All of them need Node 24 and pnpm 11, and the server needs Docker for the local Supabase stack.

## The rules that matter most

- Commits are one line, plain English, one commit per logical change, no prefixes and no trailers.
- Pull request titles read like a commit subject. The body says only what the diff cannot show.
- Run the full gate before you push: `pnpm verify`.
- Money is integer paise, never floats or strings.
- A payment is paid only when a verified webhook, or a fetch from the provider, says so.
- The product name lives in one config file per repository. `pnpm brand:check` fails if it appears anywhere else.
- Secrets never go into a file in a repository.

## Reviews

A review runs the code, not just reads it.
Reproduce a bug before trusting its fix, and run new tests against the code before the fix.
Comments state a fact and an ask, then stop.
