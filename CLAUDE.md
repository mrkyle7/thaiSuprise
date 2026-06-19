# Thai Surprise — working notes

Single-file HTML5 canvas game (`index.html`), vanilla JS, zero dependencies.
Hosted via GitHub Pages (branch-based, `main` / root) at
https://mrkyle7.github.io/thaiSuprise/ (case-sensitive path).

## Release convention (IMPORTANT)

On **every push to `main`**:

1. **Bump `GAME_VERSION`** in `index.html` (the const near the top of the
   script) following semver — patch for fixes, minor for features.
2. **Create a matching local annotated tag** (`git tag -a vX.Y.Z -m "..."`).
3. **Tell the user the exact `git push origin main` + `git push origin vX.Y.Z`
   commands** to run, because pushing tag refs from this environment is blocked
   (HTTP 403 — restricted token can update branch refs but not tag refs).

The footer (`#version`) renders `v` + `GAME_VERSION`, so the footer and the
git tags stay aligned.

## Deploy note

GitHub Pages is branch-based (Settings → Pages → Deploy from a branch → `main`
/ root). The Actions-based Pages workflow does **not** work here (restricted
Actions token), so it was removed — don't re-add it.
