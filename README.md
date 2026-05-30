# ultramcu.github.io

The landing page for **ULTRA·MCU** → <https://ultramcu.github.io/>

A single, hand-written `index.html` — a `$ make all` build-log that lists every
open-source project (Dart/Flutter on pub.dev, Go on pkg.go.dev, embedded C
firmware, research artifacts, and upstreamed fixes), with links to the two live
Flutter web demos.

- **Black & white, terminal/boot-log theme.**
- **Zero dependencies** — no framework, no CDN, no build step, no web fonts.
- **Works with JavaScript off** (all content is in the HTML; JS only adds a
  build-log reveal animation, which also respects `prefers-reduced-motion`).
- Responsive and keyboard-navigable.

Project demos live at their own sub-paths (e.g.
`/thai_promptpay_flutter.dart/`, `/thai_provinces_flutter.dart/`) and are
unaffected by this root page.
