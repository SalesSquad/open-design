# Taimi Design System

> **Source:** [taimilaunch.vercel.app/fi](https://taimilaunch.vercel.app/fi)  
> **Category:** Brands · **Surface:** web  
> **Generated:** 2026-06-26 · **Status:** AI-refined from live brand extraction

## Product Overview

Taimi ("Kasvun uusi aika") is a Finnish family-tech platform that connects household chores, learning, and saving — currently recruiting 200 developer families. The brand embodies **Calm Nordic trust-tech**: warm, trustworthy, technologically sophisticated but organic. Designed for families with children, never childish. Compliance-first without legal heaviness. AI appears as a supportive layer, never the protagonist.

**Primary surfaces:** landing page (`/fi`), family dashboard, child tasks/learning views, parent admin.

**Core capabilities:** task management, allowance tracking, savings goals, learning modules, family calendar.

### Product Context

- **Target audience:** Finnish families with children aged 4–14. Parents as primary decision-makers, children as daily users.
- **Key differentiators:** Finnish curriculum-aligned learning, local banking integration, GDPR-by-design, parent-controlled permissions.
- **Design philosophy:** Remove invisible mental load from parents. Every interaction should reduce work, not add it.

## Brand Identity

- **Tagline:** *Kasvun uusi aika* (A new era of growth)
- **Tagline (long):** *Pienistä teoista suuri kasvu* (Great growth from small deeds)
- **Brand adjectives:** lämmin, luotettava, puhdas, pohjoismainen, inhimillinen
- **Tone:** Calm Nordic trust-tech — authoritative but warm, never cold or sterile. Finnish-language copy is concise and direct. No jargon, no hype. Speaks to parents as equals.

### Messaging Pillars

1. **Arjen helpottaminen** — Taimi removes invisible meta-work, never adds it.
2. **Lapsen kasvu** — Every small deed builds responsibility, skills, and independence.
3. **Perheen yhteinen aika** — When daily life flows, time remains for what matters most.
4. **Turvallinen teknologia** — Built on the Finnish curriculum, parent-controlled.

### Vocabulary

**Use:** perhearki, kasvu, vastuu, oppiminen, säästäminen, kotityöt, yhdessä, pienistä teoista suuri kasvu, kehittäjäperhe

**Avoid:** revoluutio, mullistava, tekoälyavusteinen, disruptio, scale-up, exit

## Package Contents

```
.
├── DESIGN.md                          # Canonical design system rules (this file's source)
├── README.md                          # This file — package guide
├── SKILL.md                           # Agent-facing skill instructions
├── colors_and_type.css                # Reusable CSS token file
├── brand.html                         # Generated brand kit page
├── fonts/
│   ├── fonts.css                      # @font-face declarations (Fraunces, Inter)
│   ├── fraunces-100-900.woff2         # Display typeface
│   ├── inter-100-900.woff2            # Body typeface
│   └── manifest.json                  # Font manifest
├── logos/                             # Wordmark + icon assets (SVG, PNG, WebP at multiple sizes)
├── imagery/                           # Brand photography + CGI teacher portraits
├── context/
│   └── input-DESIGN.md               # Original color extraction input
├── preview/                           # Focused preview cards
│   ├── colors-primary.html
│   ├── typography-specimens.html
│   ├── spacing-tokens.html
│   ├── components-buttons.html
│   ├── components-cards.html
│   ├── components-inputs.html
│   └── brand-assets.html
└── ui_kits/
    └── app/
        ├── index.html                 # Applied interface kit
        └── README.md                  # UI kit reuse guide
```

## Preview Manifest

| Preview card | Purpose | Key tokens/components |
|---|---|---|
| `preview/colors-primary.html` | Full palette swatches with role labels | All 7 brand colors + dark variants |
| `preview/typography-specimens.html` | Type scale, weights, pairing demo | Fraunces (display) + Inter (body), 6 sizes |
| `preview/spacing-tokens.html` | Spacing scale visual reference | 8px baseline grid, 10 spacing steps |
| `preview/components-buttons.html` | Button variants: primary, secondary, ghost, pill CTA | Deep Forest, Nordic Gold, radius tokens |
| `preview/components-cards.html` | Card variants with imagery, text, actions | 16px radius, Cream White surface, 1px border |
| `preview/components-inputs.html` | Form inputs, selects, focus states | Sage focus ring, Warm Sand borders |
| `preview/brand-assets.html` | Logo variants + brand mark showcase | Wordmark forest/white, icon sizes |

## Reuse Workflow

1. **Import tokens** — Link `colors_and_type.css` into your project for all CSS custom properties.
2. **Apply fonts** — Copy `fonts/` and their `@font-face` declarations.
3. **Use DESIGN.md** — Give this DESIGN.md to any coding agent (Claude, Codex, Cursor) as the brand contract.
4. **Reference preview cards** — Inspect `preview/*.html` to verify the visual direction before building.
5. **Start from UI kit** — `ui_kits/app/index.html` is a runnable, composed interface example.
6. **Extend with SKILL.md** — Agents load SKILL.md for guided Taimi-branded generation.

## Preserved Assets

### Fonts
- `fonts/fraunces-100-900.woff2` (Fraunces, variable weight 100–900)
- `fonts/inter-100-900.woff2` (Inter, variable weight 100–900)

### Logos
- `logos/wordmark.svg` — Vector primary (Fraunces 600, Deep Forest #1c3d2e)
- `logos/wordmark-forest.webp` — Accent-color variant
- `logos/wordmark-white.webp` — Dark background variant
- `logos/wordmark-transparent.webp` — Transparent background
- `logos/wordmark-*.png` — Raster sizes 16–2048px
- `logos/icon-512.png`, `logos/icon-192.png` — App icons

### Imagery
Family photography (warm natural light, filmic grain) and CGI teacher portraits (Matias, Suvi).

## Review Checklist

- [ ] Color palette matches brand (Warm Cream background, Deep Forest accent)
- [ ] Typography uses Fraunces for display, Inter for body
- [ ] Cards have 16px radius, 1px Warm Sand border
- [ ] Buttons use 10px radius (standard) or pill (CTAs)
- [ ] Focus rings use Sage (#7a9e7e), 2px with 2px offset
- [ ] Finnish copy is concise, warm, jargon-free
- [ ] Noise texture overlay present at 3.5% opacity
- [ ] Dark mode available via `.dark` class or `prefers-color-scheme`
