# kalshi-edge-site

The Kalshi Edge website: https://arnavmahadev.github.io/kalshi-edge-site/

This repo only hosts the built page for GitHub Pages. It is generated and pushed by the daily
job in the (private) `arnavmahadev/kalshi-edge` repo, several times a day:

- `index.html` — the whole page in one file (today's games, suggested combos, open bets, record)
- `version.txt` — changes on every build; open pages poll it and reload themselves
- `.nojekyll` — serve the files as-is

Don't edit anything here by hand; the next run overwrites it. Change the page in
`kalshi_edge/site.py` in the code repo instead.
