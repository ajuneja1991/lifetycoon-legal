# lifetycoon-legal

Public hosting for the **LifeTycoon** (`com.ajuneja.life_tycoon`) legal pages, served via GitHub Pages.

- Privacy policy: <https://ajuneja1991.github.io/lifetycoon-legal/privacy-policy/> (the site root serves the same page)
- Terms of Service: <https://ajuneja1991.github.io/lifetycoon-legal/terms/>
- Refund policy: <https://ajuneja1991.github.io/lifetycoon-legal/refund-policy/>
- Data deletion: <https://ajuneja1991.github.io/lifetycoon-legal/data-deletion/>

**Source of truth** is `docs/legal/{privacy-policy,terms,refund-policy,data-deletion}.md` in the private
app repo. Each page here is rendered from that Markdown; when one changes, re-render it, keep the
"Last updated" date in sync, and push.

`.nojekyll` is present so the static HTML is served as-is with no build step.
