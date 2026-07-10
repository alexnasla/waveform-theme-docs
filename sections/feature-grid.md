# Feature grid

An image-and-text feature grid (2–4 columns) with an eyebrow, heading, optional subtext, and a configurable image ratio — your global features at a glance.

> **Tip:** Keep every feature image the same aspect ratio so the grid stays even.

**File:** `sections/feature-grid.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Eyebrow | `text` | What's inside |  |
| Heading | `text` | Global features |  |
| Subheading | `textarea` |  | Optional short line under the heading. |
| Show divider under heading | `checkbox` | on |  |
| Columns | `range` | 3 | 2–4. |
| Image shape | `select` | 4 / 3 | Options: Landscape (4:3) / Wide (16:10) / Photo (3:2) / Square (1:1). |
| **Spacing & style** | | | |
| Top padding | `range` | 72 | 0–160 px. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Feature (`feature`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Image | `image_picker` |  | A screenshot of the control or UI. Looks best on a dark panel-style image. |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image). |
| Title | `text` | Feature |  |
| Description | `textarea` | Describe what this feature does and why it ma… |  |
| Link (optional) | `url` |  | Makes the whole card clickable. |

_Maximum blocks: 12_
