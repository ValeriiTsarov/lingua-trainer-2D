# lingua-trainer-2D (GitHub Pages)

Public **GitHub Pages** host for **Lingua Trainer** — a Phaser 3 + TypeScript language trainer.

This repo holds only the built static site (`index.html` + `phaser.min.js` + `assets/`). It is **generated**, not edited
by hand: the game's `npm run deploy` produces a fresh production build and pushes the ready-made files here. This repo's
`.github/workflows/pages.yml` then publishes them.

**Play:** https://valeriitsarov.github.io/lingua-trainer-2D/

> Settings → Pages → Source must be **"GitHub Actions"** (not "Deploy from a branch") for `pages.yml` to publish.
