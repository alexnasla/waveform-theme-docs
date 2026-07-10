# License panel

Support-page panel explaining licensing terms with icon rows.

> **Tip:** Mirror your actual EULA terms — this is marketing copy, not the contract.

**File:** `sections/license-panel.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Heading | `text` | Licensing, in plain language |  |
| Subtext | `text` | One licence, every format, no dongles. |  |
| Button label | `text` | Read the full EULA |  |
| Button link | `url` |  |  |
| Footnote | `text` | Questions about a specific case? Just ask — w… |  |
| Top padding | `range` | 0 | 0–90 px. |
| **Spacing & style** | | | |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Item (`item`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Icon | `select` | check | Options: Check / Chip / Infinity / Shield / Refund / Bolt. |
| Title | `text` | 3 machines per licence |  |
| Text | `textarea` | Activate on up to three of your own computers… |  |

_Maximum blocks: 6_
