# Hero banner

General-purpose hero with background image, heading, text, and buttons.

> **Tip:** For the tall animated product hero, use the Hero section instead.

**File:** `sections/hero-banner.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Background image | `image_picker` |  |  |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part of the image stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |
| Eyebrow | `text` | Now shipping |  |
| Heading | `text` | The sound of the next record. |  |
| Text | `textarea` | 40,000 producers build with Spectre. Start wi… |  |
| **Buttons** | | | |
| Primary button label | `text` | Shop now |  |
| Primary button link | `url` |  |  |
| Secondary button label | `text` | View bundles |  |
| Secondary button link | `url` |  |  |
| **Spacing & style** | | | |
| Top padding | `range` | 72 | 0–160 px. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |
