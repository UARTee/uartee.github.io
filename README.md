# UARTee website

Public website for UARTee, an independent hardware project building a dual
USB-to-UART adapter with Dual, Share, and Tap connection modes.

The site is a lightweight coming-soon page built with plain HTML, CSS, and
original SVG artwork. It has no build step, framework, external fonts, analytics,
or runtime package dependency.

## Local preview

Open `index.html` directly, or serve the directory locally:

```bash
python3 -m http.server 8080 --bind 127.0.0.1
```

Open `http://127.0.0.1:8080`. Run the command from this repository.

## Content

- `index.html`: copy, sections and links.
- `styles.css`: responsive layout and colors.
- `assets/uartee-mark.svg`: original branching-signal brand mark and favicon.
- `assets/serial-paths.svg`: original conceptual hero illustration, not a
  representation of the final PCB or enclosure.
- `assets/brand/avatar.png` (512x512): GitHub organization avatar.
- `assets/brand/social-preview.png` (1280x640): repository social preview.
  Editable sources are the matching `.svg` files.

Orange: `#E65324`. Charcoal: `#232521`. Paper: `#FAF9F6`.
The darker orange `#B83C15` is used for small colored text and interactions.

The page deliberately avoids unverified voltage, baud-rate, price, licensing,
availability and launch-date claims. Review all product copy before publishing.
Links point only to the existing GitHub organization, not future repositories.

All website assets use relative paths. Review product wording and availability
claims before publishing an update.

For GitHub Pages organization sites, publish from the root of the `main` branch
of the `UARTee/uartee.github.io` repository.
