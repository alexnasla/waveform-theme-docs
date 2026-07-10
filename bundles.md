# Bundles

Waveform ships a complete bundle system — a bundles collection page and a dedicated bundle
product page — with honest savings math and no app required.

## How it works

A bundle is a normal Shopify product whose **contents** are declared in a metafield. The theme
renders the included products, computes the value comparison, and shows savings in three styles.

## Setup (one-time)

1. Create the metafield definition: **Settings → Custom data → Products → Add definition** —
   name "Bundle products", namespace and key `custom.bundle_products`, type **List of
   products**.

## Per bundle

1. **Create the product** (e.g. "Master Chain"). Set its price, and set **compare-at price to
   the exact sum of the included products' prices** — every savings number the theme shows is
   derived from this, so the math stays honest.
2. In the product's **Metafields**, fill `Bundle products` with the included products.
3. Set the product's **Theme template** to `bundle`.
4. Add it to your Bundles collection.

## The bundles collection page

Assign the `bundles` template to your Bundles collection. Its grid offers three savings
displays — badge ("Save 30%"), bar, or full price breakdown — plus grid/list layouts and a
featured-bundle strip.

## Tips

- The bundle page's "what's inside" grid links each included product to its own page — make sure
  those pages are polished first.
- A small catalog usually supports 2–4 bundles: a flagship "everything" bundle plus one or two
  themed sets.
- Per-bundle templates work exactly like per-product ones — the demo store gives each bundle its
  own template with its own imagery.

> **Note:** these are merchandising bundles — buying one delivers the bundle product itself. For
> digital products this is usually what you want (one license covering the set). If you need
> component-level fulfillment, pair the same metafield with Shopify Bundles or an app.
