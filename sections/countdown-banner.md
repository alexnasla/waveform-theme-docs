# Countdown banner

Full-width banner with a server-anchored countdown — safe for launches because every visitor sees the same time.

> **Tip:** Pair with an automatic discount so the urgency is real.

**File:** `sections/countdown-banner.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Heading | `text` | Launch Sale ends soon |  |
| Text | `textarea` | 25% off the entire catalogue — auto-applied a… |  |
| Countdown end | `text` |  | Format: YYYY-MM-DD HH:MM (store timezone). The end time is rendered server-side, so it is consistent for every visitor. |
| Hide section when countdown ends | `checkbox` | on |  |
| **Button** | | | |
| Button label | `text` | Shop the sale |  |
| Button link | `url` |  |  |
| **Spacing & style** | | | |
| Top padding | `range` | 72 | 0–160 px. |
| Bottom padding | `range` | 72 | 0–160 px. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |
