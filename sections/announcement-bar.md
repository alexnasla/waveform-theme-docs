# Announcement bar

A slim bar above the header for promotions, shipping notes, or launches. Supports an optional server-rendered countdown that is identical for every visitor.

> **Tip:** Keep it to one sentence; use **bold** for the part you want emphasized.

**File:** `sections/announcement-bar.liquid` · Fixed/system section (part of a template or section group).

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Text | `inline_richtext` | <strong>Launch Sale</strong> — 25% off everyt… | Bold text renders emphasized, matching the design. |
| Link | `url` |  |  |
| **Countdown** | | | |
| Show countdown timer | `checkbox` | off |  |
| Countdown end | `text` |  | Format: YYYY-MM-DD HH:MM (store timezone). The end time is rendered server-side, so it is consistent for every visitor. |
| Hide bar when countdown ends | `checkbox` | on |  |
| **Behavior** | | | |
| Show dismiss button | `checkbox` | on |  |
