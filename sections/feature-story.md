# Feature story

Alternating image-and-text feature blocks — the main storytelling section on product pages.

> **Tip:** Three stories is the sweet spot; each block's checklist accepts one point per line.

**File:** `sections/feature-story.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Eyebrow | `text` |  |  |
| Heading | `text` |  |  |
| Layout | `select` | alternating | Alternating: image beside text, zig-zag down the page. Stacked: a single centered column with large media — a feature-spotlight look. Options: Alternating (image left / right) / Stacked (single column). |
| Space between rows | `range` | 0 | Tightens or loosens the gap between each story row. 0 = automatic (responsive default). 0–120 px. |
| Top padding | `range` | 0 | 0–90 px. |
| **Spacing & style** | | | |
| Content alignment | `select` | default | Options: Theme default / Left / Center. |
| Heading size | `select` | default | Options: Default / Small / Large / Extra large. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Story row (`story`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Image | `image_picker` |  |  |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part of the image stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |
| Image zoom | `range` | 100 | Zoom in to crop the image — e.g. to cut empty space at the top and bottom. Pair with Image position to frame it. 100–220 %. |
| Image shape | `select` | auto | Crops the image box itself. Auto = the layout default. Pick a wider shape (16:9, 21:9) to slice off empty top/bottom. Options: Auto (layout default) / Square (1:1) / Portrait (4:5) / Standard (4:3) / Photo (3:2) / Wide (16:10) / Widescreen (16:9) / Cinematic (21:9) / Banner (16:6) / Custom (crop sides). |
| Crop top | `range` | 0 | 0–80 %. |
| Crop right | `range` | 0 | 0–80 %. |
| Crop bottom | `range` | 0 | 0–80 %. |
| Crop left | `range` | 0 | 0–80 %. |
| Icon | `select` | spark | Options: None / Meter / Saturation / Spark / Wave / EQ / Dynamics / Reverb / Keys / Grain / Chip / Bolt / Shield / Envelope (dynamics) / Filter / Delay / echo / Stereo width / Mix / blend / Limiter / Phase / Tape / Spectrum / Knob / Power / bypass / Speaker. |
| Eyebrow | `text` | Feature |  |
| Heading | `text` | Louder, cleaner, without the squash. |  |
| Text | `textarea` |  |  |
| Checklist | `textarea` |  | One item per line. |

_Maximum blocks: 6_
