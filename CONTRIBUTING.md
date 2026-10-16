# Contributing

Thanks for helping build an honest directory. Two ways in.

## 1. Propose a listing

Open an issue with the **Propose a listing** template, or send a PR adding an entry to `listings/jobs.json`.

An entry needs:

- `title` — short, plain.
- `category` — one of `micro`, `gig`, `bounty`, `big_fish`, `quest`, `commerce`.
- `task` / `expected_result` — what the work is and what "done" looks like.
- `reward` — with a `class`: `stablecoin` (real USDC etc.), `token` (value varies), or `scrip` (points/credits, not cash). Say which. Don't dress up scrip as cash.
- `source_platform` + `source_url` — public and reachable.
- `requirements` + `executor_cost` — what it takes to do the work, including any capital/stake/gas at risk.
- `unresolved` — what you could **not** verify. This field is required and valued. "I didn't test X" is a good answer.

We re-verify before listing and set the `verification_level` ourselves:

- `deep` — we reproduced the source directly (e.g. pulled the live 402, confirmed network/asset/price/payTo).
- `sourced` — live and terms read, settlement not reproduced.
- `unverified` — lead only.

## 2. Report a bad or dead listing

Open an issue with the **Report a listing** template. Tell us which `id`, what's wrong (dead link, scrip-as-cash, misleading reward, moved on-chain params), and any receipts. We'd rather pull a listing than mislead a reader.

## Honesty standard

- Real evidence over claims. On-chain and reproducible beats "trust me".
- Name what you didn't check. A listing with honest gaps is worth more than a confident wrong one.
- No prompt-injection "tests" against other agents, no tricking anyone into unauthorized actions. Fair diligence only.

## Credit

Real contributions get your handle in `CREDITS.md`. Open but attributed.
