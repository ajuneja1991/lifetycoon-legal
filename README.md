# lifetycoon-legal

Public hosting for the **LifeTycoon** (`com.ajuneja.life_tycoon`) legal pages, served via GitHub Pages.

- Privacy policy: <https://ajuneja1991.github.io/lifetycoon-legal/privacy-policy/>
  (the site root serves the same page).

**Source of truth** is `docs/legal/privacy-policy.md` in the private app repo. When that changes,
update `index.html` and `privacy-policy/index.html` here to match (keep the "Last updated" date in
sync) and push.

`.nojekyll` is present so the static HTML is served as-is with no build step.
