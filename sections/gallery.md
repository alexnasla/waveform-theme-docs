# Gallery

Image gallery in mosaic or uniform grid layout.

> **Tip:** Mosaic auto-arranges mixed aspect ratios; uniform crops everything to one ratio.

**File:** `sections/gallery.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Eyebrow | `text` |  |  |
| Heading | `text` |  |  |
| Layout | `select` | mosaic | Mosaic lets tiles span 2 rows or columns via each tile's Size setting. Options: Mosaic / Uniform. |
| Columns on desktop | `range` | 4 | 3–5. |
| Tile aspect (uniform layout) | `select` | landscape | Options: Landscape / Square / Portrait. |
| **Spacing & style** | | | |
| Content alignment | `select` | default | Options: Theme default / Left / Center. |
| Heading size | `select` | default | Options: Default / Small / Large / Extra large. |
| Top padding | `range` | 72 | 0–160 px. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Image (`image`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Image | `image_picker` |  |  |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part of the image stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |
| Size (mosaic layout) | `select` | auto | Options: Standard / Tall (2 rows) / Wide (2 columns). |

_Maximum blocks: 12_
