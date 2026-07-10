# Cart drawer

The slide-out cart. Includes the free-shipping goal bar and a recommendations upsell rail.

> **Tip:** The upsell rail recommends complements of the newest cart item automatically — no setup needed.

**File:** `sections/cart-drawer.liquid` · Fixed/system section (part of a template or section group).

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| **Reward progress bar** | | | |
| Show reward progress bar | `checkbox` | off |  |
| Spend threshold | `number` | 250 | In your store currency. Create the matching automatic discount or free gift in Shopify admin. |
| Progress text | `text` | Spend [amount] more to unlock a free gift | [amount] is replaced with the remaining spend. |
| Unlocked text | `text` | Free gift unlocked! Added at checkout. |  |
| Show "pairs well with" suggestions | `checkbox` | on | Complementary products from Shopify recommendations, excluding what's already in the cart. Set complements per product under Search & Discovery for best results. |
| **Footer** | | | |
| Delivery line | `text` | Instant · free |  |
| Trust item 1 | `text` | Instant delivery |  |
| Trust item 2 | `text` | 14-day refund |  |
