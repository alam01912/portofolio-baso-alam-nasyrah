---
name: Executive Kinetic Portfolio
colors:
  surface: '#0f131d'
  surface-dim: '#0f131d'
  surface-bright: '#353944'
  surface-container-lowest: '#0a0e18'
  surface-container-low: '#171b26'
  surface-container: '#1c1f2a'
  surface-container-high: '#262a35'
  surface-container-highest: '#313540'
  on-surface: '#dfe2f1'
  on-surface-variant: '#c3c6d7'
  inverse-surface: '#dfe2f1'
  inverse-on-surface: '#2c303b'
  outline: '#8d90a0'
  outline-variant: '#434655'
  surface-tint: '#b4c5ff'
  primary: '#b4c5ff'
  on-primary: '#002a78'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#0053db'
  secondary: '#d2bbff'
  on-secondary: '#3f008e'
  secondary-container: '#6001d1'
  on-secondary-container: '#c9aeff'
  tertiary: '#4cd7f6'
  on-tertiary: '#003640'
  tertiary-container: '#00788c'
  on-tertiary-container: '#d7f6ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#eaddff'
  secondary-fixed-dim: '#d2bbff'
  on-secondary-fixed: '#25005a'
  on-secondary-fixed-variant: '#5a00c6'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#0f131d'
  on-background: '#dfe2f1'
  surface-variant: '#313540'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.03em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
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

This design system expresses a high-caliber executive presence engineered specifically for elite tech leadership, senior product management, and high-impact design engineering. The persona blends corporate credibility with progressive digital artistry. It projects technical rigor, strategic vision, and decisive clarity.

The visual style synthesizes **Modern Executive Minimalism** with restrained **Futuristic Glassmorphism** and subtle ambient luminescent glows. Surfaces are structured, orderly, and scannable for enterprise HR leaders and hiring committees, while displaying precision-crafted micro-interactions, controlled radial aura backdrops, and luminous translucent cards. The atmosphere is confident, clean, and engineered without visual clutter or frivolous decorative friction.

## Colors

The core palette operates around a dual personality: authoritative obsidian anchors contrasted with energetic photonic accents.

- **Primary (`#2563EB`)**: Electric Blue represents structural precision, trust, and enterprise leadership. Used for dominant interactive elements, primary CTAs, critical career milestone metrics, and focused borders.
- **Secondary (`#7C3AED`)**: Royal Violet introduces executive sophistication, strategic creativity, and depth. Utilized in dual-tone linear gradients, high-level impact metrics, and selected category tags.
- **Tertiary (`#06B6D4`)**: Electric Cyan serves as a hyper-focused signal accent for real-time status indicators ("Available for Hire", verified badges, KPI growth deltas) and luminous edge highlights.
- **Neutral (`#0B0F19`)**: Deep Dark Navy provides the canvas baseline. It creates depth far superior to pure `#000000`, anchoring nested glass layers cleanly.

### Color Tokens & Modes

#### Dark Mode (Default)
- **Background Root**: `#0B0F19`
- **Surface Elevation 1 (Card/Container)**: `#0F172A` with 70% opacity and 1px border of `rgba(255, 255, 255, 0.08)`
- **Surface Elevation 2 (Elevated Glass / Hover)**: `#1E293B` at 60% opacity with `rgba(56, 189, 248, 0.2)` subtle rim
- **Text Primary**: `#F8FAFC`
- **Text Secondary**: `#94A3B8`
- **Text Muted**: `#64748B`

#### Light Mode (Executive Clean)
- **Background Root**: `#F8FAFC`
- **Surface Elevation 1**: `#FFFFFF` with soft drop border `rgba(15, 23, 42, 0.06)`
- **Surface Elevation 2**: `rgba(255, 255, 255, 0.85)` over soft linear pastel gradients (`rgba(37, 99, 235, 0.04)` to `rgba(124, 58, 237, 0.04)`)
- **Text Primary**: `#0F172A`
- **Text Secondary**: `#475569`
- **Text Muted**: `#94A3B8`

## Typography

The typographic hierarchy is designed for rapid executive consumption. Recruiters spend an average of 6–10 seconds evaluating profiles; therefore, structural readability and weight differentiation are critical.

- **Plus Jakarta Sans** delivers modern geometric strength across display headers, role titles, and categorical labels. Tight letter spacing (`-0.03em` to `-0.015em`) creates a polished, high-density editorial lockup.
- **Inter** handles high-volume narrative descriptions, achievement bullets, impact summaries, and technical competencies. It ensures neutral, optical legibility across high-DPI and standard monitors.
- **Micro-Labels & Metrics** rely on uppercase `label-sm` with widened letter-spacing (`0.05em`) to categorize dates, organizational units, and tech stack tags with clinical clarity.

## Layout & Spacing

The portfolio is structured around a central 12-column responsive fluid grid with a maximum content boundary of `1280px`. 

### Breakpoints & Adaptive Rhythm
- **Desktop (1024px and above)**: 12 columns, `1.5rem` (`24px`) gutters, `3rem` (`48px`) margins. Two- and three-column arrangements allow scannable timelines, sticky executive summaries, and portfolio case tiles.
- **Tablet (768px – 1023px)**: 8 columns, `1.25rem` (`20px`) gutters, `2rem` (`32px`) margins. Side-by-side modules collapse to primary content + secondary meta blocks.
- **Mobile (below 768px)**: 4 columns, `1rem` (`16px`) gutters, `1.25rem` (`20px`) outer margin. Layout reflows into a strict single-column chronological feed.

Vertical rhythm adheres strictly to an 8px baseline grid (`space-xs` = 4px, `space-sm` = 8px, `space-md` = 16px, `space-lg` = 24px, `space-xl` = 40px, with hero separation extending up to 80px).

## Elevation & Depth

Visual depth is achieved through layered frosted surfaces and localized light diffusion rather than muddy drop shadows.

- **Surface Tiers**:
  - **Level 0 (Canvas)**: Solid deep navy `#0B0F19` with ambient radial color meshes (`rgba(37, 99, 235, 0.12)` top right, `rgba(124, 58, 237, 0.08)` bottom left).
  - **Level 1 (Cards & Feed Panels)**: Translucent surface `rgba(15, 23, 42, 0.65)`, backdrop blur of `16px`, bordered by a subtle vector outline `1px solid rgba(255, 255, 255, 0.08)`.
  - **Level 2 (Popovers, Sticky Navigation, Active Cards)**: Elevated surface `rgba(30, 41, 59, 0.8)`, backdrop blur of `24px`, bordered by `1px solid rgba(255, 255, 255, 0.15)`.
- **Luminescence & Glows**:
  - Hover states on interactive cards trigger an electric radial gradient bloom behind the surface: `0 0 32px -8px rgba(37, 99, 235, 0.25)`.
  - Executive action elements (e.g., "Download CV", "Contact Baso") carry an accent ring glow: `0 4px 20px -2px rgba(37, 99, 235, 0.45)`.

## Shapes

The interface embraces a modern rounded architecture (`level 2`) to balance authority with approachable, polished digital tactility.

- Standard UI components (interactive buttons, input fields, and pill chips) utilize a base border-radius of `0.5rem` (`8px`).
- Card containers, timeline node modules, and portfolio case previews utilize `rounded-lg` (`1rem` / `16px`) to produce soft, structured silhouettes.
- Floating modal sheets, hero preview frames, and spotlight banners utilize `rounded-xl` (`1.5rem` / `24px`).
- Badges, status markers, and micro-tags utilize full pill encapsulation (`rounded-full` / `9999px`) to distinguish visual taxonomy from structural blocks.

## Components

### Buttons & CTAs
- **Primary Executive Button**: Solid gradient fill (`#2563EB` to `#1D4ED8`), white text (`Plus Jakarta Sans 600`), `0.5rem` radius, subtle glow on rest, intensifying glow and `-1px` Y-axis lift on hover.
- **Secondary Glass Button**: Frosted translucent fill (`rgba(255, 255, 255, 0.05)`), border `1px solid rgba(255, 255, 255, 0.15)`, text `#F8FAFC`. On hover, border transitions to `#38BDF8`.
- **Tertiary Link**: Clean inline typography with a 1px cyan animated bottom border and trailing directional arrow.

### Glassmorphism Badges & Chips
- **Skill / Technology Chips**: Translucent dark fill (`rgba(15, 23, 42, 0.6)`), 1px border (`rgba(255, 255, 255, 0.08)`), uppercase label text, padding `4px 10px`.
- **Status Indicator Badge ("Open to Executive Roles")**: Pill-shaped glass container with an active pulsing electric cyan dot (`#06B6D4`), surrounded by an ultra-soft radial aura.

### Experience Timeline & Portfolio Cards
- **Experience Cards**: Elevated container featuring company logo, role title, duration label, and quantifiable bullet points (highlighting numbers and metrics in `#38BDF8`). Features a vertical cyan/violet connecting gradient rail on the left flank.
- **Portfolio Project Cards**: Dual-zone layout with a high-fidelity visual preview framed on top, followed by an executive case summary, key deliverables, metrics, and technology tag chips below. Hover initiates a glass brightening transition and subtle border illuminate.

### Form Inputs & Executive Contact Field
- **Input Fields**: Background `rgba(15, 23, 42, 0.5)`, border `1px solid rgba(255, 255, 255, 0.1)`. Focus state illuminates the perimeter with a 1px vibrant blue ring (`#2563EB`) and an inner ambient glow.
- **Checkboxes & Radios**: Custom custom-drawn squared-circle controls with deep navy backgrounds, transitioning to vibrant blue with crisp cyan checkmark glyphs when active.

### Metrics & Impact Highlight Tile
- Dedicated high-contrast component for recruiters: large numerical KPI (`Plus Jakarta Sans 800`, gradient clip from `#38BDF8` to `#8B5CF6`) positioned above a concise impact description (e.g., "+140% ARR", "12M+ Active Users").