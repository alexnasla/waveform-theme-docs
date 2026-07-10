# Waveform's built-in metafields

Waveform reads a small set of product metafields automatically — no binding or code required.
All are optional; everything degrades gracefully when a field is empty.

Create the definitions once under **Settings → Custom data → Products → Add definition**, using
exactly these namespaces and keys:

| Namespace.key | Type | Used for |
| --- | --- | --- |
| `custom.subtitle` | Single line text | Subtitle on product cards and quick view |
| `custom.tagline` | Single line text | Short product tagline used in heroes and strips |
| `reviews.rating` | Decimal (or Rating) | Star rating on cards, product page, and SEO structured data |
| `reviews.rating_count` | Integer | Review count next to the stars; also feeds structured data |
| `custom.formats` | Single line text | Format chips, e.g. `VST3, AU, AAX` — product page, finder, compare |
| `custom.platforms` | Single line text | Platform chips, e.g. `macOS, Windows` |
| `custom.pitch` | Single line text | One-sentence pitch shown in the finder's results |
| `custom.has_trial` | Boolean | "Free trial" badge in finder/compare and product chips |
| `custom.bundle_products` | List of products | The contents of a bundle ([Bundles guide](bundles.md)) |
| `custom.version` | Single line text | Version badge in the product buy box, e.g. `v2.1` — [Product pages](product-pages.md) |
| `custom.headline` | Single line text | Overrides the product-hero headline in the buy box (falls back to the section's own setting) |
| `custom.headline_sub` | Single line text | Overrides the product-hero sub-headline / tagline in the buy box (falls back to the section's own setting) |
| `custom.audio_tracks` | List of `Audio track` metaobjects | Native-upload demo tracks for the [Audio player](sections/audio-player.md) section |
| `custom.audio_compares` | List of `Audio compare` metaobjects | A/B(/C) comparison pairs for the [A/B player](sections/ab-player.md) section |

## Metaobject metafields (audio player & A/B player)

Two of the audio sections read from **metaobject-list** metafields so you can upload audio with
Shopify's native file picker instead of pasting URLs. Create each metaobject definition once under
**Settings → Custom data → Metaobjects**, then add a product metafield (**Products → Add
definition**) of type *list of metaobject* pointing at it. Both are optional — each section falls
back to its manual URL blocks when the metafield is empty.

**`custom.audio_tracks`** — used by the [Audio player](sections/audio-player.md). Metaobject fields
the section reads:

| Field key | Type | Purpose |
| --- | --- | --- |
| `audio` | File | The audio file to play (MP3) |
| `label` | Single line text | The track name shown on the play button |
| `waveform` | Single line text | Optional pre-computed peaks; the player renders its bars from this |

**`custom.audio_compares`** — used by the [A/B player](sections/ab-player.md). Metaobject fields the
section reads:

| Field key | Type | Purpose |
| --- | --- | --- |
| `label_a` / `label_b` / `label_c` | Single line text | Version names on the toggle (default `A` / `B` / `C`) |
| `audio_a` / `audio_b` | File | Audio for versions A and B |
| `audio_c` | File | Audio for version C — optional; omit it (and `label_c`) for a 2-way A/B |

## Notes

- **Ratings power SEO.** `reviews.rating` + `reviews.rating_count` flow into the product's
  JSON-LD structured data, which is what makes star ratings eligible to appear in Google
  results. If you use a review app that writes to the standard `reviews` namespace, it plugs in
  with zero configuration; the built-in [reviews section](reviews.md) can also maintain these.
- **Fallbacks.** Formats/platforms chips fall back to the buy-box section settings when the
  product metafield is empty — set store-wide defaults there and override per product only when
  needed.
- **Beyond the built-ins**, any section setting can bind to any metafield you create — see
  [One template for many products](metafields-single-template.md).
