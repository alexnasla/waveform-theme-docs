# Testimonials

Quote cards with name, affiliation, and optional photo.

> **Tip:** Four cards on home, three on focused pages reads well.

**File:** `sections/testimonials.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Eyebrow | `text` | Trusted in real rooms |  |
| Heading | `text` | What producers say |  |
| Aggregate rating text | `text` | 4.9 average · 2,325 reviews |  |
| Show star ratings | `checkbox` | on | Turn off for endorsements/quotes from notable artists (no star rating). |
| **Spacing & style** | | | |
| Top padding | `range` | 72 | 0–160 px. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Testimonial (`testimonial`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Stars | `range` | 5 | 0–5. |
| Quote | `textarea` | “The detail in these instruments is unreal. I… |  |
| Name | `text` | Ava Mercer |  |
| Affiliation | `text` | Mix engineer · Resonant Studios |  |
| Credits label | `text` | Worked with | The small label above the credits line. Try 'Known for', 'Featured on', etc. Leave blank to hide it. |
| Credits | `text` |  | Notable names, releases, or work — e.g. Adele · Coldplay · Daft Punk. Shown as a credits line under the label above. |
| Photo | `image_picker` |  |  |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part stays in view when the photo is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |
| Image zoom | `range` | 100 | Zoom in to crop the image (e.g. trim empty space at the edges). Pair with Image position to frame it. 100–220 %. |
| Image shape | `select` | auto | Crops the photo box itself. Auto = default. Pick a wider/taller shape to reframe. Options: Auto (default) / Square (1:1) / Portrait (4:5) / Standard (4:3) / Photo (3:2) / Wide (16:10) / Widescreen (16:9). |

_Maximum blocks: 12_
