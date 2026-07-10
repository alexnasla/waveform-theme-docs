# Downloads hero

Downloads page hero with OS detection and a featured release with per-OS download buttons.

> **Tip:** Set both macOS and Windows URLs; the visitor's OS is preselected.

**File:** `sections/downloads-hero.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Eyebrow | `text` | Download Center |  |
| Heading | `inline_richtext` | Get set up <em>in minutes.</em> | Italicized text renders in the accent gradient. |
| Text | `textarea` | Every plugin and instrument installer, free d… |  |
| Show detected-OS pill | `checkbox` | on |  |
| Stat chip 1 | `text` | VST3 · AU · AAX · Standalone |  |
| Stat chip 2 | `text` | Lifetime updates included |  |
| **Featured release** | | | |
| Show featured release card | `checkbox` | on |  |
| Image | `image_picker` |  |  |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part of the image stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |
| Image chip label | `text` | Mastering Maximizer |  |
| Image chip icon | `select` | meter | Options: Meter / Grain / Keys / Wave / Saturation / Reverb / Spark. |
| Tag | `text` | Latest release |  |
| Title | `text` | Apex |  |
| Description | `richtext` | <p>Our flagship mastering maximizer, freshly … |  |
| Version | `text` | 2.0.1 |  |
| Released | `text` | May 30, 2026 |  |
| Size (macOS) | `text` | 54 MB |  |
| Size (Windows) | `text` | 52 MB |  |
| Formats | `text` | VST3 · AU · AAX |  |
| macOS installer URL | `url` |  | Upload installers under Content → Files and paste the URL. Without one the button shows a demo toast. |
| Windows installer URL | `url` |  |  |
| Note | `text` | Signed & notarised · macOS 11+ / Windows 10+ … |  |
