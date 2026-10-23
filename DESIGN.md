---
name: Executive Precision
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#1d4ed8'
  on-secondary: '#ffffff'
  secondary-container: '#4069f2'
  on-secondary-container: '#fffbff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#2f1500'
  on-tertiary-container: '#c76c00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#dce1ff'
  secondary-fixed-dim: '#b7c4ff'
  on-secondary-fixed: '#001551'
  on-secondary-fixed-variant: '#0039b5'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Manrope
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
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
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  data-metric:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system targets senior hiring managers, executive recruiters, and enterprise operations leaders seeking precision, discretion, and operational excellence in administrative coordination and document governance. The visual language blends Modern Corporate clarity with subtle editorial restraint: sharp structural rhythm, immaculate typographic hierarchy, and deliberate micro-accents. 

The aesthetic communicates quiet competence, rigorous organizational discipline, and modern efficiency. It rejects decorative clutter in favor of structured data sheets, legible timeline paths, and metric-first storytelling that allows credentials and business impact to lead.

## Colors
The palette balances authoritative weight with actionable focus:

- **Primary (`#0F172A`)**: Deep executive slate navy. Governs primary headlines, active navigation states, high-priority surfaces, and prominent callouts.
- **Secondary (`#1D4ED8`)**: Structured cobalt blue. Used for primary CTAs, active timeline checkpoints, hyperlinked metrics, and focused interactive states.
- **Tertiary (`#D97706`)**: Muted executive amber/gold. Reserved for high-value validation badges, clearance seals, key career milestones, and tenure metrics.
- **Neutral (`#64748B` / `#0F172A`)**: Crisp off-white (`#F8FAFC`) canvas grounded by cool light gray (`#F1F5F9`) card foundations and structural borders (`#E2E8F0`). Text layers transition smoothly from dark charcoal (`#0F172A`) down to muted slate (`#475569`).

## Typography
Typographic rhythm combines the geometric poise of **Manrope** for titles and numeric callouts with the scannability of **Inter** for descriptions, tables, and metadata.

- **Tabular Figures**: Force tabular figures (`font-variant-numeric: tabular-nums`) on all performance numbers, KPIs, dates, and administrative metric grids.
- **Section Headers**: Use uppercase treatment with `label-sm` tracking on section sub-labels (e.g., "CORE COMPETENCIES", "CAREER RECORD").
- **Scanning Scenarios**: Ensure clear weight separation: bold lead titles with muted secondary descriptors for high glance-value by recruiters reviewing content under tight timeframes.

## Layout & Spacing
The layout relies on a structured 12-column grid system capped at a maximum width of 1200px, centering the profile while preserving expansive gutter space.

- **Desktop (>= 1024px)**: 12-column layout. Asymmetrical 4:8 split layouts (left rail for contact, identity, credentials; right panel for career trajectory, project case sheets, data logs).
- **Tablet (768px - 1023px)**: 8-column layout. Content columns shift to stacked configurations with 1.5rem gutters and 2rem section boundaries.
- **Mobile (< 768px)**: Single-column linear flow. Sidebars re-sequence cleanly beneath the primary executive bio.
- **Vertical Rhythm**: Generous rhythm (2.5rem to 4rem between macro career phases; 0.75rem to 1.25rem between role items) to maintain high visual breathing room.

## Elevation & Depth
Elevation is maintained using crisp boundary definition and subtle atmospheric lift rather than pronounced drop shadows:

- **Structural Outlines**: Cards, badges, and containers leverage a consistent 1px stroke (`border-slate-200` / `#E2E8F0`).
- **Low-Opacity Ambient Shadows**:
  - *Standard Card*: `0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.05)`
  - *Hover / Active Lift*: `0 8px 16px -4px rgba(15, 23, 42, 0.06), 0 4px 6px -2px rgba(15, 23, 42, 0.03)`
- **Tonal Contrast**: Pure white (`#FFFFFF`) containers resting upon a cool tint background (`#F8FAFC`), giving natural elevation without heavy shadow dependency.

## Shapes
Shapes express precision through clean corners and purposeful pill geometries:

- **Containers & Cards**: Base radius of `0.5rem` (`rounded-md` / `rounded-lg`) to preserve an executive, structured silhouette.
- **Skill Badges & Metadata Chips**: Full pill curves (`9999px`) provide visual distinction between structural layout containers and granular taxonomy tags.
- **Form Controls & Search Bars**: Controlled `0.375rem` to `0.5rem` radius for a clean, professional finish.

## Components

### Buttons
- **Primary**: Solid Deep Navy (`#0F172A`) fill, crisp white text, subtle hover transition to Slate (`#1E293B`).
- **Secondary Accent**: Solid Cobalt Blue (`#1D4ED8`) fill, white text, for conversion actions (e.g., "Download Executive CV", "Schedule Interview").
- **Tertiary / Ghost**: Transparent fill with `1px` border (`#CBD5E1`), text `#0F172A`, hover background `#F1F5F9`.

### Chips & Badges
- **Skill & Technical Chips**: Light slate fill (`#F1F5F9`), text `#334155`, subtle pill outline (`#E2E8F0`).
- **Accreditation / Metric Badges**: Muted Amber/Gold surface tint (`#FEF3C7`), text `#B45309`, border `#FDE68A` for honors, security clearances, and audit-level certifications.

### Timeline Connectors (Career Track)
- Continuous vertical border (`2px` solid `#E2E8F0`) positioned along the left axis.
- Nodes marked with hollow circular rings (`8px` diameter, `#CBD5E1` border) that fill solid Cobalt (`#1D4ED8`) for the current role or key milestones.

### Cards & Detail Modules
- Background `#FFFFFF`, border `1px solid #E2E8F0`, padding `1.5rem`.
- Header zone houses the role, tenure dates (`tabular-nums`), and organization pill badge; the inner body accommodates bulleted impact metrics.

### Input Fields & Administrative Data Filters
- Background `#FFFFFF`, border `1px solid #CBD5E1`, text `#0F172A`.
- Active focus state: `2px` ring in `#1D4ED8` with zero vertical shift.

### Document Preview Cards
- Compact data grid tiles featuring file icon indicators (`.pdf`, `.xlsx`, `.docx`), file size tokens, and quick verification badges for document management proof-of-work.