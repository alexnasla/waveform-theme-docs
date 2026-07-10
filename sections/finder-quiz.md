# Finder quiz

The product-finder quiz: four questions whose answers score products by tag matches.

> **Tip:** Each answer block lists `match_tags`; products carrying those tags score higher. See the Finder guide.

**File:** `sections/finder-quiz.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| **Matches are scored by overlap between each chosen option's "match tags" and the product's tags. Per-product formats, platforms and pitch come from custom.formats, custom.platforms and custom.pitch metafields (with fallbacks).** | | | |
| Eyebrow | `text` | Guided finder |  |
| Heading | `text` | Which tools are right for you? |  |
| Text | `textarea` | No email, no sign-up. Just four questions and… |  |
| Products to match | `collection` |  | Defaults to all products. Bundles are excluded automatically. |
| Bundles to recommend | `collection` |  |  |
| Runner-up matches shown | `select` | 3 | Options: 3 / 4 / 6. |
| Default formats | `text` | VST3, AU, AAX |  |
| Default platforms | `text` | macOS, Windows |  |
| **Question 1** | | | |
| Title | `text` | What are you making? |  |
| Subtitle | `text` | Pick the closest fit — we tune the matches to… |  |
| Icon | `select` | disc | Options: Disc / Target / Wrench / Scales / Keys / Meter. |
| **Question 2** | | | |
| Title | `text` | Where do you need the most help? |  |
| Subtitle | `text` | What would move your tracks forward right now? |  |
| Icon | `select` | target | Options: Disc / Target / Wrench / Scales / Keys / Meter. |
| **Question 3** | | | |
| Title | `text` | What do you produce in? |  |
| Subtitle | `text` | So we only show formats that load in your setup. |  |
| Icon | `select` | util | Options: Disc / Target / Wrench / Scales / Keys / Meter. |
| **Question 4** | | | |
| Title | `text` | How much are you looking to take on? |  |
| Subtitle | `text` | We'll size the recommendation to match. |  |
| Icon | `select` | scales | Options: Disc / Target / Wrench / Scales / Keys / Meter. |
| **Spacing & style** | | | |
| Content alignment | `select` | default | Options: Theme default / Left / Center. |
| Heading size | `select` | default | Options: Default / Small / Large / Extra large. |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Answer option (`option`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Belongs to question | `select` | q1 | Options: Question 1 / Question 2 / Question 3 / Question 4. |
| Title | `text` | Option |  |
| Description | `text` |  |  |
| Icon | `select` | spark | Options: Wave / Bolt / Orchestra / Keys / Grain / Drum / Sliders / Meter / Reverb / Layers / Disc / Apple / Wrench / Target / Spark / Infinity. |
| Match tags | `text` |  | Comma-separated product tags this answer rewards, e.g. "mastering, mixing". |
| Preferred format | `text` |  | Products offering this format score higher, e.g. "AAX". |
| Demote products missing the format | `checkbox` | off |  |
| Match weight | `range` | 3 | 1–5. |
| Bundle recommendation | `select` | none | Options: No effect / Suggest a bundle / Suggest the complete bundle. |

_Maximum blocks: 24_
