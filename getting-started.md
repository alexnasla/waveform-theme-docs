# Getting started with Waveform

This guide takes you from a fresh install to a configured storefront. Waveform is built for
digital-product and software companies — everything here assumes you sell things like plugins,
sample packs, presets, or other downloadable products, but it works for any catalog.

## 1. Install and publish

1. **Online Store → Themes → Add theme** and upload the Waveform zip (or install from the Theme
   Store listing).
2. Click **Customize** to explore it unpublished first — your live theme is untouched until you
   click **Publish**.
3. Waveform ships with working placeholder content in every section, so the preview is never
   blank, even before you add products.

## 2. Pick your look (2 minutes)

Open **Theme editor → Theme settings**:

- **Colors** — choose Dark (default), Light, or **Auto**, which follows each visitor's system
  preference. Then pick an accent: the accent drives buttons, links, gradients, and glows
  storewide.
- **Typography** — the bundled variable fonts are self-hosted for speed; you can swap in any
  Shopify font pair.
- **Style presets** — three starting combinations are available under presets if you want a
  different baseline than the default.

See the full [Theme settings reference](theme-settings.md).

## 3. Set up navigation (the mega menu)

Waveform's header renders up to three menu levels as a mega menu automatically:

1. **Online Store → Navigation → Main menu.** Top-level items become the header tabs; their
   children become mega-menu columns; third-level items become the links.
2. **Category icons and subtitles are automatic**: when a menu item links to a collection, the
   mega menu shows an icon matched to the collection plus the first line of that **collection's
   description** as the link subtitle. Write a short, punchy first sentence in each collection
   description — it doubles as menu copy.
3. The footer uses the **Footer** and **Footer resources** menus.

## 4. Build the homepage

The default homepage is a full composition — replace its content rather than starting from
scratch:

- **Hero** — your headline. Wrap one phrase in `<em>` for the accent-gradient emphasis.
- **Collection list** — your top categories.
- **Featured collection** — best sellers.
- **Image with text ×2** — feature moments (e.g. product finder, tutorials).
- **Testimonials** — social proof.
- **Rich text** — a closing mission statement.

Every section is in the [Section reference](sections/index.md). A second complete homepage
composition ships as the `home-alt` template (**Theme editor → template picker → Homepage →
home-alt**) if you prefer a slideshow-led layout.

> **Single-product store?** Lead with the **Featured product** section (a real buy box, not a
> link), follow with **Feature story**, **Testimonials**, and **FAQ**, and keep the nav to
> Product / Support / Contact.

## 5. Products

Each product page pulls from three places:

1. **The product itself** — title, price, description, gallery media, variants.
2. **Waveform's metafields** — subtitle, rating, formats, platforms and more
   ([Metafields reference](metafields-reference.md)).
3. **The product template's sections** — feature stories, key features, specs, reviews, FAQ.

To give each product its own stories and imagery, use one template per product
([Product pages guide](product-pages.md)) or one metafield-driven template
([One template for many products](metafields-single-template.md)).

## 6. Standard pages

Create pages under **Online Store → Pages** and assign Waveform's purpose-built templates in the
page's **Theme template** dropdown:

| Page | Template | What you get |
| --- | --- | --- |
| Support | `page.support` | Hero with live FAQ search, topic cards, license panel, contact form |
| FAQ | `page.faq` | Grouped accordion FAQ |
| Contact | `page.contact` | Styled native contact form |
| Product finder | `page.finder` | Quiz + comparison ([guide](finder.md)) |
| Downloads | `page.downloads` | Installer hub with changelogs ([guide](downloads.md)) |
| About | `page.about` | Story-driven About page (hero, vision, technology, stats, how-we-work, founder, story, contact) |

## 7. Pre-launch checklist

- [ ] Favicon + share image set (Theme settings → Search engine listing)
- [ ] Meta description fallback written
- [ ] Customize the **password page** (it's your coming-soon page)
- [ ] Legal pages created (Shopify Settings → Policies)
- [ ] Filters configured in the **Search & Discovery** app (drives collection page filters)
- [ ] Payment + checkout tested with a 100%-off discount code
- [ ] Run Lighthouse on your published home/product pages — Waveform scores 100/100/100
      (performance/accessibility/SEO) on desktop out of the box; keep images reasonably sized to
      stay there
