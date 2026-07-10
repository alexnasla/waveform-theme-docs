# Product page

System: the product page buy box — gallery, options, price, quantity, trust rows, sticky add-to-cart, back-in-stock, low-stock, app blocks.

> **Tip:** Most per-product selling content lives here; see the Product Pages guide.

**File:** `sections/main-product.liquid` · Fixed/system section (part of a template or section group).

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Showcase layout | `select` | split | Options: Split — classic two-column / Immersive — floating glass panel / Editorial — content rail + floating windows / Spotlight (product beside the pitch). |
| Buy box position (immersive) | `select` | center | Where the floating buy box sits over the hero image. Move it to wherever your image has open space so it doesn't cover the product; the darkening follows it for legibility. Options: Bottom left / Bottom center / Bottom right. |
| Hero media fit | `select` | cover | How the background image or video fills the Cinematic / Editorial hero. Options: Fill section (crop to fit) / Fit & center (show whole media) / Stretch to fill. |
| Hero media position | `select` | center | Which part of the image / video stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Hero media X | `range` | 50 | 0–100 %. |
| Hero media Y | `range` | 50 | 0–100 %. |
| Cinematic hero height | `range` | 0 | Height of the full-width cinematic hero only (the band with the product name, shown when 'Show cinematic hero' is on). 0 = automatic. Does not affect the showcase/buy area below. 0–100 vh. |
| Showcase height | `range` | 0 | Height of the showcase/buy area (Spotlight, Immersive, Editorial layouts). 0 = automatic. Independent of the cinematic hero above. 0–100 vh. |
| Show breadcrumb | `checkbox` | on |  |
| Show cinematic hero | `checkbox` | on | Full-width hero with the product name lockup above the buy area. |
| Hero background | `select` | product_image | What fills the full-width cinematic hero behind the product name. Options: Product image (default) / Custom image / Background video / No image — gradient only. |
| Custom hero image | `image_picker` |  | Used when Hero background is set to Custom image. |
| Hero background video | `video` |  | Used when Hero background is set to Background video. Plays muted, looped, no controls. |
| Show icon badge | `checkbox` | on | The small square badge shown next to the product name. |
| Custom icon badge | `image_picker` |  | Optional. Replaces the default badge icon in the cinematic hero and editorial layout. |
| Show large watermark | `checkbox` | on | The oversized product-name watermark behind the editorial layout. |
| Show scroll cue in hero | `checkbox` | on |  |
| Show product description in buy box | `checkbox` | on |  |
| **Sale countdown** | | | |
| Show sale countdown | `checkbox` | off |  |
| Sale end | `text` |  | Format: YYYY-MM-DD HH:MM. Rendered server-side — consistent for every visitor. |
| Countdown label | `text` | Sale ends in |  |
| **Variant picker display** | | | |
| Option 1 | `select` | button | Options: Buttons / Dropdown / Swatches / Image swatches. |
| Option 2 | `select` | swatch | Options: Buttons / Dropdown / Swatches / Image swatches. |
| Option 3 | `select` | button | Options: Buttons / Dropdown / Swatches / Image swatches. |
| **Free trial button** | | | |
| Label | `text` | Free trial |  |
| Link | `url` |  |  |
| **Formats & platforms** | | | |
| Formats | `text` | VST3, AU, AAX, Standalone | Comma-separated. |
| Platforms | `text` | macOS, Windows, Apple Silicon | Comma-separated. macOS/Windows/Apple Silicon get matching icons. |
| **Trust items** | | | |
| Item 1 | `text` | Instant digital delivery — download right aft… |  |
| Item 2 | `text` | Secure checkout · serial licence, no dongle |  |
| Item 3 | `text` | 14-day money-back guarantee |  |
| Item 4 | `text` | Free lifetime updates |  |
| **Featured review (split layout)** | | | |
| Quote | `textarea` |  |  |
| Author | `text` |  |  |
| Role | `text` | Verified buyer |  |
| Avatar | `image_picker` |  |  |
| **Editorial layout** | | | |
| Headline | `text` |  | Per-product override: metafield custom.headline. |
| Tagline | `textarea` |  | Per-product override: metafield custom.headline_sub. |
| Watermark subtitle | `text` |  |  |
| Social proof title | `text` |  |  |
| Social proof subtitle | `text` |  |  |
| Show quantity selector | `checkbox` | off | Off by default — single-licence digital products rarely need one. |
| Show back-in-stock signup when sold out | `checkbox` | on | Captures the shopper's email with the native contact form, tagged "back-in-stock" with the product and variant — use it to notify from Shopify Email or any connected tool. |
| Low-stock alert threshold | `range` | 0 | Shows "Only X left" when a tracked variant's stock is at or below this. 0 turns it off — it only ever uses real inventory. 0–20. |
| Gallery image ratio | `select` | 16 / 10 | Options: Landscape (16:10) / Standard (4:3) / Square / Portrait (4:5) / Wide (3:2). |

## App blocks

Supports app blocks — apps you install can add their widgets here.

## Block: Option value details (`option_value`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Option name | `text` |  | Must match the product option (e.g. "License"). |
| Value | `text` |  | Must match the option value (e.g. "Studio"). |
| Note | `text` |  |  |
| Tag | `text` |  |  |
| Show color swatch | `checkbox` | off |  |
| Swatch color | `color` | #4F8CFF |  |
| Image swatch | `image_picker` |  | Shown when the option's display style is "Image swatches". |

_Maximum blocks: 24_
