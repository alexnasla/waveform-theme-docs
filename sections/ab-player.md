# A/B player

An A/B (or A/B/C) audio comparison player — shoppers toggle between two or three renders of the same passage while it plays, switching gaplessly. Reads its pairs from the product's `custom.audio_compares` metaobject metafield, or from manual URL blocks.

> **Tip:** Use identically-timed renders (e.g. dry vs. processed) so switching compares only the treatment — see the Metafields reference for the metaobject setup.

**File:** `sections/ab-player.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Eyebrow | `text` | Listen |  |
| Heading | `inline_richtext` | Compare it on real audio. |  |
| Subheading | `textarea` |  |  |
| Caption under player | `text` | Best on headphones or monitors |  |
| **Spacing & style** | | | |
| Top padding | `range` | 72 | 0–160 px. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Comparison (`compare`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Source name | `text` | Demo | Tab label, e.g. 'Lead vocal'. |
| Toggle A label | `text` | Dry |  |
| Toggle B label | `text` | With effect |  |
| Toggle C label | `text` |  | Optional third version. Leave blank for a 2-way A/B. |
| Audio A URL | `url` |  | Short loop (a few seconds). Upload under Content → Files, paste the URL. |
| Audio B URL | `url` |  | Same performance/length as A so they stay in sync. |
| Audio C URL | `url` |  | Optional. Same performance/length as A and B. Leave blank for a 2-way A/B. |

_Maximum blocks: 6_
