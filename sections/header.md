# Header

Site header: logo, 3-level mega menu, search, account, cart, and theme toggle.

> **Tip:** Mega menu category icons and link subtitles come from each linked collection's description — see Getting Started.

**File:** `sections/header.liquid` · Fixed/system section (part of a template or section group).

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Logo image | `image_picker` |  | Leave empty to show the store name with the brand mark, as designed. |
| Logo width | `range` | 140 | 60–300 px. |
| Show light/dark toggle | `checkbox` | on | Adds a sun/moon button to the header so visitors can switch between light and dark. Their choice is remembered on their device. |
| Menu | `link_list` | main-menu | Items with nested links open as a mega menu. Third-level links render as columned link cards with icons. |
| **Account menu link** | | | |
| Link label | `text` |  | Adds an extra item to the header account dropdown — e.g. a full-page customer-account app page like "My Licenses". Leave blank to hide. Only shows for signed-in customers. |
| Link subtitle | `text` |  |  |
| Account page URL or ID | `text` |  | Paste the app page's full URL from the customer accounts editor (…/account/pages/…), or just its page ID. Requires the label to be set too. |
| Icon | `select` | shield | Options: Shield / Scales / Star / Heart / Disc / Package. |

## Block: Mega menu feature (`mega_promo`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Menu item title | `text` |  | Must match a top-level menu item that has a dropdown (e.g. "Instruments"). |
| Tag | `text` | New release |  |
| Product | `product` |  |  |

_Maximum blocks: 6_
