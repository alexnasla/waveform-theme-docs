# Downloads list

The product-installers list with OS toggle, search, and per-release changelogs.

> **Tip:** Changelog format: `vX.Y.Z | date` then `- note` lines; `**bold**` works in notes.

**File:** `sections/downloads-list.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Heading | `text` | Product installers |  |
| **Spacing & style** | | | |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Installer (`installer`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Name | `text` | Plugin name |  |
| Category line | `text` | Plugin · Effect |  |
| Filter group | `select` | plugin | Options: Instrument / Plugin / Other. |
| Badge | `select` | none | Options: None / Free / Demo. |
| Icon | `select` | spark | Options: Grain / Wave / Keys / Meter / Saturation / Reverb / Dynamics / EQ / Utility / Gift / Drum / Orchestra / Chip / Spark. |
| Formats (comma-separated) | `text` | VST3, AU, AAX |  |
| Version | `text` | 1.0.0 |  |
| Size (macOS) | `text` | 50 MB |  |
| Size (Windows) | `text` |  |  |
| Updated | `text` | May 2026 |  |
| macOS installer URL | `url` |  |  |
| Windows installer URL | `url` |  |  |
| Changelog | `textarea` |  | Start a release with "v1.2.0 \| May 28, 2026", then one "- note" per line. Wrap words in **stars** for emphasis. |

_Maximum blocks: 30_
