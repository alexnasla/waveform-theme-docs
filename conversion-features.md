# Conversion features

Waveform builds in the features merchants usually install apps for. Everything below ships with
the theme; each is independent and most are opt-in.

## Cart

- **Free-shipping / gift goal bar** — a progress bar in the cart drawer and on the cart page that
  nudges shoppers toward a spend threshold. **Off by default.** See *How the gift goal bar works*
  below — it pairs with a Shopify discount.
- **One per cart (licences / digital goods)** — optional setting that caps every product at one per
  cart: re-adding shows "already in your cart" instead of increasing the quantity, and the cart-page
  quantity stepper is hidden. Theme settings → **Cart & checkout** → "Limit each product to one per
  cart." Off by default; turn it on for plugin/licence stores.
- **Drawer upsell rail** — the cart drawer recommends complements of the most recently added
  item (Shopify's recommendations API), excluding what's already in the cart, with one-tap add.
  Automatic.
- **Save for later & promo capture** — on the cart page.

### How the free-shipping / gift goal bar works

The goal bar is a **visual nudge only** — it shows progress toward a spend threshold and a message,
but it does **not** grant anything by itself. You set it up in two independent places:

1. **The theme (the message + progress)** — Theme editor → **Cart drawer** section:
   - **Show gift progress** — turn it on (it's off by default).
   - **Gift threshold** — the cart subtotal that "unlocks" the reward, e.g. `150`.
   - **Progress text** — shown while the shopper is under the threshold; use `[amount]` for the
     remaining amount, e.g. `Spend [amount] more to unlock free shipping`.
   - **Unlocked text** — shown once they cross it, e.g. `Free shipping unlocked!`.
2. **Shopify (the actual reward)** — create a matching **automatic discount** under **Discounts**,
   e.g. "free shipping on orders over $150," or a Buy X Get Y discount that adds a free product when
   the cart reaches $Y. The theme bar *advertises* the offer; the discount is what actually *delivers*
   it at checkout.

> **The bar and the discount are separate.** If you show the bar but never create the matching
> discount, shoppers are promised something they won't receive at checkout. Always create the
> discount too, and keep the threshold numbers in sync.

**Single-product / digital stores:** a spend-threshold gift usually doesn't fit (nothing to ship,
and one product can't reach a multi-item threshold), so it's fine to leave this **off** — which is
the default.

## Product page

- **Sticky add-to-cart** — follows the visitor once the buy box scrolls away. On by default.
- **Low-stock indicator** and **back-in-stock capture** — see [Product pages](product-pages.md).
- **Server-anchored sale countdown** — per-template deadline that's identical for every visitor.

## Browsing

- **Quick view** — product modal from any card, with full option selection and add-to-cart.
- **Wishlist** — heart toggle on every product card, in quick view, and on the buy box, saved to
  the visitor's browser (localStorage) and remembered across the store. No login or app required.
- **Recently viewed** — shelf section you can place on any template.

## Capture

- **Popup** — newsletter or promo modal with delay/exit-intent triggers, frequency snoozing, and
  a mobile on/off switch. **Disabled by default** — enable it in the footer group. Use exit
  intent + a real incentive; immediate popups hurt more than help.
- **Newsletter sections** — footer signup plus a standalone section, both creating
  accepts-marketing customers natively (works with Shopify Email, Klaviyo, etc.).

## Merchandising

- **Countdown banner**, **marquee**, **stats**, **logo list**, **hotspots**, **before/after** —
  see the [Section reference](sections/index.md).
- **Bundles** — full system, see the [Bundles guide](bundles.md).
- **Reviews** — native metaobject reviews, see the [Reviews guide](reviews.md).

## A restraint note

These features convert when used selectively. A store running the goal bar, a popup, countdowns,
low-stock pills, and a marquee simultaneously reads as pressure, not polish. Pick the two or
three that fit your brand.
