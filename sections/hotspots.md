# Image hotspots

An image with positioned, clickable hotspots that open product popovers.

> **Tip:** Use a product UI screenshot and pin hotspots to its features — instant interactive tour.

**File:** `sections/hotspots.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Eyebrow | `text` | Shop the setup |  |
| Heading | `text` | Everything in this rack |  |
| Image | `image_picker` |  |  |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part of the image stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |
| Hotspot dot size | `range` | 30 | Size of the + markers. They scale down automatically on mobile. 18–44 px. |
| Device frame | `select` | none | Show the image inside a device mockup. Hotspots stay aligned to the screen. Use a 16:10 image for the cleanest fit. Options: None / MacBook Pro 16". |
| **Spacing & style** | | | |
| Content alignment | `select` | default | Options: Theme default / Left / Center. |
| Heading size | `select` | default | Options: Default / Small / Large / Extra large. |
| Top padding | `range` | 72 | 0–160 px. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Hotspot (`hotspot`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Horizontal position | `range` | 50 | 2–98 %. |
| Vertical position | `range` | 50 | 2–98 %. |
| Custom title | `text` | Hotspot |  |
| Description | `textarea` |  | Shown in the popup on hover / tap. Use it to explain a feature or control. |
| **Make it shoppable (optional)** | | | |
| Product | `product` |  | Fills the popup with the product's title, price and link. |
| Custom price text | `text` |  |  |
| Custom link | `url` |  |  |

_Maximum blocks: 8_
