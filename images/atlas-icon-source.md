# Atlas icon artwork

Original vector artwork created for this portfolio in issue #27 (2026-10-17), using the existing Atlas hero’s three connected platform layers and palette (#091d38, #123451, #306ca6, #b7d9ff). No third-party artwork or fonts. The editable source is atlas-mark.svg; the committed PNG/ICO files are rasterizations of that source. The standalone page itself retains local image paths and no additional runtime dependency.

Exports: 16px, 32px, Apple touch 180px, Android 192px and 512px; ICO includes 16/32/48/64/128/256px. Render SVG at 1024px, then downsample with Lanczos. All outputs decode and match declared sizes. The icon intentionally uses no lettering so its three broad shapes remain identifiable at tab sizes.

2026-10-17 transparency correction: render the SVG on a transparent canvas (Chromium screenshot with omitBackground), then downsample with Pillow Lanczos. Preserve RGBA in every PNG and all six ICO frames. Rounded corners outside the navy tile have zero alpha; the tile and platform artwork remain opaque. Browser icon, touch icon, manifest, and manifest image URLs use version transparent-2 to refresh previous opaque exports.
