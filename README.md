Public GitHub Pages for RTKKit (Stout Gear LLC).

Source of truth for the text is `docs/privacy.md` and `docs/terms.md` in stoutgearapps-sketch/rtkkit at commit 35d274b07670d5437126e53ec2350dec2bad64b6.

The pages under `/privacy/`, `/terms/`, and `/support/` keep that text. `app-config.json` and `CNAME` are unchanged. The site does not load third-party fonts, analytics, or trackers.

## Landing page

`index.html` is the marketing page. Screenshot files are illustrated stand-ins until final app captures are ready. Replace the PNGs in place and keep these filenames:

- `assets/screens/layout.png` — Layout: captured points, a baseline, square-off, and the accuracy readout
- `assets/screens/plan-import.png` — Plan Import with a plot plan tied to control
- `assets/screens/machine-guidance.png` — Machine Guidance cut/fill readout. The hero uses this file too.
- `assets/screens/surface.png` — A surface built from points

Recommended size is 780×1688 PNG (a tall phone). The frames use that aspect ratio and `object-fit: cover`, so another tall screenshot still fills the phone.

`assets/plot-plan-sample.png` is a render of the fictional sample plot plan (StoutGear-Sample-PlotPlan.pdf). Swap that file to change the sheet on the page.

The header mark and favicon use the Stone app icon (`assets/app-icon.png`, from `variant-2-stone-512.png`). `assets/favicon-32.png`, `assets/apple-touch-icon.png`, and `favicon.ico` are the same icon at tab sizes.

## Store badges

In `index.html`, search for `STORE LINKS`. Set the `href` on `#store-link-app-store` and `#store-link-google-play` when the listings are live. Both currently point at `#coming-soon` on this page.

The footer logo is `assets/stout-gear-logo.png`, the transparent Stout Gear mark, shown light on the dark background with a CSS filter.
