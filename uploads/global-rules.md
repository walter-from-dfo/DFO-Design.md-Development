# global-rules.md — Brand Design System Foundation

These rules apply to every template, every product line, every image. No exceptions. Every template file inherits from this document. If a rule here conflicts with a template-specific rule, the template-specific rule wins — but that should be rare. These are the constants.

---

## Typography Stack

Two fonts. No others.

| Role | Font | Notes |
|---|---|---|
| Primary Header | **Neuzeit Grotesk ExtCond Black** | All primary headers across all 11 templates. Extended condensed, maximum weight. Non-negotiable. |
| All other text | **Poppins** | Sub-headers, body, descriptors, labels, captions — all Poppins. Weight varies by role (Regular / Medium / SemiBold / Bold). |

### Why This Pairing Works
Neuzeit Grotesk ExtCond Black is a display font — wide letterforms compressed into a condensed width, which creates extreme visual impact at large sizes. It is the brand's visual voice at its loudest. Poppins is a geometric humanist sans that reads cleanly at all sizes and weights. The contrast between the two is intentional and extreme: Neuzeit headers feel designed; Poppins body text feels approachable. Together they balance authority with warmth.

### Poppins Weight Roles
| Weight | Use |
|---|---|
| Regular | Body copy, supporting detail, fine print, Secondary Subs |
| Medium | Descriptors, measurement callouts, moderate-emphasis body |
| SemiBold | Feature labels, step body text, badges, sub-headers |
| Bold | Measurement dimensions (when specificity is the point) |

Never use Poppins Black or ExtraBold in brand images. Never use Neuzeit for anything except the primary header.

---

## Two-Tone Color Format — The Header Rule

**Threshold: Any header at size 140 or larger MUST use the two-tone format.**

The two-tone format is the single most recognizable brand design signature. It splits the headline across two colors:
- **Word(s) 1 — Base:** Near-black (`#231f20`) or deep navy (`#1d396a`). The setup, the context, the frame.
- **Word(s) 2 — Accent:** The product line's accent color. The emphasis, the punchline, the claim.

### How the Split Works
The break point is always at the natural language emphasis. It's a linguistic decision, not a visual one. The accent color lands on the word that carries the most emotional or informational weight.

| Header | Base (dark neutral) | Accent |
|---|---|---|
| BLISTER BE GONE | BLISTER | BE GONE |
| FIND YOUR FIT | FIND YOUR | FIT |
| CRITICS GIVE IT TWO TOES UP | CRITICS GIVE IT | TWO TOES UP |
| DO MORE OF WHAT YOU LOVE | DO MORE OF WHAT | YOU LOVE |
| MOVE FREELY, HOLD STEADY | MOVE FREELY, | HOLD STEADY |
| ROUGH HEELS, NO MORE | ROUGH HEELS, | NO MORE |

### What the Two-Tone Rule Is NOT
- It is not arbitrary — do not split mid-word or mid-phrase awkwardly.
- It is not optional at the 140+ threshold — a single-color header at large size is not a DFO image.
- It does not apply below 140pt — smaller text (subs, descriptors, labels) is single-color.

### On Dark Backgrounds
When the canvas or header block background is dark (navy, teal), the base word shifts to cream (`#fef5e3`) or white instead of near-black. The accent word remains the product accent color, potentially adjusted to a lighter/brighter variant for contrast.

---

## The Sparkle Graphic — Brand Identity Element

The sparkle is a 4-pointed star shape (rhombus-like, elongated vertically) that appears in groups of 2–3 as a brand signature element. It is present in every template in some form.

### Sparkle Anatomy
There are two cluster configurations:
- **3-Sparkle cluster (standard):** One large sparkle (lower center), one medium sparkle (upper left), one small sparkle (upper right). The three sizes create a visual constellation — not a straight row.
- **2-Sparkle accent:** One large + one small. Used in Social Proof and Doctor Developed where a lighter touch is appropriate.

### Sparkle Colors
Sparkle colors are **product-line specific** — see `color-system.md` for per-SKU assignments. The rule is:
- Each sparkle in the cluster uses a **different shade from the same accent family**.
- The large sparkle (most prominent) takes the **primary/darkest accent shade**.
- The small sparkle(s) take **lighter or secondary tones** from the same family.
- They are never all the same color — tonal variation within the cluster is part of the design.

The brand logo itself uses `#f2c11e` (Vivid Gold) as its sparkle — the full-brand sparkle color when no product accent applies.

### Sparkle Placement Rules
- Near the header text — typically upper right of the last word, or adjacent to the header block.
- Near the product in Feature Dominant — placed at the product's zone of benefit (near the heel, the hand, etc.).
- Never covering the product image.
- Never at the bottom of the canvas below content — sparkles live in the upper half.
- Scale sparkles to the template: headers at 200pt get larger sparkle clusters than headers at 140pt.

### The 3-Color Sparkle Variant
Use Case A is the only template that permits a 3-color sparkle (three different accent tones across the cluster). All other templates use the 2-color sparkle (two tones, one family).

---

## Logo — Colorway Rules

The Dr. Frederick's Original logo exists in four colorway treatments. Match the colorway to the image's background:

| Background | Logo Colorway to Use |
|---|---|
| Dark (navy, deep teal) | Light/cream version — wordmark in cream `#fef5e3`, rule in cream |
| Navy background specifically | Navy-background treatment — confirms contrast is correct |
| Cream or warm white | Standard dark version — wordmark in deep navy `#1d396a` |
| White background | Black/dark version — wordmark in near-black `#231f20` |

The gold sparkle in the logo (`#f2c11e`) remains consistent across all colorway treatments. The "LIVE FULLY™" lockup below the wordmark uses the same color as the wordmark in each treatment.

The thin horizontal rule above the wordmark is in cream (`#fef5e3`) — it's a structural separator, not a decorative element.

### Logo Placement in Templates
The logo does not appear prominently inside most carousel images — the brand is communicated through the design system itself (typography, color, sparkles, wave shapes). When the logo does appear, it's typically:
- Small, in a footer position
- On packaging shown in product images
- In the Cross Sell template as a secondary credibility mark

---

## Wave Shape — Background Divider Element

The wave/swoosh shape is a horizontal, asymmetric curved band. It serves as a content zone divider and background texture. Its single defined color is **`#a8cae4`** (Soft Sky Blue) — extracted directly from `Shapes.svg`.

### What the Wave Shape Is
From `Shapes.svg`, there are 9 distinct wave path variants:
- **Full-width horizontal bands** — span the full canvas width, used as header zone backgrounds or footer grounding elements.
- **Right-tilted variants** — wave rises on the right side, creating a dynamic diagonal energy.
- **Left-tilted variants** — wave rises on the left side, mirroring the right-tilt for compositional balance.
- **Compact bands** — shorter height, used as subtle dividers rather than dominant background elements.

The key characteristic of all variants: the top and bottom edges are **not parallel straight lines** — they curve asymmetrically. This is what makes them "wave" shapes rather than rectangles. The curve creates movement and rhythm.

### Wave Shape Color Rule
The wave in `Shapes.svg` is `#a8cae4` (Sky Blue) — the brand's background/texture color. In product-line specific templates, the wave color can shift to a tint of the product accent, but `#a8cae4` is the default and always acceptable. Never make the wave a saturated accent color — it recedes, it doesn't dominate.

### Wave Shape Placement
- Top of canvas behind the header zone — creates a sky-blue band that frames the headline.
- Bottom of canvas grounding the product zone — anchors the composition.
- Between content zones as a visual separator.
- Never layered over the product image itself.
- Never used at full saturation — the wave is a texture layer, not a focal element.

---

## Canvas Specifications

All templates produce the same output format:

| Spec | Value |
|---|---|
| Dimensions | 2000 × 2000 px |
| Aspect ratio | 1:1 square |
| Primary platform | Amazon product carousel |
| Secondary platform | TikTok Shop |
| Mobile reference width | 375px (all elements must read at this size) |

### Mobile-First Framing Rule
Every image is designed for a 375px screen first. This means:
- Key text (header, feature labels) must be legible at ~1/5th of original size.
- The product must be identifiable at thumbnail size.
- Callout text does not need to be legible at thumbnail — it's a detail-in reward for tap/zoom.
- Center all primary elements — mobile crop zones cut left and right edges.

---

## Layout Principles (Global)

These seven principles apply across all templates. No template overrides them.

1. **One message per image.** Each carousel slot has a single job. Never combine template types.
2. **Product is always visible.** Every template includes at least one clear product photo or in-use shot.
3. **Hierarchy is typographic.** Neuzeit carries the primary message. Poppins layers detail. The size ratio between header and body copy is dramatic — often 3–4×.
4. **Two-tone headers drive the eye.** The color-split headline is a brand signature at 140pt+. No exceptions.
5. **Design elements are functional.** Sparkles = brand identity signal. Waves = content zone dividers. Badges = compressed benefit claims. None are purely decorative — every element earns its place.
6. **Whitespace is generous.** Even data-dense layouts (Comparison Chart, Sizing Chart) maintain clear gutters. The images should feel designed, not crammed.
7. **Brand always wins visually.** In any comparison or cross-sell layout, the DFO product gets the saturated color, the larger image, and the dominant position.
