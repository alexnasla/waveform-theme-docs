# Styles, colors, and dark mode

## Color schemes

Waveform ships dark-first with a complete light mode. Under **Theme settings → Colors**:

- **Dark** — the signature look.
- **Light** — full light treatment; every section is tuned for it, including glass overlays and
  media scrims.
- **Auto** — follows each visitor's operating-system preference and switches live if the visitor
  changes it. The choice is applied before first paint, so there's no flash.

Visitors can also toggle the scheme from the header; their choice is remembered per browser.

## Accents

The accent color drives buttons, links, focus rings, gradient text, glows, and active states
storewide. Three accent presets ship with the theme; any custom color works. Pick something with
good contrast against both your dark and light backgrounds if you use Auto.

## Style presets

Three complete presets (colors + typography + corner radii) are available as starting points.
Applying a preset overwrites your color/typography settings — do it before fine-tuning, not
after.

## Typography

The bundled variable fonts are self-hosted from your store's CDN — no Google Fonts request, no
layout shift, fast first paint. You can switch either family to any font in Shopify's font
library; expect a small performance cost with non-bundled fonts.

## Gradient emphasis

Headings across the theme support `<em>` emphasis rendered as the accent gradient. In any
rich-text or heading field, wrap the words to highlight: `Engineer the <em>sound</em>`.

## Image guidance

- Product/gallery images: 2000–3200px wide, JPEG for photos and art, PNG for UI screenshots.
- The theme requests responsive sizes automatically — upload one large original and let the CDN
  do the rest.
- Logos for the logo-list: transparent PNG/SVG, mid-gray monochrome works in both schemes.
