# Changelog

## 1.0.0 (unreleased) — Honesty & docs refresh (2026-07-04)

Storefront‑honesty fixes from the pre‑submission audit, plus a full documentation refresh so the docs match the shipping theme.

- **Buy box:** the add‑to‑cart CTA is now gated on availability — sold‑out variants show a disabled "Sold out" state instead of an actionable button.
- **Forms:** contact / back‑in‑stock field values persist across submit and validation errors, so a failed submit no longer wipes what the shopper typed.
- **Honest copy:** promo, cart goal‑bar, and free‑shipping messaging reworded so the theme never promises a reward it doesn't actually deliver (the bar advertises; a matching Shopify discount delivers).
- **Neutralized demo claims:** removed hardcoded "100/100/100" and other demo‑store performance boasts from merchant‑facing copy; docs describe features, not marketing numbers.
- **About page:** honors `prefers-reduced-motion` — animated backgrounds and scroll reveals stand down for visitors who ask for reduced motion.
- **Global controls:** the floating **back‑to‑top** button and the sticky add‑to‑cart bar no longer collide — they're coordinated so only the appropriate control shows.
- **Docs:** regenerated the section reference from live schemas (now **77 sections**); removed the 7 legacy customer‑account section pages (the theme now relies on Shopify's new customer accounts, which operate independently of the theme); documented the new metafields (`custom.version`, `custom.headline`, `custom.headline_sub`, `custom.audio_tracks`, `custom.audio_compares`); added the Cart & checkout, Product cards, Animations, and Speed settings panels; and corrected the homepage composition and page‑template list.

## v0.9.0 — Theme Store hardening (release candidate · 2026-06)

Accessibility, checkout, and perceived‑performance work toward Shopify Theme Store submission. This is the current pre‑release; `theme_version` will move to `1.0.0` at Theme Store submission.

- **Accessibility → 100** on home, product, and collection (Lighthouse):
  - Fixed a systemic Liquid mis‑parse where `alt: X | default: Y` inside `image_tag` dropped the fallback — every image alt is now pre‑computed via `assign` (~38 tags across 33 files).
  - Heading order: USP titles `h2`; feature‑story always emits an `h2` even with an eyebrow and no heading.
  - Slideshow autoplay pause/play control (WCAG 2.2.2); popup focus trap; cart‑drawer `aria-live` announcements (WCAG 4.1.3); price‑change announcements.
  - Hardcoded control `aria-label`s moved to `t:` locale keys (header theme toggle, A/B player).
- **Checkout:** dynamic/accelerated checkout buttons on the product buy box and cart drawer (Shop Pay / Apple Pay / Google Pay / PayPal), variant‑synced; buy box reworked to Add‑to‑cart‑primary + accelerated express. Cart‑drawer accelerated buttons deferred until the cart has items (keeps ~1 MB of Shopify checkout JS off empty‑cart page loads).
- **Search:** storefront faceted filters (`search.filters`) on the product search results, with a no‑JS Apply fallback.
- **Product:** added the **spotlight** showcase layout (fourth layout); A/B/C audio comparison; MacBook Pro device frame option for the image‑hotspot section.
- **Speed stack** (Theme settings → Speed, on by default): predictive prefetch on hover/focus/press; cross‑document View Transitions; `content-visibility` on off‑screen body sections.
- **Downloads:** `<noscript>` fallback with server‑rendered installer links. **Audio player:** duration probes deferred to idle.
- **Packaging:** neutralized all `shopify://` demo resource refs from the committed default templates (fresh installs show placeholders); removed the dev‑only `page.sections-demo` template.

## v0.1.0 — Initial build

First complete theme.

- Complete OS 2.0 theme: 74 sections, JSON templates for every page type
- Dark / light / auto color schemes with accent presets
- Mega menu with automatic category icons and collection-description subtitles
- Product pages: 3 buy-box layouts, option notes/tags/color/image swatches, sticky ATC,
  low-stock, back-in-stock, server-anchored countdowns, app blocks
- Bundles system (metafield-driven contents, honest savings math)
- Native metaobject product reviews with moderated submissions
- Product finder quiz + comparison tool, downloads hub with changelogs
- Conversion suite: cart goal bar, drawer upsell rail, quick view, wishlist, recently viewed,
  popup
- Section library demo template
- Performance: 100/100/100 desktop Lighthouse (performance/accessibility/SEO) on the demo store
- Self-hosted variable fonts, structured data (Product, BreadcrumbList, Article, Organization,
  WebSite)
