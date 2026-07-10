# Troubleshooting & FAQ

**Collection filters don't appear.**
Filters are configured in Shopify's free **Search & Discovery** app (Apps → Search & Discovery →
Filters). The theme renders whatever you enable there.

**The low-stock pill / back-in-stock form never shows.**
Both need real inventory signals: the variant must have **inventory tracking ON** ("Track
quantity") and **"Continue selling when out of stock" OFF**. Untracked inventory has no stock
level to read.

**Stars don't show on product cards.**
Set the `reviews.rating` and `reviews.rating_count` metafields on the product — see the
[Metafields reference](metafields-reference.md).

**Reviews section is empty even though I created entries.**
Check the metaobject definition has **storefront access enabled** and the type is exactly
`waveform_review`. Entries must reference the product you're viewing.

**A number setting won't save (e.g. "products to show").**
Range settings snap to fixed steps (e.g. 3/6/9/12). Pick a value on the steps.

**My popup doesn't appear.**
It's disabled by default; enable it in the footer group. Once dismissed it snoozes per browser —
test in a private window, or temporarily set frequency to 0.

**Mega menu shows no icons/subtitles.**
Menu items must link to **collections**, and each collection needs a description — the first
line becomes the subtitle.

**Where are the account / login / order pages?**
Waveform relies on Shopify's **new customer accounts**, which operate independently of the theme —
Shopify hosts the sign-in, account, and order pages, and themes don't ship (or restyle) templates
for them. The header shows a **Sign in** link (gated on customer accounts being enabled under
Settings → Customer accounts); it routes to Shopify's hosted login. There are no theme-side account
sections to configure.

**Variant price shows "—" or doesn't update.**
Usually a third-party app conflict injecting its own variant script. Disable app embeds one at a
time (Theme editor → App embeds) to find the culprit.

**Light mode looks wrong in one spot.**
Sections over photography intentionally keep white text on a dark scrim in both schemes. If you
find a genuine contrast bug, report it to support with the page URL and a screenshot.

**Where can I see every section in one place?**
Create a page with the **Section library** demo template — it renders all of them with sample
content. Also see the [Section reference](sections/index.md).

**Performance dropped after launch.**
The usual suspects, in order: very large unoptimized images, third-party app scripts, and
non-bundled fonts. Waveform's own baseline is 100 desktop performance — measure with one app
embed off at a time.

**How do updates work without losing my customizations?**
Your settings and templates are data (JSON), not code — theme updates replace code while Shopify
preserves your settings where setting IDs are unchanged. We never rename setting IDs between
versions. Still: keep a duplicate of your theme before updating, and re-apply any direct code
edits you made.
