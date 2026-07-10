# Collection cards

Cards linking to collections, with image, title, and product count.

> **Tip:** Block image overrides the collection's own image; leave it empty to inherit.

**File:** `sections/collection-list.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Eyebrow | `text` |  |  |
| Heading | `text` |  |  |
| Columns | `range` | 3 | 2–4. |
| **Spacing & style** | | | |
| Content alignment | `select` | default | Options: Theme default / Left / Center. |
| Heading size | `select` | default | Options: Default / Small / Large / Extra large. |
| Top padding | `range` | 72 | 0–160 px. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Collection card (`collection`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Collection | `collection` |  |  |
| Kicker | `text` | Curated collection |  |
| Title | `text` |  | Leave empty to use the collection title. |
| Description | `textarea` |  |  |
| Link label | `text` | Discover |  |
| Corner label | `text` |  | Leave empty to show the collection's product count. |
| Image | `image_picker` |  | Leave empty to use the collection image. |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part of the image stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |

_Maximum blocks: 6_
