# Ratecard

The pricing studio for freelancers and consultants. One HTML file, no dependencies, works offline: floor rate, value pricing, three-tier proposal builder, change-order generator, and a pricing playbook.

This is the paid product. It is sold at https://nishulegacy.gumroad.com/l/ratecard ($24) and in the Career Independence Bundle with the Job Search Kit. Keep this repo private and do not publish it through GitHub Pages.

## Layout

| Path | What it is |
| --- | --- |
| `index.html` | The app. Open it in a browser, that is the whole thing. |
| `GUMROAD.md` | Listing copy for the Gumroad product page. |
| `dist/` | What buyers download: `Ratecard.html` (buyer edition), `Ratecard-v1.zip`, the Quick Start PDF, and cover images. |
| `screenshots/` | Marketing screenshots at desktop and phone widths. |

## Shipping a new version

1. Edit `index.html` and test at 390px and 1280px.
2. Rebuild the buyer edition in `dist/` and bump the zip name (`Ratecard-v2.zip`).
3. Upload the new zip to the Gumroad product. Existing buyers get it as a free update.
4. Tag the release: `git tag v2 && git push --tags`.

## Related

- Free lead magnet, the Hourly Rate Calculator, stays public in the TBD-Claude lab at https://nishu1996builds.github.io/TBD-Claude/free/rate-calculator/ and links here.
- Store-level marketing (LinkedIn, Reddit, X, email, launch posts) lives in `marketing/` in TBD-Claude because it covers every Gumroad product, not just Ratecard.

## History

Extracted from `nishu1996builds/TBD-Claude` with commit history preserved.
