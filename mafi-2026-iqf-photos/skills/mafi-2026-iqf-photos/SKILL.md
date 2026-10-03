---
name: mafi-2026-iqf-photos
description: >
  This skill should be used when a MAFI design or document needs the top-view (overhead) photo of an
  IQF / Frozen Fruits & Vegetables product: IQF strawberry, mango, pomegranate, sweet potato, carrots,
  cauliflower, sweet corn, corn-on-the-cob, green beans, green peas, broccoli or artichoke. It is the
  companion to the "mafi-2026" brand skill and holds the 12 IQF top-view product photos in full 4K resolution.
metadata:
  version: "1.0.0"
  display-name: "MAFI 2026 – IQF Photos"
---

# MAFI 2026 – IQF Photos

This skill holds the **12 IQF top-view product photos** from the MAFI 2026 brand pack, unchanged: full resolution, transparent background, overhead view in a white bowl. All paths are relative to this skill's base directory.

| Product | File |
|---|---|
| IQF Strawberry | `assets/products/top-view/iqf/iqf-strawberry.png` |
| IQF Mango | `assets/products/top-view/iqf/iqf-mango.png` |
| IQF Pomegranate | `assets/products/top-view/iqf/iqf-pomegranate.png` |
| IQF Sweet Potato | `assets/products/top-view/iqf/iqf-sweet-potato.png` |
| IQF Carrots | `assets/products/top-view/iqf/iqf-carrots.png` |
| IQF Cauliflower | `assets/products/top-view/iqf/iqf-cauliflower.png` |
| IQF Sweet Corn | `assets/products/top-view/iqf/iqf-sweet-corn.png` |
| IQF Corn-on-the-Cob | `assets/products/top-view/iqf/iqf-corn-on-the-cob.png` |
| IQF Green Beans | `assets/products/top-view/iqf/iqf-green-beans.png` |
| IQF Green Peas | `assets/products/top-view/iqf/iqf-green-peas.png` |
| IQF Broccoli | `assets/products/top-view/iqf/iqf-broccoli.png` |
| IQF Artichoke | `assets/products/top-view/iqf/iqf-artichoke.png` |

- **Get the rules from `mafi-2026`.** Follow that brand skill for everything else: brand rules, product specs (`02_Products.md`), colours, typography and layout. Load it first if it isn't loaded yet.
- **Use the image paths as given.** They match the `image_top_view` paths in that skill's `data/products.json` and `02_Products.md`.
- **Use one image direction per layout.** Don't mix top-view and glass-bowl images in the same row.
- **Copy before use.** When building HTML, artifacts, documents or design files, copy the needed images into the working or output folder and reference the copies.
