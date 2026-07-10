# Popup

Site-wide popup (newsletter or promo) with delay/exit triggers and per-visitor snooze.

> **Tip:** Disabled by default. Test with “show on next visit” — it remembers dismissals per browser.

**File:** `sections/popup.liquid` · Fixed/system section (part of a template or section group).

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Enable popup | `checkbox` | off | Shows once per visitor, then snoozes for the number of days below. Preview it by selecting this section in the editor. |
| Popup type | `select` | newsletter | Options: Newsletter signup / Promo / announcement. |
| Image | `image_picker` |  |  |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part of the image stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |
| Eyebrow | `text` | Join the studio |  |
| Heading | `text` | 10% off your first order |  |
| Text | `textarea` | New releases, free packs and production tips … |  |
| Button label | `text` |  | Promo mode only. |
| Button link | `url` |  |  |
| Dismiss link label | `text` | No thanks |  |
| **Behavior** | | | |
| Show after | `select` | delay | Options: A delay / Exit intent / Delay or exit intent. |
| Delay | `range` | 6 | 2–30 s. |
| Snooze after closing | `range` | 14 | Days before the popup can appear again for the same visitor. 1–90. |
| Show on mobile | `checkbox` | off |  |
