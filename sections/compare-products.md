# Compare products

Side-by-side product comparison table with type tabs and up to four products, remembered per visitor.

> **Tip:** Feed the spec rows from product metafields (`custom.formats`, `custom.platforms`, etc.) for consistency.

**File:** `sections/compare-products.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Eyebrow | `text` | Side by side |  |
| Heading | `text` | Compare the range |  |
| Text | `textarea` | Add up to four products and see price, format… |  |
| Products | `collection` |  | Defaults to all products. |
| Default formats | `text` | VST3, AU, AAX |  |
| Default platforms | `text` | macOS, Windows |  |
| **Spacing & style** | | | |
| Content alignment | `select` | default | Options: Theme default / Left / Center. |
| Heading size | `select` | default | Options: Default / Small / Large / Extra large. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |
