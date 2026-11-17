# The Open Signal Project — GitHub Pages drop-in

A static research microsite designed for The Hungry Rope.

## Install

1. Open the GitHub repository that serves `thehungryrope.press`.
2. Upload the entire `open-signal` folder to the **publishing root** (often repository root, sometimes `/docs`). Keep the folder structure intact.
3. Commit changes to your publishing branch. Your hosting deployment will publish the section at `https://www.thehungryrope.press/open-signal/`.
4. Optional: add a link from your main site: `<a href="/open-signal/">Open Signal Project</a>`.
5. Check the email address `editor@thehungryrope.press` is active before soliciting submissions.

## Important

- The site does **not** send/receive submissions automatically. The contact action is an ordinary `mailto:` link.
- `research.json` is machine-readable metadata, not an A2A Agent Card or a working API.
- No backend, analytics, trackers or data collection scripts are included.
- External Google Fonts are requested by CSS; remove the `@import` line for zero external font requests.
- The four registry leads are user-supplied directory observations and remain explicitly unverified.
- Do not overwrite your existing root `robots.txt` or `llms.txt` without checking them. Optional standalone draft snippets are supplied separately.
- A static GitHub Pages website cannot establish which crawler or AI system read a page, and an agent response cannot on its own prove autonomy.

## Customize

Edit `style.css` for colors and type, `index.html` for the invitation, `registry.html` for verified notes, `field-notes.html` for observations, and `research.json` for machine-readable research metadata. Keep claims and evidence labels accurate.
