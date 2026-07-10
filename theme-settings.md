# Theme settings reference

Global settings under **Theme editor → Theme settings**. These apply storewide; section settings override them where both exist.

## Colors

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Color mode | `select` | dark | Options: Dark / Light / Auto (match visitor's system). |
| Accent | `select` | blue | Options: Spectre Blue / Synth Violet / Halo Cyan / Custom. |
| Custom accent | `color` | #4F8CFF | Used when Accent is set to Custom. |
| Custom accent gradient end | `color` | #8A5CF6 |  |

## Typography

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Theme style | `select` | studio | Switches the display typeface, corner radii and section rhythm together. Options: Studio — refined, soft / Editorial — airy, rounded / Brutalist — sharp, dense. |
| **Custom fonts** | | | |
| Use custom fonts | `checkbox` | off | Overrides the bundled theme fonts with fonts from the Shopify library. |
| Heading font | `font_picker` | assistant_n4 |  |
| Body font | `font_picker` | assistant_n4 |  |

## Social media

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Instagram | `url` |  |  |
| YouTube | `url` |  |  |
| Discord | `url` |  |  |
| TikTok | `url` |  |  |
| Facebook | `url` |  |  |
| Reddit | `url` |  |  |

## Favicon

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Favicon image | `image_picker` |  | Will be scaled down to 32 x 32px |

## Search engine listing

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Fallback meta description | `textarea` |  | Used on pages without their own description (set those under each resource's search engine listing, and the homepage's under Online Store > Preferences). |
| Social sharing image | `image_picker` |  | Shown when pages without their own image are shared on social networks. 1200 × 628px recommended. |

## Cart & checkout

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Limit each product to one per cart | `checkbox` | off | For licences and digital goods. Re-adding an item shows "already in your cart" instead of increasing the quantity, and hides the quantity stepper on the cart page. |
| Show dynamic checkout buttons | `checkbox` | on | The accelerated "Buy with Shop" / Shop Pay button on product pages, next to Add to cart. Turn off to show only the standard button. (Cart express-checkout buttons aren't affected.) |
| Show Add to cart button | `checkbox` | on | Turn off for a fast-buy layout that goes straight to checkout (Buy now / Buy with Shop only). |

## Product cards

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Card image ratio | `select` | 16 / 11 | Shape of product images on collection, featured, and search cards (store-wide). Options: Wide (16:11) / Landscape (4:3) / Square / Portrait (3:4) / Cinematic (16:10). |

## Animations

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Enable scroll animations | `checkbox` | on | Fade and slide sections in as they enter the viewport. Honors reduced-motion preferences. |
| Show back-to-top button | `checkbox` | on | A floating button that appears after scrolling and returns to the top of the page. |

## Speed

Performance features, on by default. Prefetch loads the next page in the background the moment a
shopper hovers, focuses, or taps a link, so clicks feel instant — same-origin pages only, and it
backs off automatically on Save-Data or slow connections.

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Prefetch pages on hover | `checkbox` | on | Preloads the next page on hover / focus / press. |
| Smooth page transitions | `checkbox` | on | Cross-fade between pages as shoppers navigate (supported browsers only). Automatically disabled for visitors who prefer reduced motion. |
| Faster rendering of long pages | `checkbox` | on | Skip rendering off-screen sections until they scroll into view, speeding up first paint on long pages. |
