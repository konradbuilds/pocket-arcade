# Pocket Arcade v0.3

Same Pocket Arcade app and same GitHub Pages URL.

Games:
- **TILT RACER** — rebuilt with real synced forward motion, slower start and smoother acceleration.
- **BALANCE** — retained.

## Performance changes
- Canvas DPR capped at 1.5 for phones.
- Fewer road strips and decorative objects.
- Removed expensive blur effects from gameplay UI.
- Road, centre dashes, scenery and obstacles share one forward-travel value.
- Objects spawn much more slowly at the beginning.
- Procedural chiptune tempo follows actual racer speed.

## Update your existing GitHub Pages app
Replace the files in the same repository root and commit.

Do not create a new repository. The URL stays the same.

If the previous PWA version appears after deployment, fully reload or reopen once so the new service worker takes over.
