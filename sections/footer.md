# Footer

Site footer: link menus, newsletter signup, locale/currency selectors, payment icons, and an optional custom Liquid block.

> **Tip:** The newsletter form creates accepts-marketing customers — no app needed.

**File:** `sections/footer.liquid` · Fixed/system section (part of a template or section group).

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Policy links menu | `link_list` |  | Shown beneath the newsletter signup (Terms, Refund policy, Licensing…). |
| Show payment icons | `checkbox` | on |  |
| Show country/region selector | `checkbox` | on | Powered by Shopify Markets. |

## Block: Brand (`brand`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| About text | `textarea` | Studio-grade instruments and plugins for prod… |  |
| Show social icons | `checkbox` | on | Links are set in Theme settings → Social media. |

## Block: Link column (`menu`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Heading | `text` | Products |  |
| Menu | `link_list` |  |  |

## Block: Newsletter (`newsletter`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Heading | `text` | Newsletter |  |
| Text | `textarea` | Free exclusive offers, production tips and pr… |  |

## Block: Custom Liquid (`custom_liquid`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Heading | `text` |  |  |
| Liquid code | `liquid` |  | Add text, HTML or Liquid — useful for legal badges, compliance links or app snippets. |

_Maximum blocks: 6_
