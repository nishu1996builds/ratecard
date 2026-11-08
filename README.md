# Ratecard

The pricing studio for freelancers and consultants. One HTML file, no dependencies, works offline: floor rate, value pricing, three-tier proposal builder, change-order generator, and a pricing playbook.

This is the paid product. It is sold at https://nishulegacy.gumroad.com/l/ratecard ($24) and in the Career Independence Bundle with the Job Search Kit. Keep this repo private and do not publish it through GitHub Pages.

## Layout

| Path | What it is |
| --- | --- |
| `index.html` | The app. Open it in a browser, that is the whole thing. |
| `GUMROAD.md` | Listing copy for the Gumroad product page. |
| `dist/` | What buyers download: `Ratecard.html` (buyer edition), `Ratecard-v1.zip`, the Quick Start PDF, and cover images. `dist/bundle/cover.png` is the Career Independence Bundle cover. |
| `screenshots/` | Marketing screenshots at desktop and phone widths. |
| `free/rate-calculator/` | The free Hourly Rate Calculator, the lead magnet that links here. One HTML file plus its OG image and screenshots. |
| `marketing/` | The store-level marketing pack for nishulegacy.gumroad.com: 14-day plan, LinkedIn, Reddit, X, launch posts, emails, and the channel scorecard. It covers every Gumroad product, so it lives with the first paid one. |

## Shipping a new version

1. Edit `index.html` and test at 390px and 1280px.
2. Rebuild the buyer edition in `dist/` and bump the zip name (`Ratecard-v2.zip`).
3. Upload the new zip to the Gumroad product. Existing buyers get it as a free update.
4. Tag the release: `git tag v2 && git push --tags`.

## Related

- The free Hourly Rate Calculator moved here from the TBD-Claude lab on Nov 8, 2026 and is hosted on Netlify from `netlify.toml`, which publishes only `free/rate-calculator/`. One-time setup: at app.netlify.com choose **Add new site, Import an existing project, GitHub**, pick this repo and `main`, deploy, then rename the site (for example `rate-calculator`). Once the URL exists, update the canonical and OG tags in `free/rate-calculator/index.html` and every calculator link in `marketing/`. The old lab address, https://nishu1996builds.github.io/TBD-Claude/free/rate-calculator/, is gone.
- `marketing/channels.md` section B covers SoftOpen channels; the SoftOpen landing page itself lives in `nishu1996builds/SoftOpen` under `site/`.

## History

Extracted from `nishu1996builds/TBD-Claude` with commit history preserved.
