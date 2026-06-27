---
name: Taimi Design System
description: Finnish family-tech brand design system. Calm Nordic trust-tech — warm, trustworthy, organic. Use when building or styling Taimi-branded web interfaces, landing pages, dashboards, or family-focused UI.
user-invocable: true
---

# Taimi Design System

## What is inside

This is the canonical design-system package for **Taimi** — a Finnish family-tech platform (*Kasvun uusi aika*). It contains:

- **DESIGN.md** — Full design rules: palette, typography, voice & tone, imagery, layout posture, motion
- **colors_and_type.css** — Reusable CSS custom properties (colors, type scale, spacing, radius, shadows, focus rings)
- **fonts/** — Fraunces (display) and Inter (body) as variable-weight WOFF2 files
- **logos/** — Wordmark and icon in SVG, PNG, and WebP at multiple sizes
- **imagery/** — Brand photography and CGI teacher portraits
- **preview/** — 7 focused HTML preview cards for visual inspection
- **ui_kits/app/** — Runnable, composed interface kit
- **brand.html** — Self-contained brand kit page

## Source context

- **Live product:** [taimilaunch.vercel.app/fi](https://taimilaunch.vercel.app/fi)
- **Extraction method:** Brand extraction from live landing page + user-provided logo assets + ChatGPT-generated hero imagery
- **Refinement:** AI-refined with human review of color extraction, typography pairing, and voice alignment
- **Evidence:** Color extraction input in `context/input-DESIGN.md`

## When to use this skill

- Building a new Taimi-branded landing page or marketing site
- Creating a family dashboard, child task view, or parent admin interface
- Generating a pitch deck with Taimi visual identity
- Any web prototype that needs the Calm Nordic trust-tech aesthetic
- Design review: use preview cards to validate visual direction before coding

## How to use

1. **Load the design system** — Point your agent to `DESIGN.md` as the brand contract.
2. **Link the tokens** — Include `colors_and_type.css` for all CSS custom properties.
3. **Apply fonts** — Copy `fonts/` and use the `@font-face` rules from `fonts/fonts.css`.
4. **Reference preview cards** — Open `preview/*.html` in a browser to see the tokens and components rendered.
5. **Start from the UI kit** — `ui_kits/app/index.html` is a runnable, composed interface example.

### Agent prompt template

```
You are building a Taimi-branded web interface. Follow the design system:

- DESIGN.md: [load this file]
- colors_and_type.css: [link for tokens]
- fonts/: [Fraunces for display, Inter for body]
- Language: Finnish (warm, concise, direct)
- Tone: Calm Nordic trust-tech — authoritative but warm, never cold
```

## Design system highlights

### Palette
- Background: `#f5f0e8` (Warm Cream)
- Surface: `#faf7f2` (Cream White)
- Text: `#1a1a18` (Warm Ink)
- Accent: `#1c3d2e` (Deep Forest)
- CTA: `#c4924a` (Nordic Gold)

### Typography
- Display: Fraunces (100–900), tracking -0.02em
- Body: Inter (100–900), 16px base
- Section labels: 13px uppercase, 0.12em letter-spacing, Nordic Gold

### Layout
- 8px baseline grid
- Cards: 16px radius, 1px Warm Sand border
- Buttons: 10px radius (standard), pill (CTAs)
- Max prose width: 65ch
- Focus rings: Sage (#7a9e7e), 2px + 2px offset
- Transitions: 150ms cubic-bezier(0.4, 0, 0.2, 1)

### Voice
- **Adjectives:** lämmin, luotettava, puhdas, pohjoismainen, inhimillinen
- **Finnish copy:** concise and direct, no jargon, no hype
- **Messaging:** arjen helpottaminen, lapsen kasvu, perheen yhteinen aika, turvallinen teknologia

### Imagery
- Warm natural-light photography with filmic grain overlay (3.5% opacity)
- Authentic family moments, not stock
- CGI teacher portraits that feel approachable
- Full-bleed heroes with cream/forest color grading
