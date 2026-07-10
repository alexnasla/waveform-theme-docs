# Things to know

Product-page accordion for licensing, installation, refunds, and a release changelog.

> **Tip:** Release blocks render the “What's new” version history.

**File:** `sections/things-to-know.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Eyebrow | `text` | Digital product |  |
| Heading | `text` | Things to know |  |
| Changelog heading | `text` | What's new |  |
| Top padding | `range` | 0 | 0–90 px. |
| **Spacing & style** | | | |
| Content alignment | `select` | default | Options: Theme default / Left / Center. |
| Heading size | `select` | default | Options: Default / Small / Large / Extra large. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Accordion row (`accordion`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Icon | `select` | doc | Options: Document / Bolt / Refund / Shield / Scales / Support / Gift. |
| Heading | `text` | Licensing & EULA |  |
| Content | `richtext` | <p>Describe your licensing, installation or s… |  |
| Open by default | `checkbox` | off |  |

## Block: Changelog release (`release`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Version | `text` | v2.1.0 |  |
| Date | `text` | May 2026 |  |
| Notes | `textarea` |  | One item per line. |

_Maximum blocks: 12_
