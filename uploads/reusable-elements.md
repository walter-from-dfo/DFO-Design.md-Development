# reusable-elements.md — Shared Design Components

These are the recurring design components that appear across multiple templates. Each element has a defined appearance, behavior, and set of rules. When a template file says "Wave Shape — accent color," this document defines exactly what that means. Think of this as the component library.

---

## 1. Wave Shape

**Used in:** Feature Dominant, Product Details, Use Case B, How It Works, Sizing Chart
**Source file:** `Shapes.svg` — all paths, color `#a8cae4`

### What It Is
A horizontal, asymmetric curved band. Not a rectangle — the top and bottom edges curve in different directions, creating an organic wave-like silhouette. The shape has soft, sweeping geometry — it reads as a landscape element, not an architectural one.

### The 9 Shape Variants in Shapes.svg
`Shapes.svg` contains 9 distinct path variants, all in `#a8cae4`:
1. **Bottom-right panel** — fills the lower-right quadrant, top edge waves upward to the left.
2. **Top-right panel** — fills the upper-right area, bottom edge waves downward to the left.
3. **Bottom-left panel** — fills the lower-left quadrant, top edge waves upward to the right.
4. **Top-left panel** — fills the upper-left area, bottom edge waves downward to the right. This is the classic background "swoosh" behind DFO product images.
5. **Top-right narrow** — thinner variant, used as a subtle top band.
6. **Center horizontal band** — a full-width band with wave edges top and bottom.
7. **Bottom-center band** — anchors the bottom of the canvas.
8. **Wide horizontal top band** — fills the full width, used as a header zone background.
9. **Wide horizontal bottom band** — fills the full width, grounding element.

### Color Rules
- **Default:** `#a8cae4` (Soft Sky Blue) — the color defined in Shapes.svg.
- **Product-specific tint:** The wave color can shift to a light tint of the product accent (e.g., a very light teal for teal-accented products). When doing this, the wave should be at 20–40% of the accent saturation — never full color.
- **Never:** Saturated solid color. The wave recedes; it does not dominate.

### Placement Rules
- Behind the header zone (top of canvas) — creates a sky-blue or soft-accent band framing the headline.
- Behind the product image (bottom of canvas) — grounds the product composition.
- As a content zone separator between header and body.
- Never overlapping the product image itself.
- Never at full opacity on a white background where it would create a hard-edged rectangle feel — keep it soft.

---

## 2. Gentle Curve Shape

**Used in:** How It Works, Use Case B
**Distinction from Wave:** The gentle curve is subtler — a softer arc rather than a full wave band. It appears at the bottom of the canvas as a grounding element, with less visual weight than the wave shape.

### What It Is
Where the wave shape is a full horizontal band with two curving edges, the gentle curve is more like a single curved horizon line — the canvas bottom transitioning into a soft arc. It creates a sense of ground or surface beneath the content.

### Color Rules
Same palette as the wave shape — `#a8cae4` or a light accent tint. Always lower visual intensity than the wave when both appear in the same image.

### Placement
- Bottom of the step grid in How It Works — beneath the last row of step panels.
- Bottom grounding in Use Case B — below the product image.
- Never appears alone without the wave shape in the same template.

---

## 3. Three-Sparkle Brand Graphic (2-Color)

**Used in:** Feature Dominant, Comparison Chart, Use Case A, Product Details, Sizing Chart, and as accent in most others
**Source:** Sparkles_1.png through Sparkles_11.png (per-palette variants)

### What It Is
Three 4-pointed star shapes (elongated rhombus form, pointed at top/bottom and left/right) arranged in a specific spatial relationship:
- **Large sparkle** — lower center. Primary accent color. Most visually dominant.
- **Medium sparkle** — upper left. Secondary accent color (lighter or different tone from same family).
- **Small sparkle** — upper right. Tertiary accent color (lightest tone in the family).

The three sparkles do not sit in a straight row or grid. They form a loose cluster — a constellation arrangement that feels organic rather than mechanical. The large one anchors; the medium and small float above and beside it.

### The 2-Color Rule
"2-color" means two distinct hues from the same accent family — not two identical colors. The large sparkle and the medium sparkle share the same family but are different tones. The small sparkle is the lightest, often nearly white or a very light tint.

Examples from the reference sparkle images:
- **Navy/Blue palette:** Large = deep navy `#1d396a`, Medium = teal `#186972`, Small = sky blue `#a8cae4`
- **Orange/Amber palette:** Large = warm orange `#e28433`, Medium = amber gold `#f6ab25`, Small = light gold `#f5db8b`
- **Red/Maroon palette:** Large = maroon `#ac382d`, Medium = amber `#f6ab25`, Small = light gold
- **Teal palette:** Large = deep teal `#186972`, Medium = sage `#719484`, Small = light sage

### The 3-Color Sparkle Variant
Permitted only in Use Case A. Three genuinely different hues — not just tonal variations of one family. Use when the product line has a rich multi-color identity.

### Placement Rules
- Always near the header text — typically upper right of the last line, adjacent to the header block, or floating above the product in the hero zone.
- In Comparison Chart: appears inside or adjacent to the brand column header.
- In Feature Dominant: placed near the product, at the zone the product benefits (near the heel, hand, etc.).
- In Sizing Chart: prominent — upper right or beside the header. The sizing chart's sparkle support color should match the product material color.
- Scale with the template: 200pt header = larger sparkle cluster; 140pt header = smaller cluster.
- Never covering the product image.
- Never below mid-canvas.

### The Sparkle Support Color Rule (Sizing Chart specific)
In the Sizing Chart template, the medium or small sparkle's color should **echo the product's physical material color**. If the sock is pink, the support sparkle is pink. If the glove is charcoal gray, the support sparkle is a cooler gray. This detail ties the graphic to the product in a way that reads as intentional and designed.

---

## 4. Drop Shadow

**Used in:** Feature Dominant (primary), others as needed

### What It Is
A soft shadow applied beneath a product cutout image to lift it visually from the background. Not a hard-edged box shadow — a soft, natural shadow that reads like the product is resting on a surface or floating just above the background.

### When It's Required
Mandatory in Feature Dominant when the product's packaging/material color is close to the background color. Without it, the product edge blurs into the background and the product loses its visual presence.

### Shadow Specifications
- **Blur radius:** Generous — 20–40px equivalent. Soft edge.
- **Opacity:** 20–35%. Subtle, not dramatic.
- **Direction:** Downward and slightly right — standard light-from-upper-left convention.
- **Color:** Dark neutral (`#231f20`) or very dark navy. Never colored shadows.

### When to Skip
When the product is photographed on a contrasting background and the edge reads clearly without shadow. Use judgment — if you can see the product's outline without the shadow, skip it.

---

## 5. Pop-Out Circle Detail

**Used in:** Use Case B exclusively

### What It Is
A circular crop of the product's most compelling material or structural detail, placed floating beside or above the product image. It functions as a magnification annotation — "look more closely here."

### Anatomy
- **Circle shape:** Perfect circle crop. Diameter roughly 20–25% of the canvas width.
- **Outline:** Thick border in the product's primary accent color. This is the most visually prominent part of the element — the outline should be bold enough to read at thumbnail size.
- **Content:** The zoomed-in detail — grip dots, gel material, compression weave, moisture-wicking texture, medication/ingredient surface, etc. Should show something a customer couldn't see in the hero product shot.
- **Connecting arrow:** A single directional arrow pointing from the source zone on the product to the pop-out circle. Color matches the circle outline exactly — same hex, same weight.

### Rules
- The arrow and the circle outline must be the **exact same color** — they are one visual system.
- The arrow should feel hand-indicated, not CAD-precise. A slightly curved or angled arrow is more human than a perfectly straight one.
- The circle should float — never flush with the canvas edge. It needs visual breathing room.
- The content inside the circle must be genuinely revelatory — there's no point in cropping a generic area. The zoom must justify itself.

---

## 6. Badges

**Used in:** Use Case B (primary), Sizing Chart, Problem Solution

### What It Is
Small rounded icon shapes — a white symbol on a solid colored background. Each badge communicates one benefit, attribute, or care instruction in icon form. They compress information that would otherwise be a text list into a visual scanning system.

### Anatomy
- **Shape:** Rounded rectangle or circle. Consistent across all badges in the same image.
- **Background:** Product accent or complementary color. Must contrast strongly with both the badge symbol and the canvas background.
- **Symbol:** White. Simple, recognizable line icon. Should communicate its meaning without a label (though it always has a label beneath it).
- **Label:** Poppins SemiBold below the badge shape. 2–4 words maximum.

### Badge Color Rule
Badge backgrounds are **complementary to the primary accent, not identical to it**. If the primary accent is teal `#186972`, badge backgrounds might be a deeper teal, a contrasting navy, or a warm amber. They share the accent family's energy but don't duplicate the header's exact color — otherwise the badges visually compete with the header.

### Badge Symbol Design Principles
- Line icons only — no filled silhouettes, no photorealistic images.
- White on color — always. Never dark symbols on light badges.
- The icon should be legible at 24px equivalent width. If it requires detail to understand at that size, simplify it.
- Common DFO badge icons: anti-slip dots, compression gradient, washing hand, air dry, no-latex symbol, hypoallergenic leaf, temperature, grip lines, heart, medical cross.

### Badge Arrangement
- Vertical list — stacked top to bottom with consistent spacing.
- 4–6 badges per image. Below 4 feels sparse; above 6 becomes a list that nobody scans.
- Aligned to one side of the canvas — typically right edge.

---

## 7. Tab Feature Element

**Used in:** Product Details (primary), Use Case B

### What It Is
A small tab or flag-shaped accent element — like a file folder tab or a price tag shape. It labels a specific variant, SKU, model, or attribute without requiring a callout line or arrow. It sits directly adjacent to the relevant content.

### Appearance
- Shape: Rounded rectangle with a small notch or pointed end — the "tab" feeling.
- Color: Product accent, or a complementary darker tone.
- Text: Poppins SemiBold. Short — 1–3 words. Model identifier, color name, or key attribute.
- Scale: Small — never larger than the text it labels. A tab is a label anchor, not a headline.

### Placement
- Adjacent to the product image in Product Details — labels a specific size, variant, or component.
- Near the header block in Use Case B — identifies the product line or a feature tier.

---

## 8. Authority Signature Block

**Used in:** Doctor Developed (primary), Cross Sell

### What It Is
The personal endorsement element. It personalizes the brand and makes the physician identity concrete. Three parts:
1. **Script signature:** The doctor's handwritten name — "— Dr. Frederick" — in a genuine handwritten or handwritten-style script font. Prefixed with an em dash for attribution grammar.
2. **Printed credentials:** Full name + degree — "Ben Frederick, MD" — in Poppins SemiBold beneath the signature.
3. **Portrait photo** (Doctor Developed only): A professional headshot or half-body photo of the doctor. Warm lighting, lab coat, confident but approachable pose.

### The Signature Authenticity Rule
The script signature must look genuinely handwritten — casual professional, like a Sharpie on a letter. It must not look like a calligraphy font or a decorative typeface. If it looks designed, it destroys the credibility it was meant to create. When generating with AI: "handwritten cursive signature, casual professional, not calligraphy."

### Spacing Rule
There should be a consistent gap between the script signature line and the printed credentials — the same gap you'd see in a business letter closing. This makes the block read as a formal attribution.

---

## 9. Day-Count Badges

**Used in:** Problem Solution (Before/After variant)

### What It Is
Small colored pill shapes containing a timeline indicator — "1 Day", "6 Days", "4 Weeks" — that overlay the before/after photo pairs. They make the transformation claim specific and credible.

### Anatomy
- Shape: Rounded rectangle pill — small, compact.
- Background: Product primary accent fill.
- Text: Poppins SemiBold, white. Short — "1 Day", "6 Days". Nothing longer.
- Placement: Upper right or upper left corner of the before/after pair, overlapping slightly into the photo.

### The Specificity Rule
The day count must be accurate and honest. "1 Day" means one night of use. "6 Days" means six nights using the recommended routine. These are claims that customers can hold you to — only use counts that reflect real typical outcomes.

---

## 10. Connecting Arrows (How It Works)

**Used in:** How It Works / How To Use (primary), Use Case A (annotation system)

### Two Distinct Arrow Types

**Type A — Step Navigation Arrows (How It Works)**
- Directional arrows between step panels, guiding the eye from step to step.
- Must be the **exact same color as the header accent word** — not neutral, not close. Exact hex.
- Simple chevron or curved arrow shape — clean, clear direction. Not decorative.
- Scale to match the step number size — arrows should be prominent enough to see at thumbnail.

**Type B — Annotation Arrows (Use Case A, Use Case B)**
- Curved arrows pointing from a label to a specific zone in the product photo or body image.
- Color: Product accent. Should feel hand-indicated — slightly curved or organic, not mechanical.
- Appear alongside the pop-out circle element in Use Case B — always same color as the circle outline.
- In Use Case A, appear within grid cells pointing from the zone label to the annotated body zone.

### Arrow Rules That Apply to Both Types
- Never gray or neutral — colored arrows are directional signals. Gray arrows read as inactive.
- Never decorative — no arrowhead styles, no double arrows, no flourishes. Function only.
- Always pointing clearly in one direction — never ambiguous.
