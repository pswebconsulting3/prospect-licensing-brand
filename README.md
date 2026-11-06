# prospect-licensing-brand

Brand source for **Prospect Licensing & Consulting Inc** (prospectlicensing.com).
Maintained by PS Web Consulting.

This is a **client brand layer**. It carries no design system of its own — it fills in the BRAND block on top of the agency house baseline and is attached alongside it in Claude Design. If a value is not in here, the baseline decides it.

## What's in here

```
├── BRIEF.md            the project brief — read this first
├── DESIGN-SYSTEM.md    the reasoning and the usage rules
├── brand.css           the tokens. the source of truth for values
├── content/
│   └── homepage.md     the real page copy, frozen
├── references/         approved hero + the three inspiration references
└── demo/
    └── landing.html    the approved home page, built on the tokens
```

## Order of authority

1. `brand.css` — if this and the document disagree, the CSS wins
2. `BRIEF.md` — scope, audience, and the rules that constrain design decisions
3. `DESIGN-SYSTEM.md` — the reasoning behind the values, and how to apply them
4. The house baseline — anything the three files above do not specify

## Project scope

A visual re-skin of an existing WordPress + Elementor site. **Page structure and all copy stay as they are.** No new sections, no removed sections, no rewritten text. See BRIEF.md before proposing anything that changes either.

## Implementation

Tokens load through the child theme. Values mirror into Elementor Global Colors and Global Fonts so the client's own editing controls stay usable. Elementor's Google Fonts loader stays off; Playfair Display and Poppins are self-hosted, Georgia is a system font.

## Status

| | |
|---|---|
| Version | 0.2 |
| Tokens | approved |
| Home page design | approved |
| Service detail template | not started |
| Live implementation | not started |
