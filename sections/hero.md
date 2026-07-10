# Hero

The animated homepage hero with gradient-emphasis heading, stat chips, and product cards.

> **Tip:** Wrap one heading phrase in `<em>` to give it the accent gradient.

**File:** `sections/hero.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Eyebrow | `text` | Pro audio software · Instruments · Plugins · … |  |
| Heading | `inline_richtext` | Engineer the sound <em>in your head.</em> | Italicized text renders in the accent gradient. |
| Subtext | `textarea` | Studio-grade instruments and plugins, built f… |  |
| **Background image** | | | |
| Background image | `image_picker` |  | Optional. Sits behind the hero text with a dark overlay so the copy stays legible. |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part of the image stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |
| Image zoom | `range` | 100 | Zoom in to crop the image (e.g. trim empty space at the edges). Pair with Image position to frame it. 100–220 %. |
| Image darken | `range` | 65 | 0–90 %. |
| Primary button label | `text` | Explore the catalog |  |
| Primary button link | `url` |  |  |
| Secondary button label | `text` | Watch the film |  |
| Secondary button link | `url` |  |  |
| **Trust row** | | | |
| Trust text | `text` | 4.9 from 2,325 producers worldwide | Leave empty to hide the stars row. |
| **Style** | | | |
| Show accent glow | `checkbox` | on |  |
