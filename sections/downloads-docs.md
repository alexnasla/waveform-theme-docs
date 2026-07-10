# Downloads resources

Downloads page: manuals, system requirements, and a help strip.

> **Tip:** Rows use a simple `Label | Value` per-line format.

**File:** `sections/downloads-docs.liquid` · Add anywhere via **Theme editor → Add section**.

## Settings

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| **Manuals** | | | |
| Heading | `text` | Manuals & resources |  |
| Subtitle | `text` | User guides, quickstarts and licensing — PDF. |  |
| **System requirements** | | | |
| Show system requirements | `checkbox` | off | System requirements are usually specific to each product, so they're hidden on this cross-product Downloads page by default. Turn on to show a macOS / Windows spec table. |
| Heading | `text` | System requirements |  |
| Subtitle | `text` | Minimum specs for our software. |  |
| macOS rows | `textarea` | OS | macOS 11 Big Sur or later
CPU | Apple si… | One "Label \| Value" per line. |
| Windows rows | `textarea` | OS | Windows 10 / 11 (64-bit)
CPU | Intel Cor… |  |
| Note | `text` | A working internet connection is required for… |  |
| **Help strip** | | | |
| Heading | `text` | Trouble installing? |  |
| Text | `textarea` | Step-by-step guides for every DAW, plus a tea… |  |
| Secondary button label | `text` | Knowledge base |  |
| Secondary button link | `url` |  |  |
| Primary button label | `text` | Contact support |  |
| Primary button link | `url` |  |  |
| **Spacing & style** | | | |
| Section background | `select` | default | Options: Default (page background) / Subtle / Panel / Accent tint / Inverse (dark band). |
| Animate on scroll | `checkbox` | on | Fade/slide this section in. Requires Theme settings → Animations to be on. |

## Block: Document (`doc`)

| Setting | Type | Default | Notes |
| --- | --- | --- | --- |
| Name | `text` | User Guide |  |
| Subtitle | `text` | PDF · 4.2 MB |  |
| Icon | `select` | doc | Options: Book / Document / Shield / Scales / Gift. |
| File URL | `url` |  | Upload PDFs under Content → Files and paste the URL. |

_Maximum blocks: 10_
