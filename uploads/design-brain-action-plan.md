# Design Brain — Action Plan

---

## Phase 1: Build the Storage Layer
*No code required. Pure organisation work.*

1. Split `Design.md` into **11 template files** (one per template type). Each file must be fully self-contained — someone should be able to read only that file and know everything needed to produce that template.

2. Create **3 supporting files** that the template files inherit from:
   - `global-rules.md` — two-tone color convention, sparkle graphic, typography stack
   - `color-system.md` — how accent palettes shift per product line
   - `reusable-elements.md` — wave shape, badges, pop-out circle, arrows, etc.

3. Build a **Reference Image Library** — crop each completed template example from `Sample_Images.png` into its own labeled file. Example: `use-case-b-reference.png`, `feature-dominant-reference.png`. These become direct inputs to your image gen calls, not just visual references.

---

## Phase 2: Build the Retrieval Layer
*Start manual, work toward automated.*

4. Write a **Prompt Template** for each of the 11 template types — a structured fill-in-the-blank document with placeholders for product-specific variables: `{{headline_text}}`, `{{accent_color}}`, `{{feature_callouts}}`, `{{product_description}}`. Write these once, reuse accurately every time.

5. Set up a **Claude Project** (one per company). Upload all 11 template files and the reference image library. This becomes your persistent brand brain — every conversation in that project has access to the full design system without re-uploading anything.

6. *When ready to go deeper:* Set up an **OpenWebUI Knowledge Collection** on your local machine using Ollama. Upload the structured template files. Test retrieval accuracy by asking the model specific rule questions before using it for production tasks.

---

## Phase 3: Build the Action Layer
*Manual first, then automate.*

7. Run your first **manual end-to-end test**: take one filled-in prompt template + the matching reference image + the product photo → submit to GPT Image 2 or Nano Banana 2. Validate the concept works before automating anything.

8. Refine prompt templates based on what the model consistently gets right and wrong. Do this across all 11 types before moving to automation.

9. Build an **n8n workflow** to automate the pipeline once manual results are reliable. The four nodes are:
   - Receive product image + template type
   - Call LLM (Claude API or local Ollama) → produces image gen prompt
   - Call GPT Image 2 / Nano Banana 2 API with prompt + reference image
   - Save output image to folder

---

## Key Principles to Keep in Mind

- **Never dump the whole Design.md into a prompt.** The model should only see the rules for the template type it's currently building.
- **Always attach a reference image.** Text descriptions of layout rules are weak. A completed example of the template type is strong.
- **Automate last.** The n8n workflow is only worth building once the manual version works reliably. Automating a broken process just makes failures faster.
- **Same pipeline, different MD.** When you do this for company two, nothing changes structurally — you create a new set of template files and a new Claude Project. The brain is brand-agnostic.
