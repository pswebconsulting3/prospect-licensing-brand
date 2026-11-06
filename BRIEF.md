# BRIEF — Prospect Licensing & Consulting

## Goal

Re-skin an existing, working WordPress + Elementor site whose design is roughly a decade behind the quality of the business it represents. The site converts today; the redesign must not put that at risk. Success is that a returning customer recognises the site instantly and a new visitor takes it seriously.

## Constraint that shapes everything

**Content is frozen.** Every section, every link, every sentence stays. This is a re-skin, not a restructure. Where a section looks wrong, the fix is layout and typography, never rewriting or removing it. The only structural change sanctioned is collapsing the three duplicate hero copies in the DOM into one responsive section.

## Audience

Owner-operators and small-to-midsize trucking company owners across all 50 states, concentrated in Illinois. Many are first-generation immigrant business owners; a significant share of the client base is Bulgarian-American, which is why chamber membership sits on the home page.

They are not evaluating design. They arrive with a deadline, a penalty, or a truck that cannot legally move. The site's job is to make a stressed operator believe someone competent has this handled, and then get them to the right service page in as few decisions as possible.

## Page jobs

| Page | Its one job |
|---|---|
| Home | Establish competence, then route to the right service category fast |
| Service detail (~35 pages) | Explain one service plainly and start it. The highest-value template in the project |
| Trucking Insights | Deadline awareness — this is what brings people back |
| About | Trust in Vessela specifically. The reviews name her, not the company |
| Contact / Free Consultation | Convert, with the phone number never more than one glance away |

## Signature

**The horizon.** The dark hero resolves into white through a single asymmetric curve, and the three proof figures sit on a white shelf straddling the seam. It is drawn from the client's own world — the dusk road horizon in the hero photograph — and it is the one visually bold moment on the page.

**One signature moment per page.** Everything else stays quiet so it lands. Do not repeat the curve at other section boundaries.

The supporting structural device, used freely, is the **hairline rule**: service categories, deadline rows, insight panels and reviews are separated by 1px lines rather than enclosed in bordered cards. For a compliance business, a ruled list reads as a record. A grid of shadowed cards reads as a template.

## Radius personality

Pill-shaped controls inside generously rounded containers. The radius scale encodes hierarchy rather than putting one value on everything: 999px on every button, 40px on the hero and full-bleed panels, 24px on feature panels, 12px on content cards, 6px on inputs.

## Motion direction

Restrained and reactive only. Hover and focus transitions at 120–200ms, link arrows that shift 4px, nothing else. No scroll-triggered entrances, no counters animating from zero, no parallax. `prefers-reduced-motion` zeroes every duration.

Rationale: the current site animates its statistics up from zero, which means the numbers read as "0" for the first moment a visitor sees them. On a site whose credibility rests on 21 years and 10,000+ permits, the proof should be legible immediately.

## The one deliberate risk

**Georgia body copy under Playfair Display headings.**

Three families, two of them serifs, one of them a system font from 1993 — this is not the safe choice, and executed loosely it reads dated rather than established. It is deliberate. The audience is a 21-year-old family compliance business serving people who are handing over money on trust, and a serif register signals a firm that has been here a while. The risk is managed by holding Playfair to h1–h3 only, giving Georgia 1.7 line height and a 68ch measure, and letting Poppins do all the functional work below h3.

If it fails, it will fail by looking heavy. The correction is tightening the measure and raising the neutral contrast, not swapping the families.

## Anti-generic rules for this project

- No gradient orbs or blobs behind the hero
- No shadowed identical cards in a grid — hairlines instead
- No numbered markers (01 / 02 / 03); Prospect's content is not a sequence
- No stock photography of trucks beyond the existing hero image
- No second accent colour competing with the blue. No green, including on the WhatsApp glyph
- Blue never exceeds roughly 10% of a page's surface area
