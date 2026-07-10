# Map / store info

A stylized location section with image and address card.

> **Tip:** Use a map screenshot or the bundled artwork style; no API key needed.

**File:** `sections/map.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Heading | `text` | Visit the studio |  |
| Address | `text` | 148 Warehouse Lane, Brooklyn, NY 11201 |  |
| Hours | `text` | Mon–Fri 10–6 · Sat 12–4 · Sun closed |  |
| Phone | `text` | (555) 240-1180 |  |
| **Map** | | | |
| Map embed URL | `text` |  | Paste a Google Maps embed URL (Share → Embed a map → copy the iframe src). Leave blank for the decorative grid. |
| Or static map image | `image_picker` |  |  |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part of the image stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |
| **Button** | | | |
| Button label | `text` | Get directions |  |
| Button link | `url` |  |  |
| **Spacing & style** | | | |
| Top padding | `range` | 72 | 0–160 px. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |
