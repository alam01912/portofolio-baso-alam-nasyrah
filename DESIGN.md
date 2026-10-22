---
name: Executive Dossier
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#45464d'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#75777e'
  outline-variant: '#c5c6ce'
  surface-tint: '#525e7d'
  primary: '#000a24'
  on-primary: '#ffffff'
  primary-container: '#14213d'
  on-primary-container: '#7c89aa'
  inverse-primary: '#b9c6ea'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#000e0c'
  on-tertiary: '#ffffff'
  tertiary-container: '#002724'
  on-tertiary-container: '#3e978e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#b9c6ea'
  on-primary-fixed: '#0d1b36'
  on-primary-fixed-variant: '#3a4664'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#9cf2e8'
  tertiary-fixed-dim: '#80d5cb'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#00504a'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.5rem
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: '1.15'
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: '1.25'
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.65'
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.04em
  caption:
    fontFamily: Inter
    fontSize: 0.6875rem
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses a refined, editorial approach tailored for executive portfolios and curriculum vitae. The visual tone balances technical authority with quiet elegance, specifically engineered to respect the scanning habits of recruiters, executive search partners, and engineering leadership.

The aesthetic philosophy draws from modern architectural publication design: ample breathing room, disciplined typographic hierarchy, micro-delight via polished interactive accents, and a distinct lack of visual clutter. The interface conveys deliberate craftsmanship, clarity of thought, and high-impact professionalism without relying on decorative gimmicks.

## Colors

The palette establishes an immediate sense of focus and gravitas. The foundation leverages high-contrast readability against a clean backdrop, avoiding pure black to minimize eye fatigue during extended review sessions.

- **Primary (`#14213D` - Deep Navy)**: Used for primary calls-to-action, section anchors, key milestone headings, and high-emphasis interface elements.
- **Secondary (`#64748B` - Slate Gray)**: Governs meta-information, dates, secondary labels, structural dividers, and supportive context.
- **Tertiary (`#0F766E` - Refined Teal)**: Functions as the surgical accent for key achievements, verification badges, interactive hover states, active filter chips, and highlighted metrics.
- **Neutral / Text (`#0F172A` - Slate 900)**: Serves as the primary reading color for optimal legibility. Body copy and descriptive paragraphs rest comfortably at `#475569` (Slate 600).
- **Canvas & Surface**: The canvas foundation rests at `#F8FAFC` (Soft Clean), while elevated interactive blocks and cards utilize `#FFFFFF` (Pure Surface) to create crisp, natural layering.

## Typography

The type system pairs **Plus Jakarta Sans** for display, structural titles, and interface badges with **Inter** for long-form narrative, impact summaries, and project descriptions. 

This pairing establishes structural authority in section divisions while ensuring effortless scanning across bullet points, employment achievements, and technical stack catalogs. Tabular numeric variants are enforced across metrics, dates, and quantitative indicators to preserve visual cadence in data-rich sections.

## Layout & Spacing

The layout is built upon an 8pt vertical rhythm mapped inside a 12-column responsive grid container with a maximum content boundary of 1200px.

- **Desktop (>= 1024px)**: 12-column grid, `margin: 3rem`, `gutter: 1.5rem`. Asymmetric column splits (e.g., 4 columns for sticky biographical navigation, 8 columns for chronological career progression and case studies) optimize review flow.
- **Tablet (768px - 1023px)**: 8-column grid, `margin: 2rem`, `gutter: 1.25rem`. Complex side-by-side matrices collapse into prioritized vertical stacks.
- **Mobile (< 768px)**: 4-column grid, `margin: 1.25rem`, `gutter: 1rem`. Full edge-to-edge content blocks with preserved internal padding to prevent cramped body lines.

## Elevation & Depth

Visual hierarchy uses a refined hybrid approach: low-contrast borders combined with ultra-soft ambient drop shadows to isolate elements without distracting the reader.

- **Flat Canvas Tier**: The `#F8FAFC` foundation provides a clean surface for non-containerized sections and headings.
- **Card Tier (Resting)**: Background `#FFFFFF`, wrapped in a crisp 1px border (`#E2E8F0`), supported by an ambient drop shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.03)`.
- **Card Tier (Interactive / Hover)**: Translates vertically by `-2px`, transitioning smoothly to border color `#CBD5E1` and an elevated shadow: `0 10px 25px -5px rgba(20, 33, 61, 0.07), 0 8px 10px -6px rgba(20, 33, 61, 0.04)`.
- **Flyouts & Modals**: Used for deep-dive case studies and full resume previews: `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 10px 10px -5px rgba(15, 23, 42, 0.04)` over a subtle `backdrop-filter: blur(8px)` with 40% `#0F172A` mask.

## Shapes

The design uses a clean, architectural shape language (Soft / Level 1). Base components utilize crisp `0.25rem` (4px) or `0.375rem` (6px) corners, while larger cards and featured project modules use `0.5rem` (8px). 

Pill geometries are reserved strictly for taxonomy badges, status indicators, and contact badges to create visual contrast against rectangular containers.

## Components

### Buttons
- **Primary Action (e.g., Download Resume, Contact)**: Solid `#14213D` fill, pure white text, font `label-md`, 8px corner radius (`rounded-lg`), padding `0.75rem 1.5rem`. Subtle hover transition to `#1E293B` with a gentle 2px elevation lift.
- **Secondary Action**: Background `#FFFFFF`, 1px solid border (`#CBD5E1`), text `#0F172A`. Hover switches border to `#0F766E` and text to `#0F766E`.
- **Tertiary / Link Action**: Inline text link with `label-md` weight in `#0F766E`, paired with an explicit directional micro-icon with a 2px hover slide effect.

### Badges & Filter Chips
- **Skill / Technology Chips**: Neutral `#F1F5F9` background, `#475569` text, `label-sm` weight, uppercase tracking, pill-shaped radius (`9999px`), padding `0.25rem 0.75rem`.
- **Highlight Badges (e.g., "Featured Project", "Promotion")**: Soft teal tint `#F0FDFA` background, `#0F766E` border and text.

### Timeline System (Experience & Education)
- Continuous vertical rail: 2px solid `#E2E8F0` positioned along the left axis.
- Node indicators: Solid `#FFFFFF` circular discs (12px outer diameter) bordered with a 2.5px solid ring in `#0F766E` for current roles and `#94A3B8` for past tenures.
- Content clusters: Clear temporal tags, job titles set in `headline-sm`, organization names in `label-md`, followed by bulleted impact statements set in `body-md`.

### Project & Case Study Cards
- Bounded inside `#FFFFFF` shells with 1px border `#E2E8F0`.
- Internal structure: High-contrast header with project title and external reference link, narrative description (2-3 lines max for scanning), followed by an inline row of technology chips and verified outcome metrics.

### Inputs & Contact Fields
- Subtle `#F8FAFC` background resting inside a 1px `#CBD5E1` border with a 6px corner radius.
- Active focus state: Canvas shifts to `#FFFFFF`, border shifts to `#0F766E`, supplemented by a 3px outer glow ring of `rgba(15, 118, 110, 0.15)`. Labels sit statically above inputs in `label-sm` font.