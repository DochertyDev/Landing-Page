# README preview capture

Captured 2026-10-17 from main commit `7264598` in desktop Chromium at 1440px wide, device scale 1, after the page fonts were ready and image decoding completed. The committed PNG is 1440 x 758 pixels.

The capture includes the site header and opening Atlas hero only. Its bottom edge is the boundary between `#hero` and `#projects`; project cards and all subsequent sections are intentionally excluded so readers can explore the live portfolio themselves. The README preview and the accompanying "Explore the full portfolio" link both open https://dochertydev.github.io/Landing-Page/.

To reproduce, open `index.html` in Chromium with a 1440 x 1000 viewport and device scale 1. Wait for `document.fonts.ready` and image decoding, then take a screenshot with animations disabled, clipping from x=0, y=0 to width=1440 and height rounded from the bottom of `#hero` (758px at this commit). Do not use a full-page capture.

The screenshot was captured locally with external HTTP/HTTPS requests blocked. No private application screens or data were used, and no page content or styles were altered for the capture.
