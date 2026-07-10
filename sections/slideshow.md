# Slideshow

Full-bleed image slideshow with per-slide text and buttons, autoplay optional.

> **Tip:** Autoplay pauses for reduced-motion visitors and when the tab is hidden.

**File:** `sections/slideshow.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Auto-rotate slides | `checkbox` | on |  |
| Change slides every | `range` | 5 | 3–9 s. |
| **Spacing & style** | | | |
| Top padding | `range` | 72 | 0–160 px. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Slide (`slide`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Image | `image_picker` |  |  |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part of the image stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |
| Eyebrow | `text` | New release |  |
| Heading | `text` | Slide heading |  |
| Text | `textarea` |  |  |
| Button label | `text` | Shop now |  |
| Button link | `url` |  |  |

_Maximum blocks: 6_
