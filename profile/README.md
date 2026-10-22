# Just a Thanks

Thank-yous, paid in full.

A support page for creators.
Fans leave a note and an amount, in two taps, with no account.
Every rupee of a thanks reaches the creator.
Memberships and downloads carry a small fee, and the money reaches the creator's bank within two working days.

## Repositories

| Repository | What it holds |
| --- | --- |
| `justathanks` | The website: landing page, creator pages, the dashboard and the admin panel. TanStack Start on Cloudflare Workers. |
| `server` | The API: payments, the ledger, memberships, payouts and the admin API. Hono on Cloudflare Workers with Postgres. |
| `blog` | The blog. Astro, deployed on Cloudflare. |
| `.github` | This profile, the templates every repository shares, and the policies. |

## How we work

- One-line commits in plain English, one commit per change.
- Pull requests say only what the diff cannot show.
- Money is integer paise, never floats.
- A payment counts as paid only when a verified webhook says so.
- Every change runs the full gate before it is pushed: lint, typecheck, tests, brand check.

The full conventions are in `AGENTS.md` at the root of each repository.

## Contact

support@justathanks.com for anything about the product.
security@justathanks.com for security reports, see `SECURITY.md`.
