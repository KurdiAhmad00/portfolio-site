# Ahmad Kurdi — Portfolio

Personal portfolio of a full-stack developer (React & Laravel).

The entire site is one self-contained `index.html` — vanilla HTML/CSS/JS,
no frameworks, no build step, no dependencies. All assets (images, effects,
scripts) are embedded inline.

## Features

- Interactive canvas particle background (mouse-reactive, respects reduced-motion)
- Cursor light flare + scroll-following ambient flare
- Scroll-reveal animations via IntersectionObserver
- Contact form with clipboard-copy email fallback
- Responsive layout, dark theme (black / purple / red)

## Run locally

Open `index.html` in a browser. That's it.

## Deploy

Any static host works — there is nothing to build, output directory is the root.

- **GitHub Pages:** Settings → Pages → Deploy from branch → `main` / root
- **Cloudflare Pages:** Workers & Pages → Upload assets → drag the project folder

## Contact form setup

Out of the box, the form opens the visitor's mail app pre-addressed to me.
For direct in-browser submissions, create a free form at
[formspree.io](https://formspree.io) and paste the endpoint into
`FORMSPREE_ENDPOINT` at the bottom of `index.html`.

## Notes

- Case studies reference real production work (Sulhafa) and personal projects
  (Laravel-Task). No proprietary code is included in this repository.
- Optional polish: custom domain, project screenshots, favicon.

---
© 2026 Ahmad Kurdi — Thinks first. Builds second.
