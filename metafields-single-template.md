# One template for many products: binding sections to metafields

There are two ways to give every product its own feature stories, images, and copy in Waveform:

1. **Alternate templates** — one product template per product, each customized visually in the
   theme editor. Best for catalogs of roughly 5–20 distinct products. This is the pattern the
   Waveform demo store uses, and it needs no setup beyond the editor itself: create the template
   (Theme editor → template picker → **Create template**), customize its sections, then assign it
   on the product's admin page under **Theme template**.

2. **One template + metafields (dynamic sources)** — a single product template whose section
   settings pull their content from each product's metafields. Best for larger catalogs, or when
   non-technical staff maintain product content from the product admin page rather than the theme
   editor. This article covers that workflow.

Both work out of the box. Dynamic sources are a Shopify platform feature: any Waveform setting of
an eligible type (single-line text, rich text, image, URL) shows a **connect dynamic source** icon
(⊕) in the theme editor whenever the section sits in a product template.

## Step 1 — Define the metafields

In Shopify admin go to **Settings → Custom data → Products → Add definition** and create one
definition per piece of per-product content. For a three-story feature layout like the demo's:

| Name | Namespace and key (suggested) | Type |
| --- | --- | --- |
| Story 1 heading | `custom.story_1_heading` | Single line text |
| Story 1 text | `custom.story_1_text` | Multi-line text |
| Story 1 image | `custom.story_1_image` | File (image) |
| Story 2 heading | `custom.story_2_heading` | Single line text |
| … | … | … |

Image settings can only bind to **File** type metafields. Text settings bind to single-line or
multi-line text; rich text settings bind to rich text metafields.

## Step 2 — Bind the section settings

1. Open the theme editor and switch to **Products → Default product** (the template you want to
   drive with metafields).
2. Select the **Feature story** section, then one of its story blocks.
3. Hover the **Heading** field and click the **⊕ dynamic source** icon that appears next to it.
4. Pick the metafield (e.g. *Story 1 heading*). The field now shows a token instead of literal
   text.
5. Repeat for the text, bullet list, and image settings, and for the other blocks — and for any
   other section you want to vary per product (Key features, testimonials quotes, the buybox
   editorial fields all support it).

The editor preview immediately renders the values from whichever product you're previewing.

## Step 3 — Fill the values per product

On each product's admin page, scroll to the **Metafields** section and fill in the fields. Anyone
who can edit products can now maintain page content — no theme editor access needed.

## Tips

- **Set fallbacks.** A bound setting renders empty when a product has no value. Either fill the
  metafield for every product, or keep a literal-content alternate template as the default and
  use the metafield-driven template only for the products that are ready.
- **Combine with Waveform's built-in metafields.** The theme already reads
  `custom.subtitle` (card subtitles), `reviews.rating` / `reviews.rating_count` (stars and
  JSON-LD), `custom.formats`, `custom.platforms`, `custom.pitch`, `custom.has_trial` (finder and
  compare pages), and `custom.bundle_products` (bundle contents). Those work everywhere
  automatically — dynamic sources are for the *editorial* content on top.
- **Mixing both patterns is fine.** The demo store uses alternate templates for its six products;
  a 60-product store might use one metafield-driven template for the long tail and alternate
  templates for two or three flagships.
