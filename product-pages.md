# Product pages

The product template is where Waveform earns its keep. This guide covers the buy box, giving
each product its own content, variant presentation, and the stock/scarcity features.

## Anatomy of the default template

In order: **Product hero** (full-bleed showcase with your product image), **buy box** (gallery,
options, price, quantity, trust rows, review quote, sticky add-to-cart), **Feature story** ×3,
**Key features**, **Specs**, **Testimonials**, **Compare strip**, **Things to know** (accordions +
release notes), **Product reviews**, **Recommended**, **Recently viewed**.

Every piece is a section or block — add, remove, and reorder freely per template.

## One template per product (recommended for ≤ ~20 products)

1. In the theme editor's template picker choose **Products → Create template**, name it after the
   product (e.g. `halo`), based on the default product template.
2. Customize its sections — stories, features, quotes, release notes, buy-box editorial copy.
3. On the product's admin page, set **Theme template** to the new template.

The Waveform demo store does exactly this for every product — open its templates in the editor to
see worked examples. For larger catalogs, bind one template to metafields instead:
[One template for many products](metafields-single-template.md).

## Buy box settings worth knowing

- **Layout** — three showcase layouts via the section's Layout setting.
- **Editorial hero copy** — headline, tagline, social-proof lines shown in the hero. These are
  template-level settings, so they pair naturally with per-product templates.
- **Formats / platforms chips** — set per-product via metafields, with template-level fallbacks.
- **Trust rows** — four lines for delivery/guarantee/updates promises.
- **Quantity stepper** — off by default (most software is qty 1); enable for merch.
- **App blocks** — the buy box accepts app blocks, so review/upsell apps can inject widgets
  without code.

## Variant options

Waveform renders each product option as buttons, dropdowns, or swatches (per-option display
settings), enriched by **Option value** blocks in the buy-box section:

- **Note** — a small caption under the value (e.g. "5 seats" under a Studio license).
- **Tag** — a badge like "Popular".
- **Color swatch** — hex color for the value.
- **Image swatch** — set a swatch image and switch the option's display to image swatches.

Sold-out variant combinations are greyed out automatically. If a variant has its own image, the
gallery swaps to it on selection.

## Scarcity and recovery features

- **Low-stock indicator** — shows "Only N left" when inventory falls at or below your threshold.
  Requires Shopify inventory tracking ON and "continue selling when out of stock" OFF for the
  variant.
- **Back-in-stock form** — replaces the add-to-cart for sold-out variants; captures email via the
  native contact form (submissions arrive tagged `back-in-stock` with product + variant).
- **Sale countdown** — optional per-template countdown in the buy box, server-anchored so every
  visitor sees the same deadline.

## Release notes ("What's new")

The **Things to know** section's release blocks render a version history — version, date, and
one-note-per-line. Keep this current; software buyers read it as a sign of life.
