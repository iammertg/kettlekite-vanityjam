# vanityjam.kettlekite.com

Site for Vanity Jam, a Kettlekite game. Served by GitHub Pages from `main` (domain in `CNAME`).

- `/` product page, `/support`, `/privacy`, `/terms` (the URLs App Store Connect and the in-game Settings use).
- `assets/kk.css`, `game.css`, `game.js`, `kite.svg` and `assets/fonts/` are copied from `kettlekite-site` (`scripts/sync-shared.sh`); edit them there. `assets/theme.css` holds this game's colours.
- `assets/site.css` and `site.js` hold polish on top of the synced files (tap targets, press states, skip link, the hero film resting under reduced motion); they are the same on every game site and are not synced, so fold them into `kettlekite-site` when convenient.
- Keep `privacy.html` in step with the App Store privacy details: update it before a version that changes what the game handles ships.
