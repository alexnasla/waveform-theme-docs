# Video

Click-to-play video with poster image — Shopify-hosted, YouTube, or Vimeo.

> **Tip:** Loads as a lightweight facade; the player only loads on click, keeping pages fast.

**File:** `sections/video.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Cover image | `image_picker` |  |  |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part of the image stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |
| Shopify-hosted video | `video` |  |  |
| Or external video | `video_url` |  | Used when no Shopify-hosted video is selected. |
| Caption | `text` | Watch · 2 min |  |
| Heading | `text` | Inside the Master Chain |  |
| Video ratio | `select` | 16 / 9 | Options: Cinematic (16:7) / Widescreen (16:9) / Ultrawide (21:9) / Square. |
| **Spacing & style** | | | |
| Top padding | `range` | 72 | 0–160 px. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |
