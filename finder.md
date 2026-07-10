# Product finder & compare

The finder page (`page.finder` template) gives visitors a four-question quiz that recommends
products from your catalog, plus a side-by-side comparison tool. It replaces "product quiz" apps.

## How matching works

Every answer a visitor picks carries **match tags**. Products earn points for each of their
Shopify product tags that appears in the chosen answers' match tags — highest score wins, with
runners-up shown below.

## Setup

1. Create a page (e.g. "Find your plugin") and assign the **finder** template.
2. In the theme editor, open the **Finder quiz** section:
   - The four questions are section settings (e.g. "What do you make?", "What's your workflow?").
   - Each **answer block** has: its label, which question it belongs to, and its `match_tags`
     (comma-separated).
3. **Tag your products** so the quiz has something to match. Keep a small, deliberate tag
   vocabulary, e.g. `mixing`, `mastering`, `scoring`, `vocals`, `bass`, `texture`, `beginner`.
4. Optional per-answer extras: a "preferred format" weighting and a bundle hint that surfaces a
   bundle when several products tie.

The results pull each product's image, price, rating, and metafields (`custom.pitch`,
`custom.formats`, `custom.has_trial`) automatically.

## The compare tool

The same page includes **Compare products**: type tabs, up to four products side by side, spec
rows fed from product data and metafields. Visitor selections persist in their browser.

## Writing a good quiz

- Answers should differentiate, not flatter — if every answer maps to every product, results feel
  random. Aim for each answer to add tags to roughly a third of your catalog.
- Test by playing each "persona" straight through and checking the top result feels right.
- Four questions with 3–4 answers each is plenty; quizzes longer than ~30 seconds get abandoned.
