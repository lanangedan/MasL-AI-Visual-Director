# Visual Layout Intelligence

> MasL-AI-Visual-Director · Layout decision system  
> Version 1.0 · Initial archetypes derived from user-supplied layout references

## Purpose

Use layout as a deliberate communication decision—not a fixed template. Choose and adapt a wireframe based on the message, audience, content density, visual asset, and intended action.

The wireframes in the companion Layout Archetype Library are **structural references only**. They do not prescribe color, illustration style, typography, or finished artwork.

## Core principles

1. **One primary focal point.** A layout should make the intended first point of attention unmistakable.
2. **Message before decoration.** Reserve space and hierarchy for the information that matters.
3. **Visual Hook is flexible.** It can be a product, person, illustration, photograph, typographic treatment, metaphor, or data visualization.
4. **Hierarchy is not equal sizing.** Headline, visual, supporting copy, and CTA should have distinct roles and relative prominence.
5. **Adapt, do not trace blindly.** Wireframes are starting points; change proportions, positions, or omit blocks when the brief calls for it.
6. **Content earns its space.** Do not add logo, footer, CTA, description, or secondary visuals when they are not required.
7. **Protect readability.** Avoid narrow text columns and overcrowded information blocks; simplify or recommend external typesetting when copy is long.
8. **Preserve asset integrity.** Supplied logos, product images, and identity references must not be redrawn or altered without permission.
9. **Respect the output canvas.** Reflow for the requested aspect ratio and viewing context; do not stretch a layout across incompatible proportions.
10. **No pseudo-content.** Never invent factual copy, prices, specifications, logos, or labels to fill empty blocks.

## Layout archetypes (v1)

### LA-01 — Poster / Hero Visual
- **Structure:** Headline at top → large dominant visual → subheadline → compact supporting description/footer.
- **Best for:** Awareness posters, campaign posters, event announcements, one-message educational posters.
- **Hierarchy:** Headline and hero visual lead; supporting information is secondary.
- **Watch-outs:** Avoid placing too much copy below the visual or shrinking the hero unnecessarily.

### LA-02 — Educational / Information Poster
- **Structure:** Headline → claim/subheadline → central visual → supporting facts around or beside it → CTA/footer.
- **Best for:** Public education, health/safety awareness, explainers, simple information graphics.
- **Hierarchy:** Central visual connects the topic; supporting facts remain clearly grouped and scannable.
- **Watch-outs:** Do not make side labels too narrow. For dense content, use a grid or fewer facts rather than tiny text.

### LA-03 — Product Ad / Center Hero
- **Structure:** Logo (optional) → headline → product hero centered or dominant → concise details on sides → price/CTA/footer.
- **Best for:** Product advertisements, feature announcements, product-focused promotional graphics.
- **Hierarchy:** Product image is the hero; headline and offer are next.
- **Watch-outs:** Keep product silhouette clear. Side details must not compete with the product.

### LA-04 — Food / Promo Visual
- **Structure:** Headline and promise → food/product hero → description or price block → CTA/contact/footer.
- **Best for:** Food promotions, menu highlights, restaurant offers, product promos.
- **Hierarchy:** Appetite/appeal visual and offer should be immediately visible.
- **Watch-outs:** Do not bury price or CTA. Keep food photography believable and visually clean.

### LA-05 — Editorial / Multi-Visual
- **Structure:** Headline → asymmetric grid of multiple visual and text blocks → payoff visual or conclusion → footer/CTA.
- **Best for:** Editorial graphics, explainers, feature summaries, narrative-led visual communication.
- **Hierarchy:** Headline establishes topic; visual blocks create progression; final block resolves or reinforces message.
- **Watch-outs:** Multiple visuals must form a clear reading order, not a collage without purpose.

## Selection logic

Choose an archetype using this order:

1. **Primary communication goal**
   - Awareness / one strong message → LA-01
   - Explain several related points → LA-02
   - Sell or introduce a product → LA-03 or LA-04
   - Tell a visual story or combine several scenes → LA-05
2. **Asset type**
   - One hero photo/product/illustration → hero-centered structure
   - Several distinct visuals → editorial/grid structure
   - No supplied visual → design a purposeful visual hook, not generic decoration
3. **Text density**
   - Low → generous whitespace and large visual
   - Medium → one or two supporting blocks
   - High → reduce copy, group information, or recommend separate typesetting; do not force everything into one image
4. **Required action**
   - CTA/offer must be prominent → reserve a clear CTA zone
   - Informational only → footer may be omitted
5. **Canvas**
   - Recompose for the actual ratio and platform; never stretch blocks mechanically.

## Adaptation checklist

Before generating, internally confirm:
- What is the single core message?
- What should viewers notice first, second, and third?
- What is the Visual Hook and why does it communicate the message?
- Which copy is mandatory, optional, or unnecessary?
- Is there a logo/product/face asset that needs fidelity?
- Does the layout fit the requested aspect ratio and viewing size?
- Is text density realistic for one image?
- Is there any block that exists only as decoration?

Ask the user only when a missing choice materially changes the design. Otherwise select a suitable archetype and proceed.

## Relationship to Visual Style Intelligence

Layout and visual style are separate but coordinated decisions:
- **Layout** determines placement, hierarchy, grouping, and reading order.
- **Style** determines visual language: shapes, texture, color behavior, typography character, rendering, and mood.

Select both to serve the brief. Do not assume a style implies a single layout or combine incompatible visual languages without a reason.

## QA after generation

Check:
- focal point and hierarchy are clear at intended viewing size;
- layout blocks have sensible proportions and spacing;
- text is accurate and legible;
- no accidental pseudo-text or filler elements;
- supplied assets are respected;
- the composition is balanced and the reading order is intentional.

Revise only the failing element(s), preserving what already works.
