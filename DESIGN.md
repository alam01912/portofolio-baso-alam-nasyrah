---
name: Executive Kinetic
colors:
  surface: '#0a122a'
  surface-dim: '#0a122a'
  surface-bright: '#313852'
  surface-container-lowest: '#050d25'
  surface-container-low: '#131a33'
  surface-container: '#171e37'
  surface-container-high: '#212942'
  surface-container-highest: '#2c344d'
  on-surface: '#dbe1ff'
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#dbe1ff'
  inverse-on-surface: '#282f49'
  outline: '#8c909f'
  outline-variant: '#424754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e6a'
  primary-container: '#4d8eff'
  on-primary-container: '#00285d'
  inverse-primary: '#005ac2'
  secondary: '#d0bcff'
  on-secondary: '#3c0091'
  secondary-container: '#571bc1'
  on-secondary-container: '#c4abff'
  tertiary: '#4cd7f6'
  on-tertiary: '#003640'
  tertiary-container: '#009eb9'
  on-tertiary-container: '#002f38'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#0a122a'
  on-background: '#dbe1ff'
  surface-variant: '#2c344d'
typography:
  display-hero:
    fontFamily: Manrope
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Manrope
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Manrope
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Manrope
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
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

This design system balances institutional authority with kinetic digital fluency. Structured around a **70% Professional, 20% Creative, 10% Gen Z** distribution, it serves high-achieving professionals in public administration, civic technology, policy, and executive communication.

- **Tone & Mood:** Authoritative yet forward-looking, poised, crisp, and digitally native. It avoids stale governmental bureaucracy and over-saturated youth trends, grounding itself in Swiss precision with energetic tactical highlights.
- **Visual Style:** Contemporary Modular Bento Grid. Clean informational architecture framed by crisp hairline borders, deep midnight tones, and controlled chromatic flares (cyan and electric violet) that signal technological agility and creative lateral thinking.
- **Target Audience:** Public sector decision-makers, institutional recruiters, civic partners, and contemporary cross-sector collaborators who value structural rigor paired with high-modern digital presentation.

## Colors

The palette establishes gravity through deep oceanic navies while deploying high-vibrancy electric accents for visual anchors and directional flow.

- **Primary (`#3B82F6`):** Electric Cobalt. Drives core interactive states, primary actions, progress metrics, and focal links.
- **Secondary (`#8B5CF6`):** Soft Violet. Assigned to creative milestones, secondary pill badges, and contextual highlights that signify creative or strategic versatility.
- **Tertiary (`#06B6D4`):** Crisp Cyan. Used sparingly for status indicators, micro-metrics, interactive pings, and hover transitions.
- **Neutrals & Surfaces:**
  - `Canvas / Background Base`: Deep Obsidian Navy (`#0B132B`)
  - `Surface Tier 1 (Cards, Modules)`: Navy Slate (`#1C2541`)
  - `Surface Tier 2 (Interactive Elements, Hover Surfaces)`: Deep Indigo Tint (`#243256`)
  - `Text Primary`: Off-White Slate (`#F8FAFC`)
  - `Text Secondary`: Muted Steel (`#94A3B8`)
  - `Hairline Borders`: Translucent Ice (`rgba(248, 250, 252, 0.08)`)

## Typography

The typographic hierarchy combines **Manrope** for authoritative, geometric display headings and metadata badges with **Inter** for neutral, utilitarian body copy.

- Display and headline levels rely on tight tracking (`-0.02em` to `-0.03em`) to project modern editorial sharpness.
- `label-sm` leverages uppercase tracking for category eyebrows, department tags, and status trackers across governance and civic project cards.
- Line heights remain open in body copy to preserve legibility when presenting dense policy frameworks, whitepapers, or governance case studies.

## Layout & Spacing

The layout is built upon a **12-column fluid grid** designed specifically for asymmetric Bento box arrangements.

- **Canvas Limits & Breakpoints:** Desktop max content width is constrained to `1280px` centered, transitioning to 8 columns on tablet (`768px - 1023px`) and a 4-column stack on mobile (`< 768px`).
- **Bento Card Proportions:** Bento units follow modular span ratios (e.g., span 8 for primary case studies, span 4 for bio/metrics, span 6/6 for dual comparative initiatives).
- **Rhythm & Safe Margin:** Grid outer margins scale from `1.25rem` on mobile screens up to `3rem` on wide displays to ensure prominent framing. Internal card padding strictly enforces `space-lg` (24px) for visual breathing room.

## Elevation & Depth

This system avoids heavy drop shadows, opting instead for **tonal layering**, **hairline translucencies**, and **ambient color diffusion**:

- **Surface Tiers:**
  - *Base:* `#0B132B`
  - *Layer 1 (Bento Cards):* `#1C2541` encased in a crisp `1px solid rgba(248, 250, 252, 0.08)` border.
  - *Layer 2 (Floating Popovers, Flyouts, Quick Action bars):* `#243256` encased in `1px solid rgba(59, 130, 246, 0.25)`.
- **Glassmorphism Tiers:** Sticky top navigation and floating modal overlays employ `backdrop-filter: blur(16px)` with `background: rgba(11, 19, 43, 0.75)`.
- **Ambient Chromatic Glows:** Interactive hovers do not shift physically upward; they project a subtle directional glow: `box-shadow: 0 0 24px -4px rgba(59, 130, 246, 0.25)`. High-priority creative achievements utilize a soft dual aura blending `#8B5CF6` and `#06B6D4` at `15%` opacity.

## Shapes

The design uses a balanced curvature standard (`Level 2 - Rounded`):
- **Base Components:** Inputs, buttons, and micro-pills default to `0.5rem` (8px).
- **Structural Containers:** Bento grid cards, banners, and modal dialogs adopt `rounded-lg` (1rem / 16px) or `rounded-xl` (1.5rem / 24px) to retain modern digital fluidity without feeling overly playful or toy-like.
- **Status Tags & Category Badges:** Full-pill execution (`rounded-full` / 9999px) for sharp contrast against square-aligned layout modules.

## Components

### Buttons
- **Primary:** Solid `#3B82F6` surface, `#F8FAFC` label, `8px` corner radius. Hover triggers `#2563EB` with an ambient glow of `0 0 16px rgba(59, 130, 246, 0.4)`.
- **Secondary (Creative Accent):** `#1C2541` surface with a dynamic gradient hairline outline (`#8B5CF6` to `#06B6D4`), font weight `600`.
- **Ghost / Minimal:** Transparent background with `#94A3B8` text, shifting to `#F8FAFC` with a micro-glow border on hover.

### Bento Cards
- Contained modular blocks with `#1C2541` base, `16px` border radius, and `1px` translucent border.
- Cards host an optional interactive gradient header border that shifts from neutral slate to tertiary cyan on mouseover.

### Chips & Badges
- **Status Tags (Public Sector / Roles):** Pill-shaped with dark translucent backgrounds (`rgba(59, 130, 246, 0.12)`), solid border (`rgba(59, 130, 246, 0.3)`), and high-contrast text. Includes a pulsing indicator dot (`#06B6D4`) for live engagements or active governance mandates.

### Form Inputs & Search Fields
- Inset container styling using `#0E1733`, `1px` border of `rgba(248, 250, 252, 0.1)`. Focus state produces an electric border transition to `#3B82F6` and an ambient field wash.

### Interactive Checkboxes & Radio Elements
- Custom rounded boxes (`4px` for check, full circular for radio) utilizing deep `#1C2541` fills with high-luminance check vectors rendered in `#06B6D4`.

### Specialized Domain Components
- **Metric Highlight Tiles:** Bento modules pairing an ultra-clean numeral display (`display-hero`) with a micro-label (`label-sm`) in muted steel to quantify public sector reach and measurable operational outcomes.
- **Policy Timeline Trackers:** Minimal vertical line indicators using muted `#243256`, accented by active nodes illuminated in electric cyan.