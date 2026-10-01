# Pocket Arcade v0.4

Same Pocket Arcade app and same GitHub Pages URL.

Games:
- **TILT RACER** — game 1
- **BALANCE** — game 2

## v0.4 racer changes
- Much smoother forward motion.
- Stable road surface instead of snapping road bands.
- Curbs, centre dashes, scenery and obstacles move continuously from the same travel value.
- Long frames are split into small simulation steps to reduce visible jumps.
- Phone render density capped at 1.25× for better frame rate.
- Starts at about **90 km/h-ish**.
- Clean driving climbs smoothly to about **1140 km/h-ish**.
- Obstacles remain sparse at the beginning.
- 8-bit music tempo still follows speed.

## Update
Replace the files in the same GitHub repository root and commit.
The GitHub Pages URL stays the same.

If an old PWA build appears once after deployment, close/reopen or hard-refresh so the new service worker takes over.
