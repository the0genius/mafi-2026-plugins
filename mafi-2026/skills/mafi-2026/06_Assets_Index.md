# 06 · Assets Index

Every file in this pack and what it's for. **`assets/`** holds approved material you can use in new work. **`reference/`** holds past MAFI work to learn the feeling from: study it, but don't copy it 1:1.

## assets/logo/ (7 PNG, transparent)
| File | Use |
|---|---|
| `mafi-logo-primary.png` | Default: square lockup, full colour, on white |
| `mafi-logo-horizontal.png` | Wide spaces: headers, footers, slide corners |
| `mafi-logo-white.png` | On photos, the green flood, dark backgrounds |
| `mafi-logo-mono-dark.png` | One-colour reproduction |
| `mafi-logo-arabic.png` / `mafi-logo-arabic-horizontal.png` | Arabic pieces |
| `mafi-logo-bilingual-horizontal.png` | Bilingual pieces, signage |

## assets/marks/ (the leaf & the sprout, vector SVG + PNG)
| File | Use |
|---|---|
| `mafi-leaf-{blue,green,white}.svg/png` | The logo's leaf: heading marker, small signature, bullets |
| `mafi-sprout-{green,blue,white}.svg/png` | Two-leaf sprout: bullets, pill icons, map pins, giant cover crops, watermarks |

Recolour the SVGs only to green, blue or white.

## assets/products/ (two directions, all 26 products in each)
| Folder | What | Notes |
|---|---|---|
| `top-view/<family>/` | Overhead, in a white bowl, **transparent PNG** | 22 at about 3,700 px (4K masters); tomato, corn-on-the-cob, green peas and the freeze-dried cuts at 1,254 px. Includes `_alt` variants for mandarin and orange cloudy, and `freeze-dried-strawberry_mixed`. |
| `glass-bowls/<family>/` | Three-quarter view in a clear glass bowl, **on white (JPG)** | Cut from the official lineups. Freeze-dried strawberry has `_whole`, `_sliced`, `_diced` and `_powder`. |
| `_lineups/` | The four official family lineups, labelled | Citrus (8) · Tomato & Multi-Fruits (5) · IQF (12) · Freeze-dried strawberry (4 cuts). The labels are typeset, so you can use them as-is. |

File names match the product `id` in `data/products.json`. Family folders: `citrus`, `tomato-multi-fruits`, `iqf`, `freeze-dry`.
Contact sheets: `reference/_overview/products_top-view_all.jpg` and `products_glass-bowls_all.jpg`.

## assets/imagery/ (brand photography, from the 2026 brochure and profile)
| File | Use |
|---|---|
| `hero-portfolio-flatlay.jpg`, `_alt` | **The hero:** the whole portfolio overhead in white bowls. Covers, back covers, portfolio moments. |
| `hero-iqf-medley_film-still.jpg` | IQF medley on dark steel, frosted (1080p film still) |
| `family-citrus-juice-jars.jpg` | Citrus opener: juice in glass jars with fruit |
| `family-tomato-on-the-vine.jpg` | Tomato & Multi-Fruits opener |
| `family-tomato-multifruit-purees.jpg` | Purées with fruit, macro, full-bleed |
| `family-iqf-frozen-mix.jpg`, `_wide` | IQF opener: frosted fruit and vegetables, full-bleed |
| `family-freeze-dry-strawberries-bowl.jpg` | Freeze Dry opener on a dark surface |
| `iqf-scatter/*.jpg` | IQF pieces spilling in from a corner on white (sweet potato, cauliflower, corn-on-the-cob, peas) |
| `texture-leaf-macro.jpg` | Leaf macro texture, for backgrounds and side bands |
| `field-crop-rows.jpg` | Agriculture: crop rows under sky |
| `sustainability-forest-recycle.jpg` | Sustainability: aerial forest with recycle arrows |
| `facility-render-facade.jpg`, `facility-render-street.jpg` | Architectural renders of the complex (label them as renders) |

## assets/film-stills/ (29 frames from the corporate film, Sept 2026, 1280 px)
Real plant footage, renders and the film's own graphics. Use them for proof of capability, and as reference for film or motion graphics.

| # | Content | Type |
|---|---|---|
| 01 | Delta farmland at golden hour | Drone |
| 02, 13 | Plant aerial: construction complete, full solar roof | Real |
| 03 | Export gateways map | Graphic |
| 04, 27, 28 | HQ entrance, HQ exterior, VIP visitor corridor | CGI renders |
| 05, 10, 12, 19 | Evaporator towers, boiler house, CIP station, freeze-dry vessels | Real or near-real |
| 06 | Site plan with labels and figures | Real + graphics |
| 07, 08 | Freeze-dryer chambers; aseptic bag-in-drum filling | |
| 09, 11 | Freeze-dried slices falling; IQF portfolio medley | Macro food |
| 14–18 | **Capacity lower thirds** (green + white pill): a reference for data graphics | Graphics |
| 20 | Certification logo wall | Graphic |
| 21–24 | Partner logo walls | Graphic |
| 25, 26 | "IQF FACTORY" and "FREEZE DRIED FACTORY" signage | Real / render |
| 29 | End card: logo + tagline | Graphic |

## reference/ (past MAFI work, for feel only)
| Folder | What it teaches |
|---|---|
| `social-posts/` (38, numbered by date, Nov 2024 → Jul 2026) | The richest record of MAFI's creative habits: product-as-graphic, beakers, drips, applications, around-the-world, events, occasions. File names describe each post. |
| `print_products-brochure-2026/` | Product page system: family colours, spec panels, seasonality tabs, family openers, cover band |
| `print_company-profile-2026/` | Corporate layout: leaf heading markers, rounded photos, 2×2 application grids, big sprout cover, factory and packaging pages |
| `print_ci-manual-2024/` | The original identity manual: logo rules, type, colour, grid, stationery |
| `exhibition-panels-2026/` | The **Green Flood** look for trade shows |
| `deck_polaris-report-2026/` | A 2026 report deck. Its monospace and condensed fonts are **not** to be copied. |
| `_overview/` | Contact sheets of everything above, for a quick scan |

Note on older reference: early 2025 posts and the 2024 manual use turquoise and other tones. The brand palette is now **white, green, blue and black only** (`04_Visual_Identity.md`), so learn composition from them, not colour.

## data/
| File | What |
|---|---|
| `products.json` | All 26 products: specs, packaging, shelf life, applications, seasonality, both image paths, family colours and capacities |
| `company.json` | Company facts, figures, certifications, contacts (film-first figures) |

## tokens/
| File | What |
|---|---|
| `mafi-tokens.css` | CSS custom properties: colour roles, family tags, gradient, type stacks with free fallbacks, radii, shadows |
| `mafi-tokens.json` | The same, platform-neutral |
