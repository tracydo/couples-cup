# Couples Cup

The website for our 2026 fantasy football Couples League.

**Live site:** _(add your Vercel URL here)_

## How it works

`index.html` is the entire site. There's no build step and nothing to install.
It pulls scores straight from Sleeper's public API every time someone opens
the page, so it stays current on its own.

- Scores refresh on load, every 90 seconds, and whenever the tab comes back into view
- A week counts toward records and the $5 bets once the NFL moves on to the next one
- When a week wraps, the winner's face rains down the screen with a congrats banner
- If Sleeper can't be reached, the page falls back to the scores saved inside the file

## Updating the site

Replace `index.html` and commit. Vercel deploys the change automatically and
the URL stays the same.

## League

- Sleeper league ID: `1387862159001673728`
- 12 teams, 6 couples, half PPR
- Couples Cup runs Weeks 1 to 14
