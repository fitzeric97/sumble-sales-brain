# Sumble Sales Brain

Eric's AE knowledge base. The content lives in [`docs/`](docs/) and is published as a mobile-friendly site at:

**https://fitzeric97.github.io/sumble-sales-brain/**

## What's inside

- [`docs/Sumble Sales Brain.md`](docs/Sumble%20Sales%20Brain.md) — the main operational toolkit (ICP, plays, email rules, MCP tooling notes).
- [`docs/outbound-briefs/`](docs/outbound-briefs/) — strategic research briefs per target account.
- [`docs/battlecards/`](docs/battlecards/) — competitor objection handling.
- [`docs/competitive-landscape.md`](docs/competitive-landscape.md) — market positioning, customer power quotes, SWIM analysis.

## Adding a new brief

Drop a `.md` file in [`docs/outbound-briefs/`](docs/outbound-briefs/) following the [TEMPLATE](docs/outbound-briefs/TEMPLATE.md) and naming convention `{target}-{anchor}-{YYYY-MM-DD}.md`. Push to `main` and the [live site](https://fitzeric97.github.io/sumble-sales-brain/) updates within ~2 minutes.

## Previewing locally (optional)

```bash
python3 -m venv .mkdocs-venv
.mkdocs-venv/bin/pip install -r requirements-docs.txt
.mkdocs-venv/bin/mkdocs serve
```

Open http://127.0.0.1:8000.

## How publishing works

`.github/workflows/docs.yml` runs `mkdocs gh-deploy` on every push to `main`, which builds the site and force-pushes the result to the `gh-pages` branch. GitHub Pages serves that branch.

**One-time setup** in repo Settings → Pages: set Source to *Deploy from a branch*, branch `gh-pages`, folder `/ (root)`.
