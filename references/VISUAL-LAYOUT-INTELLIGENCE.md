# Visual Layout Intelligence

> MasL-AI-Visual-Director · Layout decision system  
> Version 2.0 · 21 archetypes

## Purpose

Choose layout as a communication decision—not a decorative template. Match structure to message, audience, visual assets, information density, action, and canvas. Archetype IDs and names correspond to `MasL-Layout-Archetype-Library-21.drawio` and `LAYOUT-INDEX.md`.

## Core principles

1. **One primary focal point.** Make the first point of attention unmistakable.
2. **Message before decoration.** Reserve space for the information that matters.
3. **Visual Hook is flexible.** It can be a product, person, illustration, photograph, metaphor, typography, or data visualization.
4. **Hierarchy is not equal sizing.** Headline, visual, supporting copy, and CTA need distinct roles.
5. **Adapt, do not trace blindly.** Change proportions, positions, or omit blocks when the brief calls for it.
6. **Content earns its space.** Do not add logos, footers, CTAs, descriptions, or secondary visuals without a purpose.
7. **Protect readability.** Avoid narrow columns and overcrowded blocks; simplify or recommend external typesetting for long copy.
8. **Preserve asset integrity.** Supplied logos, product images, and identity references must not be redrawn or altered without permission.
9. **Respect the canvas.** Recompose for the requested ratio; never stretch a layout mechanically.
10. **No pseudo-content.** Never invent factual copy, prices, specifications, logos, or labels to fill space.

## Archetype decision map (LA-01–LA-21)

| ID | Archetype | Choose when | Main caution |
|---|---|---|---|
| LA-01 | Poster / Hero Visual | One strong message and one dominant visual | Supporting copy must not shrink the hero |
| LA-02 | Educational / Info Poster | Several related facts explain one concept | Side facts must remain readable |
| LA-03 | Product Ad / Center Hero | Product silhouette/appearance is the main selling point | Side details cannot compete with product |
| LA-04 | Food / Promo Visual | Appetite, offer, or food item drives action | Keep price/CTA easy to find; food believable |
| LA-05 | Editorial / Multi-Visual | Multiple scenes or ideas need a visual reading sequence | Avoid collage without progression |
| LA-06 | Split Hero / Side Copy | A hero subject and explanatory copy need equal but distinct zones | Balance zones; avoid cramped copy |
| LA-07 | Top Visual / Bottom Info | Image should attract first, details follow below | Bottom band must not become dense |
| LA-08 | Center Hero / Framing | A central subject benefits from framing/supporting elements | Framing must not obscure the hero |
| LA-09 | Headline + Visual + Two Details | Exactly two key facts/benefits support the hero | Keep the two detail blocks distinct |
| LA-10 | Alternating Visual / Text | Sequential points or a short visual narrative | Establish clear reading order |
| LA-11 | Info Grid / Central Message | Several modular facts orbit a central message | Grid should not fragment the core idea |
| LA-12 | Typographic Statement | The words themselves are the main visual impact | Typography must be legible, intentional, and exact |
| LA-13 | Headline / Visual / Description | Straightforward headline, one visual, short explanation | Avoid unnecessary sections |
| LA-14 | Logo + Headline + Hero | Brand identity is required and supplied/approved | Preserve logo fidelity and give it proper scale |
| LA-15 | Headline + Central Visual + Side Details | Central object/concept needs multiple annotations | Side labels need breathing room |
| LA-16 | Headline + Visual + Detail Grid | Hero plus several compact features/specs | Reduce detail count before reducing type size |
| LA-17 | Headline + Central Illustration | A metaphor or illustration can explain the concept | Illustration should clarify, not merely decorate |
| LA-18 | Educational Three-Column | Three categories, stages, or comparison points are meaningful | Columns need parallel structure and concise copy |
| LA-19 | Logo + Top Copy + Hero + Footer | Branded message requires top framing and closing CTA/info | Do not overpopulate both top and footer |
| LA-20 | Header + Hero + Device Showcase | App, website, or software needs a device/screen presentation | Screens should be plausible; avoid fake UI text |
| LA-21 | Header + Visual + Footer (Clean) | Minimal composition with one visual and compact support | Keep whitespace purposeful; avoid adding blocks |

## Selection algorithm (use in this order)

### 1. Communication goal
- Awareness / one-message campaign → LA-01 or LA-21
- Explain several related facts → LA-02, LA-11, LA-16, or LA-18
- Sell/introduce product → LA-03, LA-08, LA-15; food/offer → LA-04
- Narrative or several scenes → LA-05 or LA-10
- Strong quote/opinion → LA-12
- App/site/software → LA-20
- Brand-led announcement → LA-14 or LA-19

### 2. Asset shape
- One hero asset → LA-01, LA-03, LA-07, LA-13, LA-21
- Subject with copy beside it → LA-06
- Central subject with annotations → LA-08 or LA-15
- Multiple distinct assets → LA-05 or LA-10
- No supplied visual → select a purposeful visual hook; LA-17 is useful for conceptual explanation

### 3. Content structure and density
- One short message → LA-12 or LA-21
- Headline + one visual + short explanation → LA-13
- Exactly two benefits/facts → LA-09
- Several modular facts → LA-02, LA-11, or LA-16
- Three parallel categories/stages → LA-18
- Sequential narrative → LA-10
- Dense content → group, prioritize, or remove copy; do not force tiny text into a single image

### 4. CTA / required information
- Offer/action must be prominent → reserve an explicit CTA zone; LA-04 or LA-19 may help
- Brand identity is required → LA-14 or LA-19, only with a supplied/approved logo
- Informational only → omit CTA/footer if unnecessary

### 5. Canvas and placement
Recompose layout for portrait, square, or landscape. Preserve hierarchy and reading order; do not scale narrow columns into illegibility. Account for platform crop and safe margins.

## Hybrid layouts

Use a hybrid only if:
- two archetypes solve distinct needs that one cannot;
- the combination has a clear reading order and single focal point;
- blocks are not duplicated merely for decoration.

State the hybrid internally as IDs (e.g. LA-06 + LA-13); do not expose archetype jargon unless it helps the user.

## Adaptation checklist

Before generation, confirm internally:
- What is the single core message?
- What should viewers notice first, second, and third?
- What is the Visual Hook and why does it communicate the message?
- Which copy is mandatory, optional, or unnecessary?
- Is there a logo/product/face asset requiring fidelity?
- Does the layout fit the requested aspect ratio and viewing size?
- Is text density realistic for one image?
- Is any block present only as decoration?

Ask only when a missing choice materially changes the design. Otherwise choose and proceed.

## Relationship to Visual Style Intelligence

- **Layout** determines placement, hierarchy, grouping, and reading order.
- **Style** determines visual language: shapes, texture, color behavior, typography character, rendering, and mood.
- Select both to serve the brief. Do not assume a style implies a single layout or combine incompatible visual languages without reason.

## QA after generation

Check:
- focal point and hierarchy are clear at intended viewing size;
- blocks have sensible proportions and spacing;
- text is accurate and legible;
- no pseudo-text or filler elements;
- supplied assets are respected;
- composition is balanced and reading order is clear;
- canvas ratio and safe margins fit the intended platform.

Revise material defects before presenting the design as final. Be candid about limitations.
