# Spec cards

System-requirements / spec cards with icon headers and label-value rows.

> **Tip:** Rows use `Label | Value`, one per line.

**File:** `sections/specs.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Eyebrow | `text` | Compatibility |  |
| Heading | `text` | System requirements |  |
| Top padding | `range` | 0 | 0–90 px. |
| **Spacing & style** | | | |
| Content alignment | `select` | default | Options: Theme default / Left / Center. |
| Heading size | `select` | default | Options: Default / Small / Large / Extra large. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Spec card (`card`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Icon | `select` | apple | Options: Apple / Windows / Chip / Utility / Document. |
| Heading | `text` | macOS |  |
| Rows | `textarea` | OS | macOS 11 Big Sur or later
CPU | Apple Si… | One row per line, label and value separated by \| (e.g. OS \| macOS 11 or later) |

_Maximum blocks: 4_
