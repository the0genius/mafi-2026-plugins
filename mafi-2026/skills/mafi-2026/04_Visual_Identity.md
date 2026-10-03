# 04 · Visual Identity

This system is deliberately **loose**:
- **A short core never changes** (section A).
- **Signatures you should lean on** come next (section B). They are strong defaults, not laws.
- **Everything else is your call** (section C), as long as the result still feels like MAFI.

**The feeling to hit:** bright, clean and appetising, a laboratory that smells like an orchard. The food's own colour does the shouting, while the design stays calm and confident and lets it.

---

## A. THE CORE (never changes)

### A1. Logo
- **What it is:** "MAFI" in a warm serif inside a rounded-rectangle frame, with **the leaf** sprouting from the top-left of the M. It uses green, a green-to-blue blend in the letters, and blue. The descriptor **FOR AGRICULTURAL PRODUCE INDUSTRIES** sits below in bold blue capitals.
- **Files:** `assets/logo/`
  - `mafi-logo-primary.png`: square, full colour, the default
  - `mafi-logo-horizontal.png`: horizontal lockup
  - `mafi-logo-white.png`: on photos, green or dark backgrounds
  - `mafi-logo-mono-dark.png`: one-colour
  - `mafi-logo-arabic.png` and `mafi-logo-arabic-horizontal.png`
  - `mafi-logo-bilingual-horizontal.png`
- **Clear space:** keep a margin around the logo equal to the height of the leaf, about 18% of the logo's width. Minimum width is **0.5 in / 12.7 mm / 48 px**.
- **On colour:**
  - Full colour on white.
  - **White** on photos, the green flood or dark backgrounds.
  - One-colour (green, blue or black) when full colour won't reproduce.
- **Never:**
  - redraw, retype, stretch or recolour parts of it
  - change the proportion between the icon and the text
  - put a gradient into the lettering
  - add effects (shadow, glow, outline)
  - place full colour on a busy photo
- **AI images must never generate the logo.** Place the real file afterwards.
- **Placement:** any deliberate anchor (a top corner, top-centre, bottom-left, or centred on covers and end cards). Use one MAFI logo per piece, plus partner or event logos only for co-branding.

### A2. The leaf & the sprout (core brand devices)
The leaf is part of MAFI's identity and should be used generously. There are two shapes, both supplied as vectors.

| Mark | File | What it is | Typical use |
|---|---|---|---|
| **The MAFI leaf** | `assets/marks/mafi-leaf-*.svg/png` | The leaf from the logo: a curled leaf over a stem | A **heading marker** placed just before section titles (the profile does this on every page); a small signature on factory signs; a list bullet |
| **The sprout** | `assets/marks/mafi-sprout-*.svg/png` | A two-leaf seedling | Bullets in contents lists, pins on maps, the leaf on lower-third pills, **giant cover graphics** (a huge white sprout cropped over a product photo), leaf-shaped callout tags, low-opacity watermarks |

**Colours:**
- Leaf and sprout: MAFI Green, MAFI Blue or white. Keep them **solid**, never outlined or gradient-filled.

**How to use them:**
- Scale freely, from a 3 mm bullet to a full-page crop.
- Bleed them off an edge.
- Use them as a window into a photo.
- At very large scale, the sprout can mask or reveal photography; the profile cover does this.

**Don't:**
- Redraw them.
- Put several different leaf styles in one piece.
- Use them as decoration on every element. **One leaf idea per layout, used with intent.**

### A3. Colour
**The colour hierarchy:** use the colours in this order of importance.

| Role | Colour | HEX | CMYK | How to use it |
|---|---|---|---|---|
| **Background** | **White** | `#FFFFFF` | 0 0 0 0 | The default ground for almost everything. Let the white breathe. |
| **Primary** | **MAFI Green** (Leaf) | `#009C49` | 97 25 0 54 | The leading brand colour: headlines, the leaf and sprout, key highlights, buttons, pills and icons, **and the flood colour** for big statement surfaces. Growth and sustainability. |
| **Secondary** | **MAFI Blue** (Mediterranean) | `#045976` | 92 54 31 9 | Supports the green: subheads, alternate headlines, information blocks, the logo descriptor, rules, data. Trust and purity. |
| **Accent / third** | **Black** | `#000000` | 0 0 0 100 | Contrast and precision: body copy, specs, product-title second words, fine details, the mono logo. |

**How much of each:** a typical piece is about 70–80% white and food photography, plus green as the main colour moment, blue in support and black for text and detail. On a Green Flood piece, green becomes the ground and white the type.

**These four are the whole brand palette.** No other brand colours: **no turquoise, no silver, no paper or linen tones**. When you need something lighter or deeper, use a **tint or shade of these four** (see below).

**Brand gradient:** a direct blend from primary green to secondary blue, `#009C49 → #045976`, with no colour in between.

**Product family colours.** These are a separate layer and **not brand colours**. They come from the product brochure and are used only to tag which family a product belongs to (title word, spec panels, month tabs, edge rule). They never appear in logos, headlines about MAFI, buttons, backgrounds or corporate pieces.

| Family | Title colour | Panel tint |
|---|---|---|
| Citrus | `#F3BC5A` amber | `#F4D089` |
| Tomato & Multi-Fruits | `#F37F64` coral | `#F7A692` |
| Frozen Fruits & Vegetables (IQF) | `#58B36A` fresh green | `#BCE0C3` |
| Freeze Dry | `#D62B2B` strawberry red | `#EFB4B4` |

**Tints and shades** (lighter or deeper versions of the four, never new hues):

| Need | Use |
|---|---|
| Soft panel or box on white | Green 10% `#E6F5ED` or blue 10% `#E6EEF1`. The page background itself stays white. |
| Hairlines, dividers, table rules | Black at 10–15% (`#D9D9D9`–`#E6E6E6`) or blue at 20% |
| Muted secondary text | Black at 60–70% |
| Depth on a Green Flood surface (the 2026 exhibition look) | Shades of the primary green: `#009C49` → `#0C6C3C` → `#0C3C24` → `#071A12` |
| Text protection over photos | A black scrim, or a green-shade scrim on Green Flood pieces |

Full token set: `tokens/mafi-tokens.css` and `tokens/mafi-tokens.json`.

### A4. Typography
| Role | Typeface | Guidance |
|---|---|---|
| Headlines | **Alverata** (Bold is the signature; lighter weights for quiet, reflective lines) | 30–100 pt in print. A warm, humanist serif. Set slightly tight. Colour: **green** by default, **blue** as the alternative, white on floods and photos. |
| Subheads, body, labels, specs | **Avenir Next** (UltraLight → Heavy, with italics) | Body Regular, 9.5–12 pt in print, in **black** (or blue for short passages). Subheads Medium or Regular, often *italic*, in **blue**. Labels Bold or Heavy in CAPS, tracked +6–10%. Very large quiet words in UltraLight. |
| Arabic | **GE SS** (GE SS Two) | Bold headings, Regular/Light body |
| Handwritten callouts | A casual monoline script | Only for pointer labels on application posts, with hand-drawn arrows |

- **Two families only** (plus Arabic). Don't add a third display face. The 2026 materials drifted into extra fonts (condensed, rounded, monospace, Roboto), so don't copy that.
- **Fallbacks when the licensed fonts aren't available** (web, quick mockups):

| Licensed font | Fallback |
|---|---|
| Alverata | **Faustina** |
| Avenir Next | **Nunito Sans** |
| GE SS | **Noto Kufi Arabic** |
| Handwritten script | **Caveat** |

- **The capital I must look like a capital I.** Never set "MAFI" in a typeface where the capital I looks like a lowercase l. The 2026 film's subtitle font made the brand read "MAFl".

---

## B. SIGNATURES (lean on these; adapt them freely)

1. **Family colour coding.** The first word of a product title is in the family colour, the second word is in black or blue, the spec panels are in the family tint, and a family-coloured rule runs at the page edge.
2. **Spec panels.** Rounded tinted boxes, each with a thin line icon: drum = packaging, kg bag = weight, calendar = shelf life, knife = cut. The "IDEAL FOR" label runs vertically. Brix sits in an outlined box.
3. **The seasonality strip.** 12 slanted, parallelogram month tabs, with the active months filled in the family tint.
4. **The sweeping gradient band.** On the brochure cover, a curved green-to-blue band frames the flat-lay photo with two arcs. It is used on covers and back covers.
5. **Heading + short rule.** A heading in Alverata (green, or blue as the alternative), a short green rule under it, and an optional leaf in front.
6. **The gradient as an edge.** A thin bar, a footer strip carrying the tagline, a vertical side band (as in the identity manual) or a frame. Keep it at the edges; never put it behind body text.
7. **Rounded photography.** Tall rounded rectangles and 2×2 photo grids with generous radius (the profile's application pages). Also full-bleed photography.
8. **Pills.**
   - Info pills with an icon, e.g. date, venue and stand on event posts.
   - The film lower third: a green pill with a white sprout and bold white category name, joined to a white pill carrying the value.
   - A full-width green pill banner with a sprout.
9. **Four-up icon row.** Thin line icons with two-line caps labels and hairline dividers between them, along the bottom of a piece.
10. **Page furniture.** A small "MAFI | 12" folio, a family-coloured rule, and generous white space.

## C. FREE (your call; vary it from piece to piece)

**Composition, scale, density, background and type weight** are all open. Choose a **mood** first.

| Mood | Looks like | Best for |
|---|---|---|
| **Daylight** (default) | A white background, green headlines, blue support, black text, colour from the food, plenty of air | Products, catalogues, social posts, spec sheets, reports, most things |
| **Green Flood** | The primary green as the ground, deepening to forest and near-black with gloss and depth. White type, fruit and liquid splashing out of the green. | Exhibitions, events, campaigns, statements, film graphics, big numbers |
| **Immersive** | A full-bleed photograph (field, kitchen, golden-hour street, factory) with white type over a soft bottom scrim | Covers, section openers, #MAFI_around_the_world |

**Room to play:**
- **Headline size:** use the whole 30–100 pt range; don't settle on about 40 every time.
- **The gradient** can sit at any edge, act as a frame, or be left out (Immersive pieces usually skip it).
- **Logo position** can move.
- **Backgrounds are white.** The only big colour floods are **primary green** (Green Flood) and full-bleed photography. **Secondary blue** works as a solid only in small moments: horizontal logo pills, stationery bands, badges, data boxes.
- **Corners:** default about 10–14 px (screen) or 3–4 mm (print), up to 24 px or more on large photos. Pills are fully round.
- **Shadows:** soft and low, tinted with the secondary blue, e.g. `0 6px 18px rgba(4,89,118,.09)`, plus a soft drop under product cut-outs. Never hard black.
- **Grid:** even-numbered columns (12 or 6). Images take two columns or a full row; text takes two columns or a centred block.
- **A series should vary.** Within a campaign or deck, don't use the same layout twice in a row. Four members of one family is right; four identical things is wrong.

---

## Imagery

**Style:** vibrant natural colours, high resolution and subject-focused. Food is always the hero. Light is bright and appetising, with soft shadows. People appear only as professionals at work, at events, or as hands in action.

| Mode | Look | In the pack |
|---|---|---|
| **Overhead cut-outs** | The product top-down in a white bowl or glass dish, transparent background | `assets/products/top-view/` |
| **Glass bowls** | Three-quarter view of the product in a clear glass bowl on white | `assets/products/glass-bowls/` |
| **Lab glassware** | Product in beakers with measuring marks: science holding nature | `reference/social-posts/14_*`, `25_*`; brochure pages |
| **Liquid in motion** | Drips from fruit slices, pours, splashes, purée ribbons | social posts 01, 02, 07, 11, 14 |
| **Scatter on white** | IQF pieces spilling in from a corner on pure white | `assets/imagery/iqf-scatter/` |
| **Macro & texture** | A purée swirl, frost on frozen fruit, a leaf macro, a full-bleed tomato texture | `assets/imagery/texture-leaf-macro.jpg`, post 06 |
| **Applications** | Desserts, salads, drinks and bakery, styled on light marble or white surfaces | brochure, profile, posts 03, 05, 33, 35 |
| **Places** | Golden-hour scenes from MAFI's markets | posts 13, 15, 16 |
| **Agriculture** | Fields and crop rows at golden hour | `assets/imagery/field-crop-rows.jpg`, film stills 01 |
| **Industry (real)** | Stainless steel, evaporators, freeze-dryers, boilers; cool clean daylight | `assets/film-stills/` |
| **Architecture** | Plant aerials, signage, HQ renders | `assets/film-stills/`, `assets/imagery/facility-*` |

**Colour grading:** warm and golden for food and fields; cool and clean for the factory. Nothing in between.

**Not used:** black-and-white photos, grain, heavy filters, illustration styles or mascots. Stock photography is not presented as MAFI's own plant or products.

## Icons
Thin, single-colour line icons (about 1.5 px on a 24 px grid, rounded joins, no fills) in MAFI Green or MAFI Blue. Common glyphs: leaf-in-circle, gear-with-leaf, globe, recycling arrows, handshake, rosette with check, drum, kg bag, calendar, knife, snowflake, factory, truck, map pin.
- **Always label icons** with short caps.
- **Fallback library:** Lucide (`stroke-width: 1.5`).

## Motion & film
- **Pace:** calm and cinematic. Golden-hour drones, macro food, slow-motion falling pieces and steady factory dollies.
- **Typography:** fades and short upward reveals, about 200–600 ms. No bounce. The gradient bar can wipe left to right.
- **Data and lower thirds:** the green + white pill with typewriter values; full-width green pill banners for locations.
- **Subtitles:** a semi-transparent dark rounded box, centred at the bottom, set in Avenir Next (not a font that confuses I and l).
- **End card:** the logo on white with "MAFI… Pioneering the Future of Food Innovation."

## Formats seen in MAFI's work
| Surface | Format |
|---|---|
| Social | 1:1 (1080 × 1080), 4:5 (1080 × 1350), 16:9 banners |
| Product brochure | US Letter portrait (8.5 × 11 in) |
| Company profile | Square, 210 × 210 mm |
| Identity manual | A4 landscape |
| Exhibition panels | Tall portrait, about 1 : 2.6 |
| Decks and film | 16:9 (1920 × 1080, 25 fps) |
