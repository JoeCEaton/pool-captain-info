# Pool Captain — public pages

The public pages for **Pool Captain**, a free offline app for league pool players:
match odds, break-speed timing, table difficulty rating, and match logging that
shows the skill level your results actually describe.

This repository holds only these pages. The app's source lives elsewhere and is
private.

| File | What it is |
| --- | --- |
| `index.html` | What the app does, tool by tool, and the call for testers |
| `privacy-policy.html` | Privacy policy — the URL the app stores require |
| `screenshots/` | Screenshots used by `index.html` |

Both pages are self-contained: no build step, no dependencies, no external requests.
Open either file in a browser to preview it.

## Published with GitHub Pages

| Page | URL |
| --- | --- |
| Overview | https://joeceaton.github.io/pool-captain-info/ |
| Privacy policy | https://joeceaton.github.io/pool-captain-info/privacy-policy.html |

The policy URL is the one to paste into Google Play Console and App Store Connect.
Pages serves the default branch from the repository root, so committing a change to
`main` republishes it within a minute or so.

## Notes

- **Every player and logged match in the screenshots is fictional.** The names are invented
  and the match data was generated for illustration, then checked against the app's
  own calculations so the figures are self-consistent. No real player's record
  appears anywhere in this repository. The break log screenshot is an exception: it is a
  real set of break measurements, which carries speeds and distances but no names.
- The screenshots were captured from a release build running on an Android emulator.
- Pool Captain is an independent app, not affiliated with, endorsed by, or sponsored
  by the American Poolplayers Association, Fargo Rate, or any league operator or
  rating service.
