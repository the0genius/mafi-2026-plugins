---
name: mafi-2026
description: >
  This skill should be used for any task involving MAFI (MAFI for Agricultural Produce Industries,
  the Egyptian–Emirati B2B agri-food ingredients company in Sadat City), when the user asks to
  "design for MAFI", "make a MAFI leaflet / flyer / brochure page / spec sheet", "create a MAFI social post",
  "build a MAFI deck or slide", "write MAFI copy", "use the MAFI brand", "check this against MAFI guidelines",
  or asks about MAFI products, specs, capacities, the factory, certifications, partners, colours, fonts,
  logo, the leaf, product photos or tagline. It contains the complete MAFI 2026 brand pack: company facts,
  all 26 products, voice and copy rules, visual identity, creative playbook, approved assets and past work.
metadata:
  version: "1.0.0"
  display-name: "MAFI 2026"
---

# MAFI 2026: complete brand knowledge

This skill directory holds the **complete MAFI Brand Pack (full-resolution edition), unchanged**. The one exception is the 12 IQF top-view photos, which live in the companion skill `mafi-2026-iqf-photos` (see section 3). All paths below are relative to this skill's base directory.

## 1. Load the knowledge (always, before producing anything)
1. Read `README.md` **in full**. It holds the 60-second brief, the reading order and the folder map.
2. Read the chapters the task needs, **in full**. Don't skim, and don't rely on a summary or on memory:

| Task | Read |
|---|---|
| Any fact about the company, figures, capacities, the complex, certifications, partners, markets, contacts | `01_Company.md` |
| Any product name, spec, packaging, shelf life, application, seasonality or product image | `02_Products.md` (+ `data/products.json`) |
| Any writing: headlines, body copy, captions, straplines, boilerplates | `03_Voice_and_Copy.md` |
| Any design: layout, colour, type, logo, leaf and sprout, imagery, icons, motion, formats | `04_Visual_Identity.md` |
| Anything new or creative (posts, leaflets, decks, campaigns, packaging, AI imagery) | `05_Creative_Playbook.md` |
| Choosing files to use | `06_Assets_Index.md` |
| Anything that seems to conflict, or questions about sources | `07_Sources_and_Decisions.md` |

3. For substantial work (a full leaflet, deck, campaign, website or brochure), read **all** of `01`–`07`.
4. Before designing, **look at** `brand-board.png` and the relevant contact sheets in `reference/_overview/` to absorb the feeling, then open individual reference files as needed.

## 2. Apply the knowledge
- **Use facts exactly as written.** Quote figures, specs, product names, taglines and straplines from the pack verbatim. Never round, invent, estimate or "improve" a figure. If something isn't in the pack, say so and ask the user. Don't guess.
- **Order of authority:**
  1. The user's direct instructions in the current conversation.
  2. Files `01`–`05`. These are the rules.
  3. `07_Sources_and_Decisions.md` for resolved conflicts.
  4. `reference/`, which shows the feeling only. Learn from it; don't copy it 1:1, and don't take colours from older pieces.
- **Hold the fixed core, then be creative.** Fixed:
  - the official logo files
  - the colour hierarchy: white background, MAFI Green `#009C49` primary, MAFI Blue `#045976` secondary, black accent; no turquoise, no other brand colours; product-family colours only to tag products
  - Alverata + Avenir Next (GE SS for Arabic)
  - the leaf and the sprout
  - the tagline "Pioneering the Future of Food Innovation"
  - the facts

  Everything else (composition, scale, density, mood, crop) is open. Follow `04` §C and `05`, and vary each piece in a series.

## 3. Use the assets
- **Logos:** `assets/logo/`. Always place the real file. Never redraw, retype or generate the logo.
- **Leaf and sprout:** `assets/marks/` (SVG + PNG).
- **Products:** two directions, with all 26 products in each. Use **one direction per layout**. Product ids and family folder names match `data/products.json`.
  - **Glass bowls:** `assets/products/glass-bowls/<family>/<product-id>.jpg`. All 26 products are in this skill.
  - **Top view** (4K, transparent PNG): `assets/products/top-view/<family>/<product-id>.png`.
    - **Citrus, Tomato & Multi-Fruits and Freeze Dry** are in this skill.
    - **The 12 IQF products** (`assets/products/top-view/iqf/`) are in the companion skill **`mafi-2026-iqf-photos`** (plugin "MAFI 2026 – IQF Photos"), at the same relative path under that skill's base directory. Load that skill to get them.
    - If it isn't installed, use the IQF glass-bowl images from this skill, and tell the user that the IQF top-view photos need the "MAFI 2026 – IQF Photos" plugin.
- **Photography:** `assets/imagery/`. **Film stills:** `assets/film-stills/`.
- **Tokens:** `tokens/mafi-tokens.css` and `tokens/mafi-tokens.json` hold colour roles, the gradient, type stacks with free fallbacks, radii and shadows.
- **When building HTML, artifacts, documents or design files,** copy the needed assets out of the skill directories into the working or output folder and reference the copies.
- **Fonts:** if Alverata or Avenir Next isn't available, use the fallbacks named in `04_Visual_Identity.md` §A4.
- **AI images:** never let an image model render text, logos, labels or Arabic. Add real type and the real logo afterwards (`05` "Using AI image tools").

## 4. Before delivering
Run the "Before you ship" checklist at the end of `05_Creative_Playbook.md`, and the proofreading checklist at the end of `03_Voice_and_Copy.md`.
