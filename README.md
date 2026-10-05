# all_privacy_policy

Central repository hosting the privacy policies for all published applications.

## Live site

GitHub Pages (branch `main`, folder `/ (root)`):

- Index: https://codex-zubair.github.io/all_privacy_policy/
- NetCarve: https://codex-zubair.github.io/all_privacy_policy/netcarve/

## How to add a policy for a new app

1. Create a folder named after the app slug, e.g. `myapp/`.
2. Add `myapp/index.html` (copy an existing policy and update the text).
3. Add a card for it in the root `index.html`.
4. Commit and push to `main`. GitHub Pages redeploys automatically.

## Notes

- `.nojekyll` is present so Pages serves files verbatim and never fails a Jekyll build.
- The URL pattern is stable: `https://codex-zubair.github.io/all_privacy_policy/<slug>/`.
- One repository for every app's policy, so Pages only needs to be enabled once.