# color-system.md — Per-Product-Line Accent Palettes

Color in this brand system is not fixed. It shifts per product line. Every SKU family has its own accent palette — a primary accent, a secondary accent, and a set of supporting tones — that flows through headers, badges, sparkles, wave shapes, and background tints. The structural rules are the same for every palette; only the hues change.

All hex values below are sourced directly from `Color_Palette.svg` and `Logo.svg`.

---

## The Fixed Colors — These Never Change

These colors appear across all product lines regardless of accent palette.

| Role | Name | Hex | Usage |
|---|---|---|---|
| Dark Text / Header Base | Near Black | `#231f20` | Primary header base word on light backgrounds |
| Primary Navy | Deep Navy | `#1d396a` | Header base word alternative, brand column fills, dark backgrounds |
| Primary Navy Alt | Dark Navy | `#10426c` | Alternative navy for deep backgrounds — nearly identical to Deep Navy, slightly darker |
| Background Warm | Warm Cream | `#fef5e3` | Warm, premium background tone. Also used as text on dark backgrounds. |
| Background Cream Alt | Cream Alt | `#fcf4e3` | Slightly cooler cream variant — appears in both SVGs. Nearly identical to Warm Cream. Use either. |
| Sky Blue (Wave) | Soft Sky Blue | `#a8cae4` | Wave/swoosh shape color. Background texture. Sourced directly from Shapes.svg. |
| Sky Blue (Logo) | Logo Sky Blue | `#98cae5` | The sky blue used in the logo system — near-identical to wave blue. For logo-adjacent elements. |

---

## Accent Palette System — How It Works

Each product family has an **accent color set**: a cluster of 2–4 related hues pulled from the same color family. These accent colors:

- **Replace** the emphasis word in the two-tone header
- **Fill** the brand column in comparison charts
- **Color** the sparkle cluster (primary + secondary tones)
- **Tint** wave shapes and background zones
- **Fill** badge backgrounds and checkmark circles
- **Outline** pop-out circle details and arrows

The accent set is always internally consistent — you never mix accent colors from different product families in the same image.

---

## Product Line Accent Palettes

### Navy / Teal Family — Core Brand Palette
**Products:** Compression Gloves, Arch Support Sleeves, and other core therapeutic products

| Role | Name | Hex | Notes |
|---|---|---|---|
| Primary Accent | Teal | `#186972` | Header emphasis, brand column fills, primary sparkle |
| Secondary Accent | Aqua | `#10ada8` | Secondary sparkle, tonal variation in step panels |
| Support | Deep Forest Teal | `#023f46` | Darkest teal — deep backgrounds, dark variants |
| Light Accent | Sky Blue | `#a8cae4` | Wave shapes, background tints |

**Header example:** "CHOOSE BETTER" (navy `#1d396a`) + "LIVE FULLY" (teal `#186972`)
**Sparkle set:** Primary sparkle in `#186972`, secondary sparkle in `#10ada8`, accent sparkle in `#a8cae4`

---

### Blue Family — Bandage / Wound Care Products
**Products:** Better Blister Bandages, Hydrocolloid products

| Role | Name | Hex | Notes |
|---|---|---|---|
| Primary Accent | Bright Blue | `#2c90ca` | Header emphasis, brand fills, sparkle primary |
| Secondary Accent | Sky Blue | `#a8cae4` | Secondary sparkle, background tints |
| Dark Support | Navy | `#1d396a` | Deep backgrounds, column fills |
| Teal Support | Teal | `#186972` | Product details, step backgrounds |

**Header example:** "BLISTER" (navy `#1d396a`) + "BE GONE" (blue `#2c90ca`)
**Note:** This palette was evident in the Use Case A and Product Details reference images — sky blue blocks, blue annotation arrows.

---

### Orange / Amber Family — Warm/Festive Products
**Products:** Gel Heel Socks (some colorways), seasonal products

| Role | Name | Hex | Notes |
|---|---|---|---|
| Primary Accent | Warm Orange | `#e28433` | Header emphasis, brand column, primary sparkle |
| Secondary Accent | Amber Gold | `#f6ab25` | Secondary sparkle, tonal variation |
| Vivid Accent | Vivid Gold | `#f2c11e` | Brightest gold — logo sparkle color, highlight details |
| Light Accent | Light Gold | `#f5db8b` | Background tints, very light accent zones |

**Header example:** "HAPPY" (near-black `#231f20`) + "HEALING" (orange `#e28433`)
**Note:** The Product Details reference images (bandage packaging) use this palette — warm cream background, orange/amber accent elements.

---

### Red / Maroon Family — Gift / Premium Products
**Products:** Heel Socks (gift packaging), premium colorways

| Role | Name | Hex | Notes |
|---|---|---|---|
| Primary Accent | Deep Red/Maroon | `#ac382d` | Header emphasis, brand fills, primary sparkle |
| Secondary Accent | Deep Burgundy | `#812525` | Darker variant — backgrounds, depth |
| Warm Accent | Coral Red | `#cc4727` | Mid-tone accent — arrows, badges |
| Support | Amber | `#f6ab25` | Sparkle support color |

**Header example:** "GIFTABLE" (dark neutral) + "SELF CARE" (maroon `#ac382d`)
**Note:** Seen in the Cross Sell reference image for the heel sock gifting variant — deep maroon/purple background, warm amber sparkles. This is the product's "gift occasion" palette.

---

### Green / Sage Family — Natural / Wellness Products
**Products:** Foot Cream (FC01), natural/organic-positioned SKUs

| Role | Name | Hex | Notes |
|---|---|---|---|
| Primary Accent | Forest Green | `#3d5d2b` | Header emphasis, brand fills |
| Secondary Accent | Sage | `#719484` | Secondary sparkle, background tints |
| Light Accent | Soft Sage | `#b6c1ac` | Background tints, support tones |
| Gold Support | Warm Gold | `#cfb06b` | Luxury signal — sparkle support, detail accents |

**Header example:** "LESS ROUGH." (dark neutral) + "MORE YOU." (forest `#3d5d2b`)
**Note:** This palette pairs well with the Warm Cream background — green on cream reads as natural, therapeutic, botanical.

---

### Pink / Rose Family — Soft/Comfort Products
**Products:** Fuzzy Heel Socks, comfort-positioned products

**Note:** The pink/rose palette appears in the Sizing Chart reference image (fuzzy sock) and several Feature Dominant variants. The exact pinks are not in the core SVG files — they appear to be product-specific accent colors used for those SKU families. When building images for pink-accented products, the designer provides the specific pink hex as part of the product brief. The brand structure (two-tone header, sparkle with support color matching the product material) remains the same.

General guidance: the sparkle support color for the pink family should match the product's physical material color — if the sock is pale pink, the secondary sparkle echoes that pink. This rule is explicit in the Sizing Chart template rules.

---

## Color Usage Rules — Apply to Every Palette

These rules hold regardless of which accent palette is active:

| Context | Rule |
|---|---|
| Header base word | `#231f20` (near-black) or `#1d396a` (deep navy) — always dark, always neutral |
| Header accent word | Product line primary accent — saturated, confident |
| Background | White, warm cream, or very light tint of the product accent — never saturated |
| Brand column (comparison chart) | Product primary accent — full saturation |
| Competitor columns | Muted gray tones — `#c4c6b8` or similar — always visually receding |
| Badge icon backgrounds | Complementary to the primary accent — not identical, not neutral |
| Badge symbols | Always white (`#ffffff`) — no exceptions |
| Wave shapes | `#a8cae4` (default) or a soft tint of the product accent — never full saturation |
| Arrows (How It Works) | Exact hex of the header accent word — same color, same shade |
| Pop-out circle outlines | Product primary accent — high contrast against both background and product |

---

## The Dark Background Rule

Several templates have light and dark background variants. When the background is dark:

| Element | Light Background | Dark Background |
|---|---|---|
| Header base word | `#231f20` or `#1d396a` | `#fef5e3` (cream) or `#ffffff` (white) |
| Header accent word | Product accent (saturated) | Product accent — may use lighter variant for contrast |
| Body copy | `#231f20` | `#fef5e3` or `#ffffff` |
| Background | White / light cream | `#1d396a` (deep navy) or `#10426c` (dark navy) or `#023f46` (deep teal) |

Dark backgrounds are used in:
- Doctor Developed (authoritative variant)
- Social Proof header block
- Comparison Chart brand column
- How It Works (premium variant)
- Feature Dominant (some product lines)

---

## Quick Reference — All Extracted Hex Values

Sourced from `Color_Palette.svg` and `Logo.svg`. Complete master list.

### Neutrals & Structure
- `#231f20` — Near Black (dark text, header base)
- `#fef5e3` — Warm Cream (background, light text on dark)
- `#fcf4e3` — Cream Alt (background variant)
- `#ffffff` — White

### Navy Family
- `#1d396a` — Deep Navy (primary brand color)
- `#10426c` — Dark Navy (deep background variant)
- `#15345a` — Deep Navy 3 (darker variant)
- `#152740` — Very Dark Navy (deepest variant)
- `#184377` — Navy 4
- `#2c4d70` — Navy 5 (lighter)

### Teal Family
- `#186972` — Teal (primary product accent for therapeutic line)
- `#10ada8` — Aqua (bright, energetic teal accent)
- `#023f46` — Deep Forest Teal (very dark teal background)
- `#026489` — Dark Teal (mid-dark teal)

### Blue Family
- `#a8cae4` — Soft Sky Blue (wave shapes — Shapes.svg source)
- `#98cae5` / `#98cbe7` — Logo Sky Blue (near-identical to wave blue)
- `#2c90ca` — Bright Blue (product accent for bandage/wound care line)

### Orange / Amber / Gold Family
- `#e28433` — Warm Orange/Amber (product accent)
- `#e38533` — Orange variant (near-identical to above)
- `#ec7e23` — Brighter Orange
- `#f6ab25` — Amber Gold
- `#f8ac27` — Warm Amber (near-identical to above)
- `#f2c11e` — Vivid Gold (logo sparkle, brand signature)
- `#cfb06b` — Warm Gold (muted, luxury signal)
- `#f5db8b` — Light Gold (very soft, background tints)

### Red / Maroon Family
- `#cc4727` — Coral Red
- `#ac382d` — Warm Red/Maroon
- `#812525` — Deep Burgundy

### Green / Sage Family
- `#3d5d2b` — Forest Green
- `#719484` — Sage (muted green-gray)
- `#747f35` — Olive Green
- `#b6c1ac` — Soft Sage Gray
- `#c4c6b8` — Light Sage Gray (competitor column neutral)
