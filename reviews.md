# Product reviews

Waveform includes native product reviews stored as Shopify **metaobjects** — no review app, no
external scripts, fully yours. Submissions are moderated: nothing appears until you approve it
by creating the entry.

## One-time setup

1. **Settings → Custom data → Metaobjects → Add definition.**
2. Name: `Waveform review`, type: `waveform_review` (the type string matters — the theme reads
   this exact type. Don't use `product_review`; Shopify reserves it).
3. Add fields with these keys:

| Field | Key | Type |
| --- | --- | --- |
| Product | `product` | Product reference |
| Author | `author` | Single line text |
| Rating | `rating` | Integer (1–5) |
| Title | `title` | Single line text |
| Body | `body` | Multi-line text |
| Review date | `review_date` | Date |
| Verified | `verified` | Boolean |

4. Under the definition's **Storefronts** option, enable storefront access (the theme reads the
   entries through the storefront — without this they stay invisible).

## How reviews flow

1. A customer submits the review form on a product page. It arrives in your inbox via the native
   contact form, tagged `product-review`, with the product, rating, and text.
2. You approve by creating a `Waveform review` metaobject entry with those values (**Content →
   Metaobjects → Waveform review → Add entry**).
3. The entry appears on that product's page immediately.

## Ratings and SEO

The reviews section prefers the product's `reviews.rating` / `reviews.rating_count` metafields
for the aggregate line (so it agrees with your cards and structured data), falling back to an
average computed from entries. Keep the metafields updated as reviews accumulate — they're what
makes stars eligible to show in Google results.

## Tips

- Seed each product with 2–3 genuine early reviews (beta testers count — mark them verified).
- The section shows a handful by default with a "show all" expander — no pagination to manage.
