# Before / after

A draggable comparison slider between two images — ideal for dry/wet audio visuals, on/off states, or product transformations.

> **Tip:** Use two images with identical dimensions and framing so only the treatment changes.

**File:** `sections/before-after.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Eyebrow | `text` | See the difference |  |
| Heading | `text` | Before & after |  |
| Text | `textarea` | Drag the handle to compare two images — ideal… |  |
| Before image | `image_picker` |  |  |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part of the image stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |
| After image | `image_picker` |  |  |
| Before label | `text` | Before |  |
| After label | `text` | After |  |
| Starting position | `range` | 50 | 10–90 %. |
| **Spacing & style** | | | |
| Content alignment | `select` | default | Options: Theme default / Left / Center. |
| Heading size | `select` | default | Options: Default / Small / Large / Extra large. |
| Top padding | `range` | 72 | 0–160 px. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |
