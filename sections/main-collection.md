# Collection

System: collection page with live filters, sort, density toggle, and promo tiles.

> **Tip:** Filters come from Shopify's Search & Discovery configuration.

**File:** `sections/main-collection.liquid` · Fixed/system section (part of a template or section group).

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Show breadcrumb | `checkbox` | on |  |
| **Hero banner** | | | |
| Show hero banner | `checkbox` | on |  |
| Eyebrow | `text` | The catalogue |  |
| Heading | `inline_richtext` |  | Leave empty to use the collection title. Italics render in the accent gradient. |
| Hero image | `image_picker` |  | Leave empty to use the collection image. |
| Image fit | `select` | cover | Options: Fill (crop to fit) / Fit (show whole image) / Stretch. |
| Image position | `select` | center | Which part of the image stays in view when it is cropped. Options: Center / Top / Bottom / Left / Right / Top left / Top right / Bottom left / Bottom right / Custom (X / Y). |
| Custom X | `range` | 50 | 0–100 %. |
| Custom Y | `range` | 50 | 0–100 %. |
| Show product-count chip | `checkbox` | on |  |
| **Filtering & sorting** | | | |
| Filter layout | `select` | sidebar | Configure which filters appear in the Search & Discovery app. Options: Sidebar / Drawer / Hidden. |
| **Pagination** | | | |
| Products per page | `range` | 9 | 6–24. |
| Pagination | `select` | load_more | Options: Load more with progress / Numbered pages. |
| **Spacing & style** | | | |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Hero stat chip (`stat`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Value | `text` | 4.8 ★ |  |
| Label | `text` | rated |  |

## Block: Promo tile (`promo`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Eyebrow | `text` | Bundle & save |  |
| Heading | `text` | The whole rack, one price. |  |
| Text | `textarea` | Every instrument and plugin in a single bundl… |  |
| Button label | `text` | See bundles |  |
| Link | `url` |  |  |
| Grid position | `range` | 5 | 2–12. |

_Maximum blocks: 6_
