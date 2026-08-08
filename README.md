# SOS 110 · Chapter 5 — Conservation

Click-through web slideshow for **Chapter 5: Conservation — Why Is It Important
to Protect Biodiversity?** (SOS 110).

**Live:** https://ryanpcornell.github.io/sos110-chapter-5/

Self-contained static site (GitHub Pages). Built from the reusable `_deck-builder`
pipeline. Includes several live, in-slide class interactives backed by Firebase
Firestore (spectrum "Agree ↔ Disagree" polls, a "type a dollar amount" valuation
poll, and a bespoke Intrinsic-Value valuation slide). Add `?host` to the projected
copy's URL to get the instructor controls (reveal/reset); students use the plain URL.

## Files
- `index.html` — the whole deck.
- `media/` — images.
- `firebase-config.js` — client Firebase config for the live polls (safe to publish;
  access is scoped by Firestore security rules).
- `.nojekyll` — serve files as-is on GitHub Pages.
