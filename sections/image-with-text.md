# Image with text

The workhorse split section: media on one side, heading/text/button on the other.

> **Tip:** Alternate `media_left` / `media_right` down a page for rhythm.

**File:** `sections/image-with-text.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Image | `image_picker` |  |  |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part of the image stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |
| Image zoom | `range` | 100 | Zoom in to crop the image (e.g. trim empty space at the edges). Pair with Image position to frame it. 100–220 %. |
| Image position | `select` | media_right | Options: Right / Left. |
| Eyebrow | `text` | Guided finder |  |
| Heading | `text` | Not sure where to start? |  |
| Text | `textarea` | Answer a few questions about your genre, DAW … |  |
| **Button** | | | |
| Button label | `text` | Find your sound |  |
| Button link | `url` |  |  |
| Button style | `select` | primary | Options: Primary / Secondary / Ghost. |
| Button icon | `select` | spark | Options: Spark / Play / Arrow / None. |
| **Style** | | | |
| Show accent glow | `checkbox` | on |  |
| Blend image edge | `checkbox` | on | Softly fades the image into the text panel. Turn off for a clean, hard edge. |
| Top padding | `range` | 0 | 0–90 px. |
| **Spacing & style** | | | |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |
