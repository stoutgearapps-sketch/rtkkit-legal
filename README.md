Public GitHub Pages for RTKKit (Stout Gear LLC).

Source of truth for the text is `docs/privacy.md` and `docs/terms.md` in stoutgearapps-sketch/rtkkit at commit 35d274b07670d5437126e53ec2350dec2bad64b6.

The pages under `/privacy/`, `/terms/`, and `/support/` keep that text. `app-config.json` and `CNAME` are unchanged. The site does not load third-party fonts, analytics, or trackers.

## Landing page

`index.html` is the marketing page. Screenshot files are illustrated stand-ins until final app captures are ready. Replace the PNGs in place and keep these filenames:

- `assets/screens/*.webp` — iPhone screenshots (780×1695 WebP, from the App Store set). The hero uses `machine-guidance.webp`.
- `assets/screens/tablet/*.webp` — Android tablet screenshots (800×1280 WebP).

Recommended size is 780×1688 PNG (a tall phone). The frames use that aspect ratio and `object-fit: cover`, so another tall screenshot still fills the phone.

`assets/plot-plan-sample.png` is a render of the fictional sample plot plan (StoutGear-Sample-PlotPlan.pdf). Swap that file to change the sheet on the page.

The header mark and favicon use the Stone app icon (`assets/app-icon.png`, from `variant-2-stone-512.png`). `assets/favicon-32.png`, `assets/apple-touch-icon.png`, and `favicon.ico` are the same icon at tab sizes.

## Store badges

The App Store listing is live. `#store-link-app-store` uses the official black "Download on the App Store" badge (`assets/app-store-badge.svg`, from [Apple's badge guidelines](https://developer.apple.com/app-store/marketing/guidelines/)) and links to `https://apps.apple.com/us/app/rtk-kit/id6760628726` (seller Anthony Stout, bundle `app.replit.rtkkit`). It is placed first, ahead of the Google Play badge.

Google Play is live (US). `#store-link-google-play` uses the official "Get it on Google Play" badge (`assets/google-play-badge.png`, from [Google's badge guidelines](https://play.google.com/intl/en_us/badges/)) and links to `https://play.google.com/store/apps/details?id=app.replit.rtkkit`.

The footer logo is `assets/stout-gear-logo.png`, the transparent Stout Gear mark, shown light on the dark background with a CSS filter.
