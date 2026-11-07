# UAT INSTRUCTIONS — MASL-AI VISUAL DIRECTOR

## Purpose
Validate whether MasL-AI-Visual-Director consistently selects an appropriate layout archetype (LA-01–LA-21), art direction, hierarchy, and visual density—and produces a polished, communication-first single-image design.

UAT evaluates the **design decision and output**, not merely whether an image can be generated.

## How to Run a Test
For each test case:

1. Read and follow `PROJECT-INSTRUCTIONS.md` and `SKILL.md`.
2. Interpret the brief without inventing facts or copy.
3. Identify the selected layout archetype (LA-ID + name) and briefly justify it using the layout intelligence references.
4. State the intended hierarchy, focal point, composition, and text strategy.
5. If the brief is actionable, proceed to generate the final design. Do not stop at a wireframe unless explicitly requested.
6. Inspect the result against the acceptance criteria below.
7. Record failures and propose targeted revisions.

## Test Cases

### UAT-A — Simple Campaign Poster (Baseline)
**Brief:** Create a campaign poster for a community digital-literacy event. Main headline: “Cerdas Digital, Aman Bersama”. Supporting copy: “Kenali risiko. Lindungi data. Bijak berinternet.” No date, venue, organizer, or CTA is supplied; do not invent them.

**Expected direction:** One dominant message, one clear hero visual, restrained supporting copy.
**Candidate layouts:** LA-01 Poster / Hero Visual or LA-21 Header + Visual + Footer (Clean).
**Test focus:** Baseline hierarchy, restraint, text fidelity, and avoiding fabricated event details.

### UAT-B — Cybersecurity Educational Poster
**Brief:** Create an educational poster titled “5 Kebiasaan Aman di Internet” with these exact points:
1. Gunakan kata sandi unik
2. Aktifkan autentikasi dua faktor
3. Periksa tautan sebelum klik
4. Jangan bagikan kode OTP
5. Perbarui perangkat dan aplikasi

Audience: students and beginner internet users. Tone: approachable, clear, not frightening. No statistics or additional claims.

**Expected direction:** Headline → five scannable tips → concise visual support.
**Candidate layouts:** LA-02 Educational / Info Poster or LA-16 Headline + Visual + Detail Grid.
**Test focus:** Information hierarchy, density, readability, and grouping.

### UAT-C — Product Promotion (Two Benefits)
**Brief:** Promote a fictional productivity app named “Fokus”. Headline: “Kerja Lebih Fokus”. Benefits: “Atur prioritas” and “Pantau progres”. CTA: “Coba Fokus”. No pricing, ratings, or performance claims.

**Expected direction:** Product/app hero, two benefits, clear CTA.
**Candidate layouts:** LA-03 Product Ad / Center Hero or LA-09 Headline + Visual + Two Details.
**Test focus:** Product hierarchy, benefit placement, and CTA clarity.

### UAT-D — Three-Scene Visual Story
**Brief:** Create a visual storytelling poster showing a beginner's journey: (1) overwhelmed by notifications, (2) learning to manage digital habits, (3) confidently using technology. No additional explanatory copy is required.

**Expected direction:** Three distinct but connected visual beats with a clear progression.
**Candidate layouts:** LA-05 Editorial / Multi-Visual or LA-10 Alternating Visual / Text.
**Test focus:** Narrative sequence, visual continuity, and avoiding clutter.

### UAT-E — Mobile App Promotion
**Brief:** Promote a mobile app called “RuangBelajar”. Main headline: “Belajar, di Mana Saja”. Show a smartphone with a generic learning interface. Supporting copy: “Materi ringkas. Belajar fleksibel.” CTA: “Mulai Belajar”. Do not invent app features beyond the supplied copy.

**Expected direction:** Prominent device/app visual, headline, supporting copy, CTA.
**Candidate layout:** LA-20 Header + Hero + Device Showcase.
**Test focus:** Device showcase, screen plausibility, hierarchy, and text fidelity.

## Acceptance Criteria
Score each item from 1–5 (1 = poor, 3 = acceptable, 5 = excellent):

- **Brief fidelity:** all supplied facts and exact copy preserved; no invented claims.
- **Layout fit:** selected archetype supports the communication goal and content.
- **Hierarchy:** primary message and focal point are immediately clear.
- **Readability:** text is legible and appropriately prioritized for the format.
- **Composition:** balance, spacing, alignment, and negative space are intentional.
- **Style coherence:** visual treatment supports audience and message.
- **Craft:** no obvious artifacts, pseudo-text, broken elements, or distracting decoration.
- **Output readiness:** feels like a finished design, not a wireframe or generic AI image.

A test passes when every criterion scores at least 3 and Brief Fidelity, Layout Fit, Hierarchy, and Output Readiness score at least 4. Record scores and concrete evidence; do not pass based on subjective praise alone.

## UAT Report Format
- Test ID and brief
- Selected archetype (LA-ID + title)
- Why this layout fits
- Design direction (hierarchy, focal point, composition, palette/style, text strategy)
- Result / image reference
- Scorecard (8 criteria)
- Issues found
- Targeted revision
- Pass / Fail

## Test Discipline
- Do not force the candidate layout if another LA archetype clearly fits better; document the actual selection and rationale.
- Candidate layouts are hypotheses, not mandatory answers.
- Do not change multiple design variables in one revision unless necessary.
- Keep exact supplied copy unchanged.
- If generated text is inaccurate, report it and recommend controlled typesetting for critical text.
- Run tests individually so failures can be attributed to a specific decision.
