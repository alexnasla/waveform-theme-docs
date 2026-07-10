# Downloads page

The downloads page (`page.downloads` template) is an installer hub: a featured latest release
with per-OS buttons, a searchable list of all installers with changelogs, and a docs strip.
It's for **public installers and trials** — for paid license delivery, use a digital-delivery
app or your own license portal, and link it from here.

## Setup

1. Create a page (e.g. "Downloads") and assign the **downloads** template.
2. **Downloads hero** — the featured release: name, version, and a download URL + file size per
   OS. The visitor's operating system is detected and preselected.
3. **Downloads list** — one block per product release. Each block holds the per-OS URLs and a
   changelog written in a simple format:

   ```
   v2.1.0 | May 2026
   - New transient-aware release algorithm
   - **Apple Silicon** performance pass
   v2.0.0 | Jan 2026
   - Redesigned interface & metering
   ```

   One `vX.Y.Z | date` line starts a release; `- ` lines are its notes; `**bold**` is rendered.

4. **Downloads docs** — manuals and system requirements using `Label | Value` rows, plus a help
   strip linking to support.

## Where to host the files

Anywhere that serves a direct URL: Shopify **Files** works for installers under its size limits;
larger packages typically live on a CDN or S3-style bucket. Paste the direct link into the
block.

## Tips

- Keep the hero pointed at your flagship's current version — it's the page's main job.
- The list's OS toggle and search only shine once you have several products; with one product,
  consider hiding the list section and letting the hero carry the page.
